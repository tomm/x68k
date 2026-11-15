
OBJS = dis68k.o
CFLAGS = -Wall -O0 -g

.c.o:
	$(CC) $(CFLAGS) -c $<

dis68k: $(OBJS)
	$(CC) -o dis68k $(OBJS)

clean:
	rm -f *.o dis68k


