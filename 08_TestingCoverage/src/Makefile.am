lib_LTLIBRARIES = libbuf.la

if COND_GCOV
	CFLAGS += -fprofile-arcs -ftest-coverage -O0 -g
endif

#gcov:
#	gcov .libc/libbuf -t -j -k