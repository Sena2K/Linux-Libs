all:
		
	gcc -W -Wall -Wextra -pedantic -std=c17 -c util.c -o util.o
	gcc -shared -fPIC -o libutil.so util.c
	
	
	gcc -W -Wall -Wextra -pedantic -std=c17 -c main.c -o main.o
	gcc main.o -L. -lutil -Wl,-rpath=. -o ms04


clean:
	rm -f main.o
	rm -f util.o
	rm -f libutil.o
	rm -f ms04
