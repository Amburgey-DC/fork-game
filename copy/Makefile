# Compiler
CXX = g++

# Compiler flags:
# -std=c++23  Use the C++23 standard
# -Wall       Enable all common warnings
# -g          Enable debugging information
CXXFLAGS = -std=c++23 -Wall -g

# Executable
TARGET = Fork

# Source file
SRCS = main2.cpp

# `make`
all: $(TARGET)

$(TARGET): $(SRCS)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(SRCS)

# `make clean`
clean:
	rm -f $(TARGET)

# Prevents "make" from getting confused if a file named "clean" exists
.PHONY: all clean
