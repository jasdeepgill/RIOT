include ../Makefile.tests_common

DISABLE_MODULE += auto_init

# for native we can go do a couple of more operations in reasonable time...
ifneq (,$(filter native,$(BOARD)))
  CFLAGS += -DTEST_ITER=100000000
endif

include $(RIOTBASE)/Makefile.include
