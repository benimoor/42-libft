LIBFT
This is the "libft" project, part of the curriculum at 42 school. The goal of this project is to create our own implementation of various standard C library functions, as well as additional utility functions that will be used throughout the rest of our studies at the school.

Getting started
To get started with this project, you'll need a basic understanding of the C programming language, as well as a Unix-like environment to compile and run the code. To build the library, simply run make from the project directory, which will compile all of the source files and create a libft.a static library.

Library functions
The "libft" library contains the following standard library functions, each implemented from scratch:

ft_memset
ft_bzero
ft_memcpy
ft_memccpy
ft_memmove
ft_memchr
ft_memcmp
ft_strlen
ft_strlcpy
ft_strlcat
ft_strchr
ft_strrchr
ft_strnstr
ft_strncmp
ft_atoi
ft_isalpha
ft_isdigit
ft_isalnum
ft_isascii
ft_isprint
ft_toupper
ft_tolower

In addition to these standard library functions, the library also contains the following utility functions:

ft_calloc
ft_strdup
ft_substr
ft_strjoin
ft_strtrim
ft_split
ft_itoa
ft_strmapi
ft_putchar_fd
ft_putstr_fd
ft_putendl_fd
ft_putnbr_fd

The library also includes the following bonus functions related to linked lists:

ft_lstnew
ft_lstadd_front
ft_lstsize
ft_lstlast
ft_lstadd_back
ft_lstdelone
ft_lstclear
ft_lstiter
ft_lstmap

To use the "libft" library in your own projects, simply include the libft.h header file and link against the libft.a library file. For example, to compile a file my_program.c that uses the ft_strlen function, you could use the following command:

bash
Copy code
gcc my_program.c -I./includes -L. -lft
This assumes that your my_program.c file includes the libft.h header file, and that the library files are located in the same directory as your source file.

Contributions
This project is a learning exercise and is not intended for external contributions. However, if you find any issues with the library or have suggestions for improvement, please feel free to create an issue or submit a pull request.

Credits
This project was completed as part of the curriculum at 42 school, and was written entirely from scratch by Erik (ergrigor).
