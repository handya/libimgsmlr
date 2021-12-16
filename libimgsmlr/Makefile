# imgsmlr/Makefile

CC=gcc
CFLAGS=-g -Werror -fPIC -I c
LDFLAGS=-L/usr/include

SRCS=imgsmlr.c

all: libimgsmlr.so

libimgsmlr.so: ${SRCS}
	$(CC) ${CFLAGS} ${LDFLAGS} -Werror $^ -shared -o $@

clean:
	rm -f libimgsmlr.so
