vfs: $(patsubst %.c,%.o,$(wildcard *.c))
	$(LD) $^ -o $@
%.o: %.c
	$(CC) $^ -ggdb -o $@
