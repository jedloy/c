CC = gcc
CFLAGS = -Wall -Wextra -Werror -std=c99 -pedantic

SRC = $(wildcard *.c)
OBJ = $(SRC:c=o)
BIN = main

.PHONY: all
all: $(OBJ)
	$(CC) $^ -o $(BIN)

.PHONY: clean
clean:
	rm -f $(OBJ) $(BIN)
