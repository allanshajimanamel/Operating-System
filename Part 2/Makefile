TARGET= OS_PRG3
CC= gcc
LDFLAGS= -pthread
SRC = crazyprofessor.c
DEBUG= -ggdb

all: $(TARGET)

crazyprofessor: OS_PRG3.c
	$(CC) $(LDFLAGS) $(DEBUG) $(SRC) -o $(TARGET)
	
# let's clean up the mess
clean:
	rm -rf OS_PRG3


