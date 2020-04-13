MESSAGE(STATUS "\tBuilding miscellaneous support...")

ADD_LIBRARY(misc STATIC
	lfds711_misc_globals.c
	lfds711_misc_internal_backoff_init.c
	lfds711_misc_query.c)
