## Random Number System Generator

### Design an algorithm to generate a 6-digit random number that works based on either the binary, octal or hexadecimal system.

1. Choose a random number system to generate the 6-digit number in (binary, octal, or hexadecimal).
2. Generate a random number between 0 and the highest 6-digit number that can be represented in the chosen number
   system. The highest 6-digit number is 111111 in binary, 77777 in octal, and FFFFFF in hexadecimal.
3. Convert the generated number to the chosen number system if necessary.
4. If the generated number has less than 6 digits, add leading zeroes to make it a 6-digit number.
5. Output the generated 6-digit number in the chosen number system.

### Write a clear specification of the input to the algorithm and expected output.

### Specification of Input:

The algorithm requires the user to input a number system (binary, octal, or hexadecimal) in which they want to generate
a 6-digit random number.

### Specification of Output:

The algorithm will output a 6-digit random number in the number system specified by the user. If the generated number
has less than 6 digits, leading zeroes will be added to make it a 6-digit number.

### For example:

### Input: "octal"

### Output: "064321" (a random 6-digit number in octal system)

### Input: "hexadecimal"

### Output: "01A3F6" (a random 6-digit number in hexadecimal system)

### Input: "binary"

### Output: "101011" (a random 6-digit number in binary system)

### Explain how the algorithm works and state any limitations, if any. The explanation should include a brief overview of the process of generating a random number, the logic behind using either the binary, octal or hexadecimal system, and any potential issues or limitations that may arise during the implementation of the algorithm.

There are a few potential limitations or issues to consider when implementing this algorithm.

1. The range of possible generated numbers will be different depending on the chosen number system. For example, the
   highest possible number in binary is 111111 (or 63 in decimal), while the highest possible number in hexadecimal is
   FFFFFF (or 16,777,215 in decimal). This means that the algorithm will be biased towards generating smaller numbers in
   binary and larger numbers in hexadecimal.
2. Another potential issue is that the algorithm assumes that the input will always be one of the three supported number
   systems. If the user inputs an invalid or unsupported system, the algorithm will not work as expected.




