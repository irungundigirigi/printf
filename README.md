### Printf
## Introduction

printf is the C language function to to formatted printing. In the most simple case printf takes argument: a string of characters to be printed. So ``` printf("xyz") ```  would simply print x then y then z. To identify a string we add " to the beginning of a string. In case we wanted to print a double-quote we use a backslash (virgule, \) as an escape character. Without a backslash, special characters have a natural special meaning.

| Character | Description                 |
|-----------|-----------------------------|
| \\        | Print a backslash           |
| \"        | Print a double quote        |
| ’         | Start or end a character constant |
| \'        | Print a single quote        |
| %         | Start a format specification |
| \%        | Print a percent sign        |

#### Format specifications
printf becomes very powerful when printing the contents of a variable. For example formar specifier  %d  prints a number. This is done by adding another  argument to the printf statement shown here:
```
int age;
age = 25;
printf(" I am a %d years old\n", age);
```

##### Percent
Every format specification starts with a percent sign and ends with a letter. The letters are chosen to have some nmenonic meaning.

| Format    | Description                                |
|-----------|--------------------------------------------|
| \%c       | Print a single character                   |
| \%d       | Print a decimal (base 10) number          |
| \%e       | Print an exponential floating-point number |
| \%f       | Print a floating-point number              |
| \%g       | Print a general-format floating-point number |
| \%i       | Print an integer in base 10                |
| \%o       | Print a number in octal (base 8)           |
| \%s       | Print a string of characters               |
| \%u       | Print an unsigned decimal (base 10) number |
| \%x       | Print a number in hexadecimal (base 16)    |
| \%\%      | Print a percent sign                       |


