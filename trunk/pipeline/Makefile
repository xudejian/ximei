CC=gcc

CFLAGS= -O2 -W -Wall -D_REENTRANT #-DNDEBUG
LDFLAGS=

OBJS=net.o greeting_bonze.o

LIBO=libgreeting_bonze.a

all	: $(LIBO)

$(LIBO) : $(OBJS)
	@-rm -f $@
	$(AR) rcv $@ $^
	@-rm -f $^
clean:
	@-rm -f *.o $(LIBO)
tags:
	ctags *.h *.c

