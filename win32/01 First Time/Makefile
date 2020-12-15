PROG=run.exe
SRCS=app.c
OBJS=$(SRCS:.c=.o)


$(PROG): $(OBJS)
	$(CC) -o $@ $(OBJS)

clean:
	rm -f $(PROG) $(OBJS)