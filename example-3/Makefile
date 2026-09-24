.PHONY: all clean run show

CXX = g++
CXXFLAGS = -Wall -Wextra -std=c++11

SOURCE = Kazino-Royal.cpp
TARGET = kazino-royal
OBJ = $(SOURCE:.cpp=.o)

all: $(TARGET)

$(TARGET): $(OBJ)
	$(CXX) $(CXXFLAGS) $(OBJ) -o $(TARGET)

$(OBJ): $(SOURCE)
	$(CXX) $(CXXFLAGS) -c $(SOURCE) -o $(OBJ)

run: $(TARGET)
	./$(TARGET)

show:
	@echo "CXX = $(CXX)"
	@echo "CXXFLAGS = $(CXXFLAGS)"
	@echo "SOURCE = $(SOURCE)"
	@echo "TARGET = $(TARGET)"

clean:
	rm -f $(TARGET) $(OBJ)
