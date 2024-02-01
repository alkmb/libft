# Custom C Library (42 Project)

This is a comprehensive C library providing a set of functions for various tasks, including memory manipulation, type conversion, string manipulation, list/structure operations, and more. Below is an overview of the different categories of functions available in this library.


## Directory Structure

libft/
├── alloc/
│   ├── ft_calloc.c
│   └── ft_crazy_free.c
├── chars/
│   ├── ft_isalnum.c
│   ├── ft_isalpha.c
│   ├── ft_isascii.c
│   ├── ft_isdigit.c
│   ├── ft_ishexdigit.c
│   ├── ft_isprint.c
│   ├── ft_isspace.c
│   ├── ft_tolower.c
│   └── ft_toupper.c
├── files/
│   ├── ft_get_next_line.c
│   ├── ft_putchar_fd.c
│   ├── ft_putendl_fd.c
│   ├── ft_putnbr_fd.c
│   └── ft_putstr_fd.c
├── lists/
│   ├── ft_lstadd_back_bonus.c
│   ├── ft_lstadd_front_bonus.c
│   ├── ft_lstclear_bonus.c
│   ├── ft_lstdelone_bonus.c
│   ├── ft_lstiter_bonus.c
│   ├── ft_lstlast_bonus.c
│   ├── ft_lstmap_bonus.c
│   ├── ft_lstnew_bonus.c
│   └── ft_lstsize_bonus.c
├── memory/
│   ├── ft_bzero.c
│   ├── ft_memchr.c
│   ├── ft_memcmp.c
│   ├── ft_memcpy.c
│   ├── ft_memmove.c
│   └── ft_memset.c
├── numbers/
│   ├── ft_atof.c
│   ├── ft_atoi.c
│   └── ft_itoa.c
├── printf/
│   ├── ft_printf.c
│   ├── put_numbers.c
│   └── put_strings.c
└── strings/
    ├── ft_split.c
    ├── ft_strchr.c
    ├── ft_strdup.c
    ├── ft_striteri.c
    ├── ft_strjoin.c
    ├── ft_strlcat.c
    ├── ft_strlcpy.c
    ├── ft_strlen.c
    ├── ft_strmapi.c
    ├── ft_strncmp.c
    ├── ft_strnstr.c
    ├── ft_strrchr.c
    ├── ft_strtrim.c
    └── ft_substr.c

- Alloc Functions: Custom implementations for memory allocation and freeing.
- Chars Functions: Functions for character manipulation and checking.
- Files Functions: Functions for file-related operations.
- Lists Functions: Operations on linked lists (bonus functions included).
- Memory Functions: Memory manipulation functions.
- Numbers Functions: Functions for numeric operations.
- Printf Functions: Implementation of a simplified printf function.
- Strings Functions: String manipulation functions.
