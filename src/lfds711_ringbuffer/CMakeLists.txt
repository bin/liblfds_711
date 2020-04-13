MESSAGE(STATUS "\tBuilding ringbuffer...")

ADD_LIBRARY(ringbuffer STATIC
	lfds711_ringbuffer_cleanup.c
	lfds711_ringbuffer_init.c
	lfds711_ringbuffer_query.c
	lfds711_ringbuffer_read.c
	lfds711_ringbuffer_write.c)
