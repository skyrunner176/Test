# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: mvaude <mvaude@student.42.fr>              +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2014/10/29 17:36:12 by mvaude            #+#    #+#              #
#    Updated: 2014/11/06 15:29:52 by slgracie         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = Moulinette

all: $(NAME)

$(NAME):
	@gcc -fPIC -Wall -Werror -Wextra -c ./libft/*.c
	@gcc -fPIC -Werror -Wall -Wextra -shared -o libft.so *.o
	./Mouli-nator

clean:
	@rm -rf *.o
	@rm -rf libft.so

re: clean all
