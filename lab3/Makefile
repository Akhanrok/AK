all: lab3

lab3: calculator.o main.o
	g++ calculator.o main.o -o lab3
	
calculator.o: calculator.cpp
	g++ -c calculator.cpp
	
main.o: main.cpp
	g++ -c main.cpp
	
clean:
	rm -rf *0 lab3
