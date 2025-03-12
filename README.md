# **Libft - 42 Network**  

## **Overview**  
This project is the first step in my journey at **42 Network**. The goal of **Libft** is to rebuild essential functions from the C standard library, along with additional utility functions that will be useful throughout the entire curriculum. By implementing these functions, I gain a deeper understanding of low-level programming, memory management, and algorithmic problem-solving.  

## **Project Scope**  
Libft consists of multiple categories of functions, including:  

- **Libc Functions**: Rewriting standard library functions such as `strlen`, `strcpy`, `strcmp`, `memset`, `bzero`, and more.  
- **Memory Management**: Implementing functions like `malloc`, `free`, and `realloc` to handle dynamic memory allocation.  
- **String Manipulation**: Functions for handling and modifying strings efficiently.  
- **Linked Lists**: Implementing basic linked list structures and operations.  
- **Custom Utility Functions**: Additional helper functions that facilitate various tasks in future projects.  

## **Learning Outcomes**  
- Understanding the inner workings of core C functions.  
- Improving problem-solving skills and debugging capabilities.  
- Gaining a strong foundation for future 42 projects.  

## **Usage**  
### How to Build and Run

1. Clone the repository:
   
   ```bash
   git clone https://github.com/LuizGandra/libft-42.git
   cd libft-42

2. Build the mandatory part:
   
   ```bash
   make

3. Build the bonus part (optional):
   
   ```bash
   make
This includes linked list functions in `libft.a`.

4. Link the library to your C project:
   
   ```bash
   clang -o <program> <file>.c -L<libft.a directory> -lft

#### Additional commands

- `make clean`: remove object files.
- `make fclean`: remove the program and object files.
- `make re`: rebuild everything.

## Project Structure

- `libft.h`: function prototypes.
- `ft_*.c`: mandatory function sources.
- `ft_*_bonus.c`: bonus function sources.
- `Makefile`: compilation automation.
