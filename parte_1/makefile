main: main.c sum.o sub.o mul.o div.o arithmetic.h
	gcc -o main main.c sum.o sub.o mul.o div.o

sum.o: sum.c arithmetic.h
	gcc -c sum.c

sub.o: sub.c arithmetic.h
	gcc -c sub.c

mul.o: mul.c arithmetic.h
	gcc -c mul.c

div.o: mul.c arithmetic.h
	gcc -c div.c

clean:
	rm *.o main
