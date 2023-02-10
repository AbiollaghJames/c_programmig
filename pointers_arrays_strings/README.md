POINTERS: A variable which cotains a memory address
The size of each type of variable is defined in bytes
    eg - char -> 1 byte (8 bits)
       - int -> 4 bytes (4*8 = 32bits)
       - float -> 4 bytes (same to int) 
* We use the sizeof operator to determine size of those
  types on our computer.

  example:
  #include <stdio.h>
  int main()
  {
    int n;

    printf("size of type 'char': %lu\", sizeof(char));
    printf("size of type 'int': %lu\", sizeof(int));
    printf("size of type 'float': %lu\", sizeof(float));
    printf("size of type n: %lu\", sizeof(n));

    return (0);
  }
  * The size determines how many possible values a 
    variable can hold eg a char variable could hold 256(2^8(No of bits)) different values.

    example:
    char c;
    c = 'H'; // address of c is 8 for instance.
    We've declared variable c of type char, address is 8.
    So 'H' is stored at c's address but since a byte oly stores numbers, the byte will hold ascii value of c which is 72.

