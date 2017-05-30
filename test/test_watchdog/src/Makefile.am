AUTOMAKE_OPTIONS=foreign


AM_CPPFLAGS=-I$(top_srcdir)/platform/common/inc   \
	 -I$(top_srcdir)/test/test_watchdog/inc 


test_watchdog_LDADD =   \
                $(top_srcdir)/platform/common/src/libCommon.a

noinst_PROGRAMS = test_watchdog
test_watchdog_SOURCES=test_watchdog.cpp
