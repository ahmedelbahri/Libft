# Libft 1337

**Libft** is a custom C library project designed to help improve and refine low-level programming skills in C. It implements a set of functions commonly found in the C standard library, as well as custom utility functions that are useful for building more complex projects. This repository is part of the 42 School curriculum.

---

## Table of Contents

- [About](#about)
- [Installation](#installation)
- [Functions](#functions)
- [Usage](#usage)
- [License](#license)

---

## About

Libft 1337 is a personal library project for 42 School. The objective is to implement a selection of functions that replicate parts of the C standard library. By completing this project, you will improve your understanding of memory management, string manipulation, and basic algorithms.

---

## Installation

To install **libft 1337**, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/your_username/libft.git
    cd libft
    ```

2. Compile the library:
    ```bash
    make
    ```

3. Optionally, to remove all compiled objects:
    ```bash
    make clean
    ```

4. To remove the library completely:
    ```bash
    make fclean
    ```

5. To recompile the library after cleaning:
    ```bash
    make re
    ```

---

## Functions

The library implements the following functions:

- `ft_memset` - Fills memory with a constant byte.
- `ft_bzero` - Sets memory to zero.
- `ft_memcpy` - Copies memory from one location to another.
- `ft_memmove` - Moves memory with overlap handling.
- `ft_strlen` - Returns the length of a string.
- `ft_strdup` - Duplicates a string.
- `ft_strcpy` - Copies a string to another string.
- `ft_strcat` - Concatenates two strings.
- `ft_strchr` - Searches for the first occurrence of a character in a string.
- `ft_atoi` - Converts a string to an integer.
- `ft_isdigit` - Checks if a character is a digit.
- `ft_isalpha` - Checks if a character is an alphabetic letter.
- `ft_isalnum` - Checks if a character is alphanumeric.
- `ft_toupper` - Converts a character to uppercase.
- `ft_tolower` - Converts a character to lowercase.

**More functions may be included in the future.**

---

## Usage

You can use **libft 1337** in your projects by including the `libft.h` header file and linking the library when compiling your code. Example:

```c
#include "libft.h"

int main() {
    char *str = "Hello, world!";
    printf("Length of string: %d\n", ft_strlen(str));
    return 0;
}
