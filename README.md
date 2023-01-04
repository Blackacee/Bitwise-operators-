# Bitwise-operators
//JS bitwise operators 
//Bitwise or
var a;
a = 0b0011 | 0b1010; // a === 0b1011
// truth table
// 1010 | (or)
// 0011 
// 1011 (result)

//Bitwise and
a = 0b0011 & 0b1010; // a === 0b0010
// truth table
// 1010 & (and)
// 0011 
// 0010 (result)

//Bitwise not
a = ~0b0011; // a === 0b1100
// truth table
// 10 ~(not)
// 01 (result)

//Bitwise xor (exclusive or)
a = 0b1010 ^ 0b0011; // a === 0b1001
// truth table
// 1010 ^ (xor)
// 0011 
// 1001 (result)

//Bitwise left shift
a = 0b0001 << 1; // a === 0b0010
a = 0b0001 << 2; // a === 0b0100
a = 0b0001 << 3; // a === 0b1000
