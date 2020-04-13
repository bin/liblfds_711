MESSAGE(STATUS "\tBuilding hash table (add-only)...")

ADD_LIBRARY(hash STATIC
	lfds711_hash_addonly_cleanup.c
	lfds711_hash_addonly_get.c
	lfds711_hash_addonly_init.c
	lfds711_hash_addonly_insert.c
	lfds711_hash_addonly_iterate.c
	lfds711_hash_addonly_query.c)
