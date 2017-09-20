CC = gcc
#LDFLAGS  -lX11
LDFLAGS=
# options I'll pass to the compiler.
#CFLAGS ?=
#CFLAGS=-c -Wall
CP = cp
MKDIR_P = mkdir -p
OUT_DIR = build
SOURCES=main.c test.c
OBJECTS=$(SOURCES:.c=.o)
EXECUTABLE=acliwerp

directories: $(OUT_DIR)

build:
    ${MKDIR_P} $(OUT_DIR)