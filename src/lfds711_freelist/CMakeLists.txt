MESSAGE(STATUS "\tBuilding freelist...")

ADD_LIBRARY(freelist STATIC
	lfds711_freelist_cleanup.c
	lfds711_freelist_init.c
	lfds711_freelist_pop.c
	lfds711_freelist_push.c
	lfds711_freelist_query.c)
