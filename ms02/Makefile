all:
	gcc -W -Wall -Wextra -pedantic -std=c17 -c util.c -o util.o
	ar cr libutil.a util.o
	
	
	gcc -W -Wall -Wextra -pedantic -std=c17 -c main.c -o main.o
	gcc  main.o -L. -lutil -o ms02



clean:
	rm -f main.o
	rm -f util.o
	rm -f libutil.o
	rm -f ms02

