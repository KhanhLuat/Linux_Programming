main.o : main.c
	gcc -c -o main.o main.c
test: main.o
	gcc -o make main.o
clean:
	rm -rf main.o
	rm -rf make