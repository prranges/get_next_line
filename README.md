# get_next_line

***The aim of this project is to code a function that returns a line ending with a newline, read from a file descriptor.***

This project also introduces the concept of static variables in C programming.

## Technical considerations

- Allowed functions: ```malloc```, ```free```, ```write```
- All heap allocated memory space must be properly freed when necessary

## How to test
> Run the following commands

```shell
$ git clone https://github.com/prranges/get_next_line.git
$ cd get_next_line
$ gcc -D BUFFER_SIZE=32 -o get_next_line main.c get_next_line.c get_next_line_utils.c
$ ./get_next_line some_text_file.txt
```
