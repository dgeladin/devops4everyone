CC=g++
CFLAGS=-g -Wall
all: fib

fib.o: clean
        $(CC) -c fib.cpp

fib: fib.o
        $(CC) -o fib fib.o

clean:
        rm fib fib.o
