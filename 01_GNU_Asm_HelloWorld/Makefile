srcs=$(wildcard *.asm)
objs=$(srcs:%.asm=%.o)

all:
	arm-linux-gnueabihf-as $(srcs) -o $(objs)
	arm-linux-gnueabihf-ld $(objs) -o hello
clean:
	rm *.o hello
