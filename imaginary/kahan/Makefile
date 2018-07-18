TOP = ../..
include $(TOP)/mk/boilerplate.mk
include $(TOP)/mk/target.mk

FAST_OPTS = 250000
NORM_OPTS = 2000000
SLOW_OPTS = 2000000

#We enforce the use of sse here.
#We do so because precision between x64 and x86 would differ otherwise.
SRC_HC_OPTS += -package array -msse2
