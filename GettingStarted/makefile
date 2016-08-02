CC = g++

CPP = $(wildcard src/*.cpp)

EXE = main.exe

LFLAGS = 

$(EXE): $(CPP)
	@$(CC) -o $@ $(LFLAGS) $^ 

RUN: $(EXE)
	@./$^