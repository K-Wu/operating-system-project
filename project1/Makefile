SRC_PATH = src
INCLUDE_PATH = include
CXX_FLAGS = --std=c++11
OBJECTS = main.o
TARGET = main

all: $(OBJECTS)
	g++ -o $(TARGET) $(OBJECTS) $(CXX_FLAGS) -pthread

main.o: $(SRC_PATH)/main.cpp
	g++ -c $(SRC_PATH)/main.cpp $(CXX_FLAGS) -pthread

clean:
	-rm $(TARGET) $(OBJECTS) $(TARGET).exe
