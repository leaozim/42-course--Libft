# Libft

## Introduction

LIBFT is a project aimed at learning how C functions work, implementing them and understanding how to use them.

To run it I needed to learn about:
  C base;
  pointers;
  Memory allocation;
  Operations with basic data structure.

* **Mandatory part:** In the mandatory part, a set of functions from the LIBC file were redone, having the same prototypes and behaviors as the original ones. In addition to them, a set of functions were developed that are not in LIBC, or that are part of it, but in a different way.
* **Bonus part:** In the bonus functions were made to manipulate lists.

## Make

| Command | Usage |
| --- | --- |
| `make` | creates .o files for each function as well as the main library file, libft.a |
| `make bonus` | creates .o files for bonus functions as well as the main library file, libft.a |
| `make clean` | removes the .o files used to create the library |
| `make fclean` | removes the .o & .a files used to create the library |
| `make re` | removes all .o & .a files then remakes them |


## Mandatory part


<table border="1" width="300"> 
 <tr>
  <td  align="center"colspan="4">C Library ctype.h</td>
 </tr>
 
 <tr>
  <td align="center">Libft </td>
  <td align="center">Description </td>
 </tr>

 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_isalnum.c">ft_isalnum</a></td>
  <td>Checks if the character passed is alphanumeric.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_isalpha.c">ft_isalpha</a></td>
  <td>Checks if the character passed is alphabetic.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_isascii.c">ft_isascii</a></td>
  <td>Checks if the character passed is ASCII.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_digit.c">ft_digit</a></td>
  <td>Checks if the character passed is decimal digit.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_isprint.c">ft_isprint</a></td>
  <td>Checks if the character passed is printable, including space.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_tolower.c">ft_tolower</a></td>
  <td>Converts uppercase letters to lowercase.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_toupper.c">ft_toupper</a></td>
  <td>Converts lowercase letters to uppercase.</td>
 </tr>
 
 <tr>
  <td  align="center"colspan="4"> C Library Sting.h</td>
 </tr>
 
  <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_bzero.c">ft_bzero</a></td>
  <td>Resets the dynamic memory region replacing whatever is there by null to clear it of junk values.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_memchr.c">ft_memchr</a></td>
  <td>Looks for the first occurrence of the character c (an unsigned character) in the first n bytes of the pointed string, by the str argument.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_memcmp.c">ft_memcmp</a></td>
  <td>Compares the first n bytes of memory area str1 and memory area str2.</td>
 </tr>
 
 <tr>
   <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_memcpy.c">ft_memcpy</a></td>
  <td>assign each character of src pointer to dest pointer as counter is less than the size, and returns the dest pointer.</td>
 </tr>
 
  <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_memmove.c">ft_memmove</a></td>
  <td>Copy bytes of length from buffer pointed to by src to buffer pointed to by std. Copying overlapping regions is handled safely.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_memset.c">ft_memset</a></td>
  <td>Fills length bytes starting at dst with the value C.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_strchr.c">ft_strchr</a></td>
  <td>finds the first occurrence of C (converted to a char) in the string pointed to by S.</td>
 </tr>
 
  <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_strlcat.c">ft_strlcat</a></td>
  <td>appends the NULL terminated string src to the end of dst.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_strlcpy.c">ft_strlcpy</a></td>
  <td>Copy up to length 1 character from NULL terminated string src to dst, ending in NULL the result.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_strlen.c">ft_strlen</a></td>
  <td>Counts how many characters there are while the parameter passed is not null.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_strncmp.c">ft_strncmp</a></td>
  <td>Compares at most the first n bytes of str1 and str2.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_strnstr.c">ft_strnstr</a></td>
  <td>Finds the first occurrence of the null term string nated s2 in string s1, where no more than n characters are searched.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_strrchr.c">ft_strrchr</a></td>
  <td>look for the last occurrence of the character c (an unsigned character) in the string pointed to by the str argument</td>
 </tr>
 
 <tr>
  <td  align="center"colspan="4">C Library Stdlib.h</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_atoi.c">ft_atoi</a></td>
  <td>converts the initial portion of the string pointed to by nptr to int. Atoi() does not detect errors</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_calloc.c">ft_calloc</a></td>
  <td>allocates memory for an array of nmemb elements of size each and returns a pointer to the allocated memory.</td>
 </tr>
 
 <tr>
  <td  align="center"colspan="4">Non-stantard C Library</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_itoa.c">ft_itoa</a></td>
  <td>Converts the int to a string (type char *).</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_putchar_fd.c">ft_putchar_fd</a></td>
  <td>Displays the 'c' character for the given file descriptor.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_putendl_fd.c">ft_putendl_fd</a></td>
  <td>Displays the string 's' for the given file descriptor, followed by a newline.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_putnbr_fd.c">ft_putnbr_fd</a></td>
  <td>Display the integer 'n' for the given file descriptor.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_putstr_fd.c">ft_putstr_fd</a></td>
  <td>Display the string 's' for the given descriptor file.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_strdup.c">ft_strdup</a></td>
  <td>Returns a pointer to a new string that is a duplicate of string s.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_strjoin.c">ft_strjoin</a></td>
  <td>returns a newstring, which is the result of concatenating 's1' and 's2'.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_strmapi.c">ft_strmapi</a></td>
  <td>Apply the 'f' function to each character of the string 's' to create a new string.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_strtrim.c">ft_strtrim</a></td>
  <td>returns a copy of 's1' with the characters specified in 'set' removed from beginning and end of string.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_substr.c">ft_substr</a></td>
  <td>Returns a substring of the string 's'. The substring starts at index 'start' and is of maximum length 'len'.</td>
 </tr>
  </table>
  
  
  ## Bonus part
  
  
  
 <table border="1" width="300"> 
 <tr>
  <td  align="center"colspan="4"> Chained lists manipulation</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_lstadd_back.c">ft_lstadd_back</a></td>
  <td>Adds the element at the end of the list.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_lstadd_front.c">ft_lstadd_front</a></td>
  <td>Adds the element at the beginning of the list.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_lstclear.c">ft_lstclear</a></td>
  <td>Deletes and frees the given element and every successor of that element, using a given function and free.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_lstdelone.c">ft_lstdelone</a></td>
  <td>Takes as a parameter an element and frees the memory of the element’s content using a function given as a parameter and free the element.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_lstiter.c">ft_lstiter</a></td>
  <td>Iterates the list and applies a function to the content of each element.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_lstlast.c">ft_lstlast</a></td>
  <td>Returns the last element of the list.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_lstmap.c">ft_lstmap</a></td>
  <td>Iterates the list and applies a function to the content of each element. Creates a new list resulting of the successive applications of the function. A 'del' function is used to delete the content of an element if needed.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_lstnew.c">ft_lstnew</a></td>
  <td>Returns a new element.</td>
 </tr>
 
 <tr>
  <td><a href="https://github.com/leaozim/Libft/blob/main/srcs/ft_lstsize.c">ft_lstsize</a></td>
  <td>Counts the number of elements in a list.</td>
 </tr>

 </table>
