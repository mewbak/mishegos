SRCS = $(wildcard *.c) $(wildcard ../vendor/*.c)
OBJS = $(SRCS:.c=.o)

PROG = mishegos

.PHONY: all
all: $(PROG)

$(PROG): $(OBJS)

.PHONY: clean
clean:
	rm -rf $(PROG) $(OBJS)
