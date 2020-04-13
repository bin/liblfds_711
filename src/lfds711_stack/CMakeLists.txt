MESSAGE(STATUS "\tBuilding stack...")

ADD_LIBRARY(stack STATIC
	lfds711_stack_cleanup.c
	lfds711_stack_init.c
	lfds711_stack_pop.c
	lfds711_stack_push.c
	lfds711_stack_query.c)
