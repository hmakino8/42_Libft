# Libft

### Program name
`libft.a`
### Turn in files
`*.c`, `libft.h`, `Makefile`
### Usage
To compile the library, run:
```sh
$ make
```
### Description
Write your own library, containing an extract of important functions for your cursus.<br>
You are free to add any function to your libft as you see fit.

## Functions List 
- #### Functions from `<ctype.h>` library
|||
-|-
[`ft_isascii`](https://github.com/hmakino8/42tokyo/blob/master/42cursus/Libft/ft_isascii.c)|test for ASCII character.
[`ft_isalnum`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_isalnum.c)|alphanumeric character test.
[`ft_isalpha`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_isalpha.c)|alphabetic character test.
[`ft_isdigit`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_isdigit.c)|decimal-digit character test.
[`ft_isprint`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_isprint.c)|printing character test (space character inclusive).*
[`ft_tolower`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_tolower.c)|upper case to lower case letter conversion.
[`ft_toupper`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_toupper.c)|lower case to upper case letter conversion.
- #### Functions from `<stdlib.h>` library
|||
-|-
[`ft_atoi`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_atoi.c)|convert ASCII string to integer.
- #### Functions from `<strings.h>` library
|||
-|-
[`ft_bzero`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_bzero.c)|write zeroes to a byte string.
[`ft_memset`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_memset.c)|write a byte to a byte string.
[`ft_memchr`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_memchr.c)|locate byte in byte string.
[`ft_memcmp`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_memcmp.c)|compare byte string.
[`ft_memmove`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_memmove.c)|copy byte string.
[`ft_memcpy`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_memcpy.c)|copy memory area.
[`ft_strlen`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_strlen.c)|find length of string.
[`ft_strchr`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_strchr.c)|locate character in string (first occurrence).
[`ft_strrchr`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_strrchr.c)|locate character in string (last occurence).
[`ft_strnstr`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_strnstr.c)|locate a substring in a string (size-bounded).
[`ft_strncmp`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_strncmp.c)|compare strings (size-bounded).
[`ft_strlcpy`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_strlcpy.c)|copy strings.
[`ft_strdup`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_strdup.c)|save a copy of a string (with malloc).
[`ft_strlcat`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_strlcat.c)|size-bounded string concatenation.
- #### Non-standard functions
|||
|-|-|
[`ft_putchar_fd`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_putchar_fd.c)|output a character to given file.
[`ft_putstr_fd`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_putstr_fd.c)|output string to given file.
[`ft_putendl_fd`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_putendl_fd.c)|output string to given file with newline.
[`ft_putnbr_fd`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_putnbr_fd.c)|output integer to given file.
[`ft_itoa`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_itoa.c)|convert integer to ASCII string.
[`ft_strtrim`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_strtrim.c)|trim beginning and end of string with the specified characters.
[`ft_strjoin`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_strjoin.c)|concatenate two strings into a new string (with malloc).
[`ft_split`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_split.c)|split string, with specified character as delimiter, into an array of strings.
[`ft_strmapi`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_strmapi.c)|create new string from modifying string with specified function.
- #### Linked list functions
|||
-|-
[`ft_lstnew`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_lstnew.c)|create new list.
[`ft_lstadd_front`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_lstadd_front.c)|add new element at the front of list.
[`ft_lstadd_back`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_lstadd_back.c)|add new element at the end of list.
[`ft_lstdelone`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_lstdelone.c)|delete element from list.
[`ft_lstiter`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_lstiter.c)|apply function to content of all list's elements.
[`ft_lstmap`](https://github.com/hmakino8/42_Libft/blob/main/Libft/ft_lstmap.c)|apply function to content of all list's elements into new list.
