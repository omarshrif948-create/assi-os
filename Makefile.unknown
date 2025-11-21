# Compiler
CC = gcc

# Flags
CFLAGS = -Wall

# Targets
all: process_creation output_program simple_program

# 1. Process Creation
process_creation: process_creation.c
	$(CC) $(CFLAGS) process_creation.c -o process_creation

# 2. Linker Example (Compiles file1.c and file2.c together)
output_program: file1.c file2.c
	$(CC) $(CFLAGS) file1.c file2.c -o output_program

# 3. Loader Example
simple_program: simple_program.c
	$(CC) $(CFLAGS) simple_program.c -o simple_program

# Clean up binaries
clean:
	rm -f process_creation output_program simple_program
