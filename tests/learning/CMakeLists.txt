IF (HAVE_DIMEMBED)
	ADD_SUBDIRECTORY (dimensionalembedding)
ENDIF (HAVE_DIMEMBED)

IF (HAVE_STATISTICS)
    ADD_SUBDIRECTORY (statistics)
ENDIF (HAVE_STATISTICS)

IF (HAVE_ATOMSPACE)
    ADD_SUBDIRECTORY (PatternMiner)
    ADD_SUBDIRECTORY (pattern-index)
    ADD_SUBDIRECTORY (miner)
ENDIF (HAVE_ATOMSPACE)
