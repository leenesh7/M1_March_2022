all: tt

ttr:main.o train ticket reservation.o
	gcc -Wall -o pd main.o train ticket reservation.o

main.o:main.c
	gcc -c -Wall main.c

train ticket reservation.o:train ticket reservation.c
	gcc -c -Wall train ticket reservation.c
