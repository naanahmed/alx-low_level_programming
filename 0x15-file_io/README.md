# C - File I/O

In this project, I learned about file descriptors and unique identifiers

## Requirements

Allowed editors: `vi`, `vim`, `emacs`
All files compiled on Ubuntu 20.04 LTS using `gcc`, using the options `-Wall -Werror -Wextra -pedantic -std=gnu89`

## Header File :file_folder:

* [main.h](./main.h): Header file containing definitions and prototypes for all types and functions written for the project. 


| Type/File                 | Definition/Prototype                                                 |
| ------------------------- | -------------------------------------------------------------------- |
| `0-read_textfile.c`       | `ssize_t read_textfile(const char *filename, size_t letters);`       |
| `1-create_file.c`         | `int create_file(const char *filename, char *text_content);`         |
| `2-append_text_to_file.c` | `int append_text_to_file(const char *filename, char *text_content);` |
| `3-cp.c`                  | `cp file_from file_to`                                               |
| `100-elf_header.c`        | `elf_header elf_filename`                                            | 

## Tasks :page_with_curl:

* **0. Tread lightly, she is near**
  * [0-read_textfile.c](./0-read_textfile.c): A function that reads a text file and prints it to the `POSIX` standard output.

* **1. Under the snow**  
  * [1-create_file.c](./1-create_file.c): A function that creates a file

* **2. Speak gently, she can hear**
  * [2-append_text_to_file.c](./2-append_text_to_file.c): A function that appends text at the end of a file

* **3. cp**
  * [3-cp.c](./3-cp.c): A program that copies the content of a file to another file. 

* **4. elf**
  * [100-elf_header.c](./100-elf_header.c): A program that displays the information contained in the `ELF` header at the start of an `ELF` file.
