.MAIN: all

all:
	gcc -Wall -Wextra -Werror -c includes/ft.h srcs/ft_putchar.c srcs/ft_putstr.c srcs/ft_strlen.c srcs/ft_strcmp.c srcs/ft_swap.c
	mv ft_putchar.o ft_putstr.o ft_strlen.o ft_strcmp.o ft_swap.o srcs/
	ar rcs libft.a srcs/ft_putchar.o srcs/ft_putstr.o srcs/ft_strlen.o srcs/ft_strcmp.o srcs/ft_swap.o includes/ft.h.gch

libft.a:
	gcc -Wall -Wextra -Werror -c includes/ft.h srcs/ft_putchar.c srcs/ft_putstr.c srcs/ft_strlen.c srcs/ft_strcmp.c srcs/ft_swap.c
	mv ft_putchar.o ft_putstr.o ft_strlen.o ft_strcmp.o ft_swap.o srcs/
	ar rcs libft.a srcs/ft_putchar.o srcs/ft_putstr.o srcs/ft_strlen.o srcs/ft_strcmp.o srcs/ft_swap.o includes/ft.h.gch

clean:
	rm -f srcs/*.o includes/ft.h.gch

fclean:
	rm -f srcs/*.o includes/ft.h.gch libft.a

re:
	rm -f srcs/*.o includes/ft.h.gch libft.a
	gcc -Wall -Wextra -Werror -c includes/ft.h srcs/ft_putchar.c srcs/ft_putstr.c srcs/ft_strlen.c srcs/ft_strcmp.c srcs/ft_swap.c
	mv ft_putchar.o ft_putstr.o ft_strlen.o ft_strcmp.o ft_swap.o srcs/
	ar rcs libft.a srcs/ft_putchar.o srcs/ft_putstr.o srcs/ft_strlen.o srcs/ft_strcmp.o srcs/ft_swap.o includes/ft.h.gch
