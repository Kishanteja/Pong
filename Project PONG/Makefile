CXX := g++
CXXFLAGS := -lncurses
TARGET := pong
SRCS := main.cpp Player.cpp Ball.cpp

default: build

build:
	$(CXX) $(SRCS) $(CXXFLAGS) -o $(TARGET)

run:
	./$(TARGET) || true

clean:
	rm -f $(TARGET)

.PHONY: default build run clean