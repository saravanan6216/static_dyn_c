$(CC) = gcc

final:	main.o add.o sub.o
	$(CC) main.o add.o sub.o -o y
main.o: main.c
	$(CC) -c main.c
add.o:	add.c
	$(CC) -c add.c
sub.o:	sub.c 
	$(CC) -c sub.c
clean:
	rm -rif *o y
