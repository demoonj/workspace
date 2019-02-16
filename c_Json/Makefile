CXXFLAGS=-Werror -Wall -g

jsonxx_test: jsonxx_test.cpp jsonxx.o

jsonxx.o: jsonxx.h jsonxx.cpp

test: jsonxx_test
	./jsonxx_test

.PHONY: clean
clean:
	rm -f jsonxx_test *.o *~
