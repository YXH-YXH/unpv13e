include ../Make.defines

PROGS =	daytimetcpcli daytimetcpcli1 daytimetcpcli2 daytimetcpcli3 \
		daytimetcpsrv daytimetcpsrv1 daytimetcpsrv2 daytimetcpsrv3 \
		daytimetcpcliv6 daytimetcpsrvv6 \
		daytimetcpcli_exam-1_3 daytimetcpcli_exam-1_4 \
		daytimetcpcli_exam-1_5 daytimetcpsrv_exam-1.5 \
		byteorder

all:	${PROGS}

daytimetcpcli_exam-1_3:	daytimetcpcli_exam-1_3.o
		${CC} ${CFLAGS} -o $@ daytimetcpcli_exam-1_3.o ${LIBS}

daytimetcpcli_exam-1_4:	daytimetcpcli_exam-1_4.o
		${CC} ${CFLAGS} -o $@ daytimetcpcli_exam-1_4.o ${LIBS}

daytimetcpcli_exam-1_5: daytimetcpcli_exam-1_5.o
		${CC} ${CFLAGS} -o $@ daytimetcpcli_exam-1_5.o ${LIBS}

daytimetcpsrv_exam-1_5: daytimetcpsrv_exam-1.5.o
		${CC} ${CFLAGS} -o $@ daytimetcpsrv_exam-1.5.o ${LIBS}

daytimetcpcli:	daytimetcpcli.o
		${CC} ${CFLAGS} -o $@ daytimetcpcli.o ${LIBS}

daytimetcpcli1:	daytimetcpcli1.o
		${CC} ${CFLAGS} -o $@ daytimetcpcli1.o ${LIBS}

daytimetcpcli2:	daytimetcpcli2.o
		${CC} ${CFLAGS} -o $@ daytimetcpcli2.o ${LIBS}

daytimetcpcli3:	daytimetcpcli3.o
		${CC} ${CFLAGS} -o $@ daytimetcpcli3.o ${LIBS}

daytimetcpsrv:	daytimetcpsrv.o
		${CC} ${CFLAGS} -o $@ daytimetcpsrv.o ${LIBS}

daytimetcpsrv1:	daytimetcpsrv1.o
		${CC} ${CFLAGS} -o $@ daytimetcpsrv1.o ${LIBS}

daytimetcpsrv2:	daytimetcpsrv2.o
		${CC} ${CFLAGS} -o $@ daytimetcpsrv2.o ${LIBS}

daytimetcpsrv3:	daytimetcpsrv3.o
		${CC} ${CFLAGS} -o $@ daytimetcpsrv3.o ${LIBS}

daytimetcpcliv6:	daytimetcpcliv6.o
		${CC} ${CFLAGS} -o $@ daytimetcpcliv6.o ${LIBS}

daytimetcpsrvv6:	daytimetcpsrvv6.o
		${CC} ${CFLAGS} -o $@ daytimetcpsrvv6.o ${LIBS}

byteorder:	byteorder.o
		${CC} ${CFLAGS} -o $@ byteorder.o ${LIBS}

clean:
		rm -f ${PROGS} ${CLEANFILES}
