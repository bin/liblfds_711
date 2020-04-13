CMAKE_MINIMUM_REQUIRED(VERSION 3.14)

SET(CMAKE_C_STANDARD 11)

PROJECT(lfds)

MESSAGE(STATUS "Building libldfs...")

INCLUDE_DIRECTORIES(${CMAKE_SOURCE_DIR}/inc)

ADD_SUBDIRECTORY(${CMAKE_SOURCE_DIR}/src)

# Have to create a dummy target here
ADD_LIBRARY(lfds STATIC ${CMAKE_SOURCE_DIR}/src/.dummy.c)

TARGET_LINK_LIBRARIES(lfds STATIC
	btree
	freelist
	hash
	list_ordered
	list_unordered
	misc
	prng
	queue_bounded_many_many
	queue_bounded_single_single
	queue_unbounded_many_many
	ringbuffer
	stack)
