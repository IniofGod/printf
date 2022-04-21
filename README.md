# 0x10. C - printf
## Description
This team project is part of the first year curriculum of Alx Software Engineering Boothcamp. _printf replicates the C standard library printf() function.

What you should learn from this project:
1. How to use git in a team setting<br>
2. Applying variadic functions to a big project<br>
3. The complexities of printf<br>
4. Managing a lot of files and finding a good workflow

## Prototype
`int _printf(const char *format, ...);`
## Usage
1. Prints a string to the standard output, according to a given format
2. All files were created and compiled on Ubuntu 14.04.4 LTS using GCC 4.8.4 with the command `gcc -Wall -Werror -Wextra -pedantic *.c`
3. Returns the number of characters in the output string on success, -1 otherwise
4. Call it this way: `_printf("format string", arguments...)` where `format string `can contain conversion specifiers and flags, along with regular characters

## Examples
`_printf("Hello, ALX SCHOOL\n")` prints *"Hello, Holberton"*, followed by a new line<br>
`_printf("%s", "Hello")` prints *"Hello"*<br>
`_printf("This is a number: %d", 98) `prints *"This is a number: 98"*

## Tasks
These are all the tasks of this project, the ones that are completed link to the corresponding files.

### 0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life
Write a function that produces output according to format.<br>
c : converts input into a character<br><br>
s : converts input into a string
### 1. Education is when you read the fine print. Experience is what you get if you don't
Handle the following conversion specifiers:<br><br>
d : converts input into a base 10 integer<br><br>

i : converts input into an integer
### 2.  Just because it's in print doesn't mean it's the gospel
Create a man page for your function
### 3. With a face like mine, I do better in print
Handle the following conversion specifiers:<br><br>
b : the unsigned int argument is converted to binary
### 4. What one has not experienced, one will never understand in print
Handle the following conversion specifiers:<br><br>
u : converts the input into an unsigned integer<br><br>
o : converts the input into an octal number<br><br>
x : converts the input into a hexadecimal number<br><br>
X : converts the input into a hexadecimal number with capital letters
### 5. Nothing in fine print is ever good news
Use a local buffer of 1024 chars in order to call write as little as possible.
### 6. My weakness is wearing too much leopard print
Handle the following custom conversion specifier:<br><br>
S : prints the string<br><br>
Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)
### 7.  How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print
Handle the following conversion specifier:<br><br>
p : int input is converted to a pointer address
### 8. The big print gives and the small print takes away
Handle the following flag characters for non-custom conversion specifiers:<br><br>
+ : adds a + in front of signed positive numbers and a - in front of signed negative numbers<br><br>
space : same as +, but adds a space (is overwritten by +)
### 9. adds a 0 in front of octal conversions that don't begin with one, and a 0x or 0X for x or X conversions
[9. Sarcasm is lost in print]<br><br>
Handle the following length modifiers for non-custom conversion specifiers:<br><br>
l : converts d, i, u, o, x, X conversions in short signed or unsigned ints<br><br>
h : converts d, i, u, o, x, X conversions in long signed or unsigned ints<br><br>
10. Print some money and give it to us for the rain forests<br><br>
Handle the field width for non-custom conversion specifiers.<br><br>
11. The negative is the equivalent of the composer's score, and the print the performance<br><br>
Handle the precision for non-custom conversion specifiers.<br><br>
12. It's depressing when you're still around and your albums are out of print<br><br>
Handle the 0 flag character for non-custom conversion specifiers.<br><br>
13. Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection<br><br>
Handle the - flag character for non-custom conversion specifiers.<br><br>
14. Print is the sharpest and the strongest weapon of our party
Handle the following custom conversion specifier:<br><br>
r : prints the reversed string<br><br>
15. The flood of print has turned reading into a process of gulping rather than savoring
Handle the following custom conversion specifier:<br><br>
R : prints the rot13'ed string
[16. * ]
All the above options work well together.

## Authors
[Oluwasube Promise](https://github.com/oluwasube) - oluwasubepromise@gmail.com
<br>
[Ilesanmi Blessing](https://github.com/IniofGod) - blessingilesanmi22@gmail.com
