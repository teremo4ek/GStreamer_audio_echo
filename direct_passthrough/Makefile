CC=gcc
LIBS=`pkg-config gstreamer-0.10 --libs`
CFLAGS=-Wall `pkg-config gstreamer-0.10 --cflags`

main: main.c
	$(CC) $(LIBS) $(CFLAGS) -o direct_passthrough main.c

clean:
	rm direct_passthrough
