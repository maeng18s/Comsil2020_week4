OBJECT = main.o
SRCS = main.cpp

CC= g++
CFLAGS = -c

TARGET = main

$(TARGET):$(OBJECT) LinkedList.h Stack.h
			$(CC) -o $(TARGET) $(OBJECT)

clean: 
		rm $(OBJECT) $(TARGET)

