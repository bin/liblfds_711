MESSAGE(STATUS "\tBuilding b-tree (add-only, un-balanced)...")

ADD_LIBRARY(btree STATIC
	lfds711_btree_addonly_unbalanced_cleanup.c
	lfds711_btree_addonly_unbalanced_get.c
	lfds711_btree_addonly_unbalanced_init.c
	lfds711_btree_addonly_unbalanced_insert.c
	lfds711_btree_addonly_unbalanced_query.c)
