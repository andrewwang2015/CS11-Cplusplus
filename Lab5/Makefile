CXXFLAGS = -std=c++14 -Wall

all : genmaze

genmaze : maze.o genmaze.o
	$(CXX) $(CXXFLAGS) $^ -o $@ $(LDFLAGS)

clean :
	rm -f genmaze *.o *~

.PHONY : all clean

