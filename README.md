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

### Mandatory part


<table border="1" width="300"> 
 <tr>
  <td  align="center"colspan="4">C Library ctype.h</td>
 </tr>
 
 <tr>
  <td align="center">Libft </td>
  <td align="center">Description </td>
 </tr>

 <tr>
  <td>ft_isalnum</td>
  <td>Checks if the character passed is alphanumeric.</td>
 </tr>
 
 <tr>
  <td>ft_isalpha</td>
  <td>Checks if the character passed is alphabetic.</td>
 </tr>
 
 <tr>
  <td>ft_isascii</td>
  <td>Checks if the character passed is ASCII.</td>
 </tr>
 
 <tr>
  <td>ft_digit</td>
  <td>Checks if the character passed is decimal digit.</td>
 </tr>
 
 <tr>
  <td>ft_isprint</td>
  <td>Checks if the character passed is printable, including space.</td>
 </tr>
 
 <tr>
  <td>ft_tolower</td>
  <td>Converts uppercase letters to lowercase.</td>
 </tr>
 
  <tr>
  <td>ft_toupper</td>
  <td>Converts lowercase letters to uppercase.</td>
 </tr>
 
 <tr>
  <td  align="center"colspan="4"> C Library Sting.h</td>
 </tr>
 
  <tr>
  <td>ft_bzero</td>
  <td>Resets the dynamic memory region replacing whatever is there by null to clear it of junk values.</td>
 </tr>
 
 <tr>
  <td>ft_memchr</td>
  <td>Looks for the first occurrence of the character c (an unsigned character) in the first n bytes of the pointed string, by the str argument.</td>
 </tr>
 
 <tr>
  <td>ft_memcmp</td>
  <td>Compares the first n bytes of memory area str1 and memory area str2.</td>
 </tr>
 
 <tr>
  <td>ft_memcpy</td>
  <td>assign each character of src pointer to dest pointer as counter is less than the size, and returns the dest pointer.</td>
 </tr>
 
  <tr>
  <td>ft_memmove</td>
  <td>Copy bytes of length from buffer pointed to by src to buffer pointed to by std. Copying overlapping regions is handled safely.</td>
 </tr>
 
 <tr>
  <td>ft_memset</td>
  <td>Fills length bytes starting at dst with the value C.</td>
 </tr>
 
 <tr>
  <td>ft_strchr</td>
  <td>finds the first occurrence of C (converted to a char) in the string pointed to by S.</td>
 </tr>
 
  <tr>
  <td>ft_strlcat</td>
  <td>appends the NULL terminated string src to the end of dst.</td>
 </tr>
 
 <tr>
  <td>ft_strlcpy</td>
  <td>Copy up to length 1 character from NULL terminated string src to dst, ending in NULL the result.</td>
 </tr>
 
  <tr>
  <td>ft_strlen</td>
  <td>Counts how many characters there are while the parameter passed is not null.</td>
 </tr>
 
 <tr>
  <td>ft_strncmp</td>
  <td>Compares at most the first n bytes of str1 and str2.</td>
 </tr>
 
 <tr>
  <td>ft_strnstr</td>
  <td>Finds the first occurrence of the null term string nated s2 in string s1, where no more than n characters are searched.</td>
 </tr>
 
 <tr>
  <td>ft_strrchr</td>
  <td>look for the last occurrence of the character c (an unsigned character) in the string pointed to by the str argument</td>
 </tr>
 
 <tr>
  <td  align="center"colspan="4">C Library Stdlib.h</td>
 </tr>
 
 <tr>
  <td>ft_atoi</td>
  <td>converts the initial portion of the string pointed to by nptr to int. Atoi() does not detect errors</td>
 </tr>
 
 <tr>
  <td>ft_calloc</td>
  <td>allocates memory for an array of nmemb elements of size each and returns a pointer to the allocated memory.</td>
 </tr>
 
 <tr>
  <td  align="center"colspan="4">Non-stantard C Library</td>
 </tr>
 
 <tr>
  <td>ft_itoa</td>
  <td>Converts the int to a string (type char *).</td>
 </tr>
 
 <tr>
  <td>ft_putchar_fd</td>
  <td>Displays the 'c' character for the given file descriptor.</td>
 </tr>
 
 <tr>
  <td>ft_putendl_fd</td>
  <td>Displays the string 's' for the given file descriptor, followed by a newline.</td>
 </tr>
 
 <tr>
  <td>ft_putnbr_fd</td>
  <td>Display the integer 'n' for the given file descriptor.</td>
 </tr>
 
 <tr>
  <td>ft_putstr_fd</td>
  <td>Display the string 's' for the given descriptor file.</td>
 </tr>
 
 <tr>
  <td>ft_strdup</td>
  <td>Returns a pointer to a new string that is a duplicate of string s.</td>
 </tr>
 
 <tr>
  <td>ft_strjoin</td>
  <td>returns a newstring, which is the result of concatenating 's1' and 's2'.</td>
 </tr>
 
 <tr>
  <td>ft_strmapi</td>
  <td>Apply the 'f' function to each character of the string 's' to create a new string.</td>
 </tr>
 
 <tr>
  <td>ft_strtrim</td>
  <td>returns a copy of 's1' with the characters specified in 'set' removed from beginning and end of string.</td>
 </tr>
 
 <tr>
  <td>ft_substr</td>
  <td>Returns a substring of the string 's'. The substring starts at index 'start' and is of maximum length 'len'.</td>
 </tr>
  </table>
  
  
  ### Bonus part
  
  
  <table border="1" width="300"> 
 <tr>
  <td  align="center"colspan="4"> Chained lists manipulation</td>
 </tr>
 
 <tr>
  <td>ft_lstadd_back</td>
  <td>Adds the element at the end of the list.</td>
 </tr>
 
  <tr>
 <td>ft_lstadd_front</td>
  <td>Adds the element at the beginning of the list.</td>
 </tr>
 
  <tr>
 <td>ft_lstclear</td>
  <td>Deletes and frees the given element and every successor of that element, using a given function and free.</td>
 </tr>
 
 <tr>
  <td>ft_lstdelone</td>
  <td>Takes as a parameter an element and frees the memory of the element’s content using a function given as a parameter and free the element.</td>
 </tr>
 
 <tr>
  <td>ft_lstiter</td>
  <td>Iterates the list and applies a function to the content of each element.</td>
 </tr>
 
 <tr>
  <td>ft_lstlast</td>
  <td>Returns the last element of the list.</td>
 </tr>
 
 <tr>
  <td>ft_lstmap</td>
  <td>Iterates the list and applies a function to the content of each element. Creates a new list resulting of the successive applications of the function. A 'del' function is used to delete the content of an element if needed.</td>
 </tr>
 
 <tr>
  <td>ft_lstnew</td>
  <td>Returns a new element.</td>
 </tr>
 
 <tr>
  <td>ft_lstsize</td>
  <td>Counts the number of elements in a list.</td>
 </tr>

 </table>
