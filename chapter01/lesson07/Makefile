src=$(wildcard ./*.c)
objs=$(patsubst *.c *.o $(src))
target=app
$(target):$(src)
	gcc $(src) -o $(target)
%.o:%.c
	gcc -c $< -o $@
clean:
	rm $(objs)