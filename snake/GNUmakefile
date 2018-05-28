CC=cc
PROG=snake
SRCS=snake.c
CFLAGS=-lm -lcurses
INSTALL_DIR=/usr/local/games

all:${PROG}

${PROG}:${SRCS}
	${CC} ${SRCS} -o ${PROG} ${CFLAGS}

clean:
	rm -f ${PROG}

install:${PROG}
	mkdir -p ${INSTALL_DIR}
	cp ${PROG} ${INSTALL_DIR}
