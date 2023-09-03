# 42cursus - Libft

## About  
The purpose of this project is to re-code some libc functions, as well as other common utility functions to be reused in the subsequent 42 projects.
<br>
*For more detailed information, look at the subject of this project.*

## Files  
### Makefile  
- Makefile
### Header  
- libft.h
### Source code  

|  Libc Functions  | Additional Functions  |  Bonus Functions |
| :------------ | :------------ | :------------ |
| ft_isalpha  | ft_substr  | ft_lstnew  |
| ft_isdigit  | ft_strjoin  | ft_lstadd_front  |
| ft_isalnum  | ft_strtrim  | ft_lstsize  |
| ft_isascii  | ft_split | ft_lstlast  |
| isprint  | ft_itoa  | ft_lstadd_back  |
| ft_strlen  | ft_strmapi  | ft_lstdelone  |
| ft_memset  | ft_striteri  | ft_lstclear  |
| ft_bzero  | ft_putchar_fd  | ft_lstiter  |
| ft_memcpy  | ft_putstr_fd  | ft_lstmap  |
| ft_memmove  | ft_putendl_fd  |   |
| ft_strlcpy  | ft_putnbr_fd  |   |
| ft_strlcat  |   |   |
| ft_toupper  |   |   |
| ft_tolower  |   |   |
| ft_strchr  |   |   |
| ft_strrchr  |   |   |
| ft_strncmp  |   |   |
| ft_memchr  |   |   |
| ft_memcmp  |   |   |
| ft_strnstr  |   |   |
| ft_atoi  |   |   |
| ft_calloc  |   |   |
| ft_strdup  |   |   |

## Instructions

### 1.Cloning the repositories  
```shell
$ git clone https://github.com/proche-c/libft.git
```
### 2.Compiling  
```shell
$ cd path/to/libft && make
```
### 3. How to use it in your code. 
Include its header in the header of your code:
```shell
#include "libft.h"
```
and, when compiling your code, add the required flags:
```shell
$ -lft -L path/to/libft.a -I path/to/libft.h
```
### 4. Cleaning all binary and executable files
```shell
$ cd path/to/libft && make fclean
```
