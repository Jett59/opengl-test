all: game.exe

game.exe: $(patsubst %.c,%.o,$(shell ls | grep .c))
	ld -o game.exe $(shell ls | grep .o)

clean:
	rm $(shell ls | grep .o) $(shell ls | grep .exe)