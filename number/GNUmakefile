CC=gcc
PROG=number
SRCS=number.c

all:${PROG}

${PROG}:${SRCS}
	${CC} ${SRCS} -o ${PROG}

install:${PROG}
	cp ${PROG} /usr/local/bin/

clean:
	rm -f ${PROG}
