#  ___     ___ ___ 
# |  _|___| . |  _|
# |  _| . | . | . |
# |_| |  _|___|___|
#     |_|          

objs = fp86.o test.o
name = fp86

all: $(name)

$(name): $(objs)
	ld	-o $(name) $(objs)
%.o: %.asm
	as	$< -o $@
clean:
	rm	-rf $(objs) $(name)
