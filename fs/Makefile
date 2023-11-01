CFLAGS = -ggdb
CFLAGS += -I../include/

vfs: $(patsubst %.c,%.o,$(wildcard *.c))
	$(LD) $^ -o $@
%.o: %.c
	$(CC) $(CFLAGS) $^ -o $@
