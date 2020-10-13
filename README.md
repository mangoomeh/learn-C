# Learn-C

## Chapter 1.1
### Hello World
The following prints 'hello, world':
```
#include <stdio.h>

main()
{
  printf("hello, world\n");
}
```
Note than printf is a function from standard library, not part of the C language.

### Declaring Variables
```
int lower;
lower = 0;
float step;
step = 10.0;
```
Other data types: char, short, long, double.\
Also: arrays, structures, unions of basic types, pointers, functions.

### While Loops
```
while (i < j) {
  i = 2 * i;
}
```

### Operations
```
c = 5/9
d = 5.0/9.0
```
Division truncates for integers.\
c will be zero, since 5 and 9 are integers.\
d will not be zero since 5.0 and 9.0 are floating point numbers.

### Output Formatting
General: % | space-allocated | .precision | type
```
printf("%6.2f", 123.12)
```
