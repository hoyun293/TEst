CC = gcc
CFLAG += -g
OBJ = main.o read.o write.o


test : $(OBJ)
	$(CC) -o test $(OBJ)
main.o : io.h main.c
	gcc -c main.c
read.o : io.h read.c
	gcc -c read.c
write.o : io.h write.c
	gcc -c write.c
clean : 
	rm -rf *.o
