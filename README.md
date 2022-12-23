# C# Basics
## Variables
Variables are used to store values. They have a type, such as int (for integers), float (for floating-point numbers), or string (for strings), and a name. For example:
```
int age = 30;
float weight = 75.5f;
string name = "John";
```
## Data types
C# has several data types, including numbers, strings, and Booleans. Numbers can be integers or floating-point values, and can be written with or without a decimal point. Strings are sequences of characters, and are written using double quotes. Booleans represent true or false values.

## Operators
C# supports a variety of operators, such as arithmetic operators (e.g., +, -, *, /), relational operators (e.g., <, >, ==, !=), and logical operators (e.g., &&, ||, !). These operators can be used to perform calculations and compare values.

## Control structures
C# has several control structures that allow you to control the flow of your program. These include if statements, for loops, and while loops. For example:
```
if (age > 18) {
  Console.WriteLine("You are an adult.");
} else {
  Console.WriteLine("You are a minor.");
}
```
```
for (int i = 0; i < 10; i++) {
  Console.WriteLine(i);
}
```
```
int i = 0;
while (i < 10) {
  Console.WriteLine(i);
  i++;
}
```
## Functions
Functions are blocks of code that can be called from other parts of your program. They can take parameters and return a value. For example:
```
int Add(int x, int y) {
  return x + y;
}

int main() {
  int result = Add(2, 3);
  Console.WriteLine(result); // prints 5
  return 0;
}
```
These are just a few of the basics of C#. There are many other concepts to learn, such as classes, arrays, inheritance, and more. I recommend finding a good tutorial or textbook to learn more about the language.
