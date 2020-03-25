CC = gcc

all: epoll_example
 
epoll_example: epoll_example.c
	$(CC) -Wall -Werror -o $@ epoll_example.c

echoman:
	$(CC) echoman.c -o echoman -Werror -g

clean:
	@rm -v echoman epoll_example
