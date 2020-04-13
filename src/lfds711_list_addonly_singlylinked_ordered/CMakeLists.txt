MESSAGE(STATUS "\tBuilding singly-linked list (add-only, ordered)...")

ADD_LIBRARY(list_ordered STATIC
	lfds711_list_addonly_singlylinked_ordered_cleanup.c
	lfds711_list_addonly_singlylinked_ordered_get.c
	lfds711_list_addonly_singlylinked_ordered_init.c
	lfds711_list_addonly_singlylinked_ordered_insert.c
	lfds711_list_addonly_singlylinked_ordered_query.c)
