# file: GNUMakefile
#

# define a target for the application
#
all: foo

# define a target to link the application
#	g++ -L./ -lfoo foo.o -o foo
#
foo: foo.o foo_00.o
	g++ foo.o foo_00.o -o foo

# define a target to compile the application
#
foo.o: foo.cc
	g++ -O2 -c foo.cc -o foo.o

foo_00.o: foo_00.cc
	g++ -O2 -c foo_00.cc -o foo_00.o

# define a target to clean the directory
#
clean:
	rm -f foo.o
	rm -f foo

#
# end of file


