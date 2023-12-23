CXX := clang++
CXXFLAGS := -g -Wall
SOURCE := main.cpp
TARGET := main.bin

.all: build clean

build:
	$(CXX) $(CXXFLAGS) $(SOURCE) -o $(TARGET)

clean:
	rm $(TARGET)
