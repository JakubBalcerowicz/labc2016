sources = zad0.c za1.c zad2.c zad3-1.c zad3-2.c

programs = $(basename $(sources))
objects = $(addsuffix .o, $(programs))

CFLAGS = -Wall -std=c11 -I /opt/X11/include
LDFLAGS = -L /opt/X11/lib
LDLIBS = -lGL -lGLU -lglut -lm

.PHONY : clean
clean :
	-$(RM) $(objects) $(programs) *~

all : $(programs)
