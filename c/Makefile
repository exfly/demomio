CC = gcc

all: epoll_lt_example epoll_et_example echoman
 
epoll_lt_example: epoll_lt_example.c
	$(CC) -Wall -Werror -o $@ epoll_lt_example.c

epoll_et_example: epoll_et_example.c
	$(CC) -Wall -Werror -o $@ epoll_et_example.c

echoman:
	$(CC) echoman.c -o echoman -Werror -g

clean:
	@rm -v echoman epoll_lt_example epoll_et_example
