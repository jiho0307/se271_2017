CPPFLAGS=-Wall -std=c++14 -pedantic-errors

#all: intlist intlist_inclassdef intlist_dynamic 
all: intlist_dynamic intlist

intlist_initial: intlist_initial.cpp main.cpp
	g++ $(CPPFLAGS) -D INITIAL -o intlist_initial intlist_initial.cpp main.cpp

intlist_inclassdef: intlist_inclassdef.cpp main.cpp
	g++ $(CPPFLAGS) -D INCLASS -o intlist_inclassdef intlist_inclassdef.cpp main.cpp

intlist_dynamic: intlist_dynamic.cpp main.cpp
	g++ $(CPPFLAGS) -D DYNAMIC -o intlist_dynamic intlist_dynamic.cpp main.cpp

intlist: intlist.cpp main.cpp
	g++ $(CPPFLAGS) -D FINAL -o intlist intlist.cpp main.cpp

.PHONY: clean

clean:
	rm -rf intlist intlist_inclassdef intlist_dynamic

