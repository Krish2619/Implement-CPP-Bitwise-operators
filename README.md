Aim:
To understand and implement various bitwise operators and bit manipulation techniques in C++ including AND, OR, XOR, NOT, left shift, right shift, and bit setting/resetting operations.

Apparatus:
1. GNU g++ compiler or any C++ compiler
2. Text editor or IDE such as Visual Studio Code, Code::Blocks, or Dev-C++

Program Explanation:

Program 1: Bitwise Operations
Initializes two integer variables a = 10 and b = 14.
Performs various bitwise operations on these numbers:
& (AND) to find common bits set in both numbers.
| (OR) to combine bits set in either number.
^ (XOR) to find bits set in one number but not both.
~ (NOT) to invert all bits.
<< (left shift) to shift bits to the left, effectively multiplying by 2.
>> (right shift) to shift bits to the right, effectively dividing by 2.
Displays the results of these operations.

Program 2: Bit Setting and Resetting
Initializes an integer variable a = 128 (binary 10000000).
Takes user input for which bit to set and which bit to reset (counting from 0).
Uses bitwise operators and bit shifts to:
Set a particular bit by OR-ing a with a mask where the target bit is 1.
Reset a particular bit by AND-ing a with the negation of a mask where the target bit is 1.
Displays the results after setting and resetting the specified bits.

Algorithm:

Program 1:
1. Start.
2. Initialize integers a and b.
3. Calculate:
   AND (a & b)
   OR (a | b)
   XOR (a ^ b)
   NOT (~a and ~b)
   Left shift (a << 1 and b << 1)
   Right shift (a >> 1 and b >> 1)
4. Display all results.
5. End.

Program 2:
1. Start.
2. Initialize integer a with 128.
3. Input bit positions to set (bit_set) and reset (bit_reset).
4. Set the bit: a | (1 << bit_set)
5. Reset the bit: a & ~(1 << bit_reset)
6. Display results.
7. End.

Key Concepts:
Bitwise Operators: AND, OR, XOR, NOT, left shift (<<), and right shift (>>).
Bit Manipulation: Setting and resetting specific bits using bitwise operations combined with bit shifting.
Binary Representation: Understanding how integers are represented as binary for bitwise operations.
user Input: Taking user-specified bit positions for dynamic bit manipulation.

Conclusion:
These programs illustrate essential bitwise operations and bit manipulation techniques that form a fundamental part of low-level programming and performance-critical applications. By learning to apply AND, OR, XOR, NOT, and bit shifts, as well as dynamically setting and resetting bits, programmers gain control over individual bits within data, enabling efficient memory and performance optimization. These foundational concepts are crucial in systems programming, embedded systems, cryptography, and more.
