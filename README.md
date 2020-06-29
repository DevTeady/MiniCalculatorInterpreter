# Mini Calculator Interpreter

Tiny calculator interpreter with supporting Mathematical functions using Python.

![Mini Calculator Interpreter python](screen.jpg)

## Features

- Variable
- Mathematical Constants
- Mathematical Functions

### Mathematical Constants

- pi
- e

### Mathematical Functions

- sin
- cos
- log
- log10
- log2
- exp
- sqrt
- acos
- atan
- radians
- sinh
- cosh
- tanh
- asin
- ceil
- fabs
- actorial
- loor
- copysign
- pow

### Using

```
git clone https://github.com/BaseMax/MiniCalculatorInterpreter
cd MiniCalculatorInterpreter
sudo pip3 install ply
python calculator.py
```

### Grammer

```
S -> statement

statement -> NAME EQUALS expression
statement -> expression,statement

expression -> expression PLUS expression
expression -> expression MINUS expression
expression -> expression DIVIDE expression
expression -> expression TIMES expression
expression -> MINUS expression
expression -> LPAREN expression RPAREN

expressions -> expressions COLON expression
expressions -> expression
expressions -> <empty>

expression -> NAME LPAREN expressions RPAREN
expression -> NUMBER_INT
expression -> NUMBER_DOUBLE
expression -> NAME
```

----

# Max Base

My nickname is Max, Programming language developer, Full-stack programmer. I love computer scientists, researchers, and compilers. [Max Base]https://maxbase.org/))

## Asrez Team

A team includes some programmer, developer, designer, researchers) especially Max Base.

[Asrez Team]https://www.asrez.com/)

