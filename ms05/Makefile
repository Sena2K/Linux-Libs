all:
		
	gcc -W -Wall -Wextra -pedantic -std=c17 -c util.c -o util.o
	gcc -shared -fPIC -o libutil.so util.c
	
	
	gcc -W -Wall -Wextra -std=c17 main.c -o ms05


clean:
	rm -f main.o
	rm -f util.o
	rm -f libutil.o
	rm -f ms05
