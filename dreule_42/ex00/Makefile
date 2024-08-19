CC = gcc
CFLAGS = -Wall -Wextra -Werror

SRCS = main.c functions.h ft_strlen.c ft_putstr.c 
OBJS = $(SRCS:.c=.o)

NAME = rush-02

all: $(NAME)

$(NAME): $(OBJS)
	$(CC) $(CFLAGS) -o $(NAME) $(OBJS)

clean:
	rm -f $(OBJS)

fclean: clean
	rm -f $(NAME)

re: fclean all

%.o: %.c
	$(CC) $(CFLAGS) -c $< -o $@
