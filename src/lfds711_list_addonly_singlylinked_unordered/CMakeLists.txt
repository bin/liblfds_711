MESSAGE(STATUS "\tBuilding singly-linked list (add-only, un-ordered)...")

ADD_LIBRARY(list_unordered STATIC
	lfds711_list_addonly_singlylinked_unordered_cleanup.c
	lfds711_list_addonly_singlylinked_unordered_get.c
	lfds711_list_addonly_singlylinked_unordered_init.c
	lfds711_list_addonly_singlylinked_unordered_insert.c
	lfds711_list_addonly_singlylinked_unordered_query.c)
