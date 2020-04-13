MESSAGE(STATUS "\tBuilding prng...")

ADD_LIBRARY(prng STATIC
	lfds711_prng_init.c)
