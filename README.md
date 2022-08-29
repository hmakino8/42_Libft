# Libft
*A project to reimplement the C library.*

## Program name
libft.a
## Turn in files
*.c, libft.h, Makefile
## Usage
To compile the library, run:
```sh
$ make
```
## Description
Write your own library, containing an extract of important functions for your cursus.<br>
You are free to add any function to your libft as you see fit.

## Functions List 
- ### Functions from `<ctype.h>` library
|||
-|-
**`ft_isascii`**|test for ASCII character.
**`ft_isalnum`**|alphanumeric character test.
**`ft_isalpha`**|alphabetic character test.
**`ft_isdigit`**|decimal-digit character test.
**`ft_isprint`**|printing character test (space character inclusive).
**`ft_tolower`**|upper case to lower case letter conversion.
**`ft_toupper`**|lower case to upper case letter conversion.
- ### Functions from `<stdlib.h>` library
|||
-|-
**`ft_atoi`**|convert ASCII string to integer.
- ### Functions from `<strings.h>` library
|||
-|-
**`ft_bzero`**|write zeroes to a byte string.
**`ft_memset`**|write a byte to a byte string.
**`ft_memchr`**|locate byte in byte string.
**`ft_memcmp`**|compare byte string.
**`ft_memmove`**|copy byte string.
**`ft_memcpy`**|copy memory area.
**`ft_memccpy`**|copy string until character found.
- ### Functions from `<string.h>` library
|||
|-|-|
**`ft_strlen`**|find length of string.
**`ft_strchr`**|locate character in string (first occurrence).
**`ft_strrchr`**|locate character in string (last occurence).
**`ft_strstr`**|locate a substring in a string.
**`ft_strnstr`**|locate a substring in a string (size-bounded).
**`ft_strcmp`**|compare strings.
**`ft_strncmp`**|compare strings (size-bounded).
**`ft_strcpy`**|copy strings.
**`ft_strncpy`**|copy strings (size-bounded).
**`ft_strdup`**|save a copy of a string (with malloc).
**`ft_strcat`**|concatenate strings (s2 into s1).
**`ft_strncat`**|concatenate strings (s2 into s1, size-bounded).
**`ft_strlcat`**|size-bounded string concatenation.
- ### Non-standard functions
|||
|-|-|
**`ft_putchar`**|output a character to stdout.
**`ft_putchar_fd`**|output a character to given file.
**`ft_putstr`**|output string to stdout.
**`ft_putstr_fd`**|output string to given file.
**`ft_putendl`**|output string to stdout with newline.
**`ft_putendl_fd`**|output string to given file with newline.
**`ft_putnbr`**|output integer to stdout.
**`ft_putnbr_fd`**|output integer to given file.
**`ft_itoa`**|convert integer to ASCII string.
**`ft_strtrim`**|trim beginning and end of string with the specified characters.
**`ft_strjoin`**|concatenate two strings into a new string (with malloc).
**`ft_split`**|split string, with specified character as delimiter, into an array of strings.
**`ft_strmapi`**|create new string from modifying string with specified function.
- ### Linked list functions
|||
-|-
**`ft_lstnew`**|create new list.
**`ft_lstadd`**|add new element at end of list.
**`ft_lstdelone`**|delete element from list.
**`ft_lstiter`**|apply function to content of all list's elements.
**`ft_lstmap`**|apply function to content of all list's elements into new list.
