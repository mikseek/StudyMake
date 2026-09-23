.PHONY: all clean 

CXX = g++
CXXFLAGS = -Wall -o2

SOURCE = Kazino-Royal.cpp
TARGET = hello 

all: $(TARGET)

$(TARGET): $(SOURCE)
	$(CXX) $(CXXFLAGS) $(SOURCE) -o $(TARGET)

clean:
	rm -f $(TARGET) *.O
