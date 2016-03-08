Basic Types and Operations

->  Every value in scala is an object and every operation on an object is a method call

->  scala doesnot have operators . All the operations are method calls

->  1+2 in scala is calling the method '+' in the integer value 1 which takes one argument ie 2 . so in effect it is 1.+(2)

->  All the members of package scala and java.lang are automatically imported into scala sourec file

->  Scala shell always prints integer values in base 10

->  Integer Literals comes in three forms - decimal, hexadecimal and octal.

->  If number begins with 0x or 0X, its hexadecimal. 

->  If number begins with non-zero digit, its decimal

->  If number ends in L or l, its long

->  Float and Double follow IEEE754 standard

->  stripMargin method is used to remove leading spaces in string when a string value is written in multiple lines

->  3 operator notations - postfix, prefix and infix.

->  prefix operators are +, -, !, and ~

->  modulus operator follows IEEE754 standard and thus remainder uses rounding division , not truncating division

->  The logical-and and logical-or operations are short-circuited

->  a && b - b is evaluated only if a is true
 
->  == != are final in Any and equals extends == 

->  Any method which start with * has highest precedence

->  Any method that ends in a ‘:’ character is invoked on its right operand, passing in the left operand
