
# FIXME - Only supports Linux for now

lib_LTLIBRARIES = libBlocksRuntime.la
include_HEADERS = Block.h Block_private.h

libBlocksRuntime_la_CFLAGS = -std=c99 -Wall -Wextra -W -pedantic

libBlocksRuntime_la_SOURCES = runtime.c data.c config2.h

check_PROGRAMS = blockrt-test

TESTS = blockrt-test

blockrt_test_SOURCES = test/main.c

blockrt_test_CFLAGS = -I. -fblocks

blockrt_test_LDADD = libBlocksRuntime.la


