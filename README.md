> Don't stop until you're done!

**Documentation**

1. [Python](https://docs.python.org/3/)
2. [Python Wiki](https://wiki.python.org/moin/FrontPage)
3. [Python Style Guide](https://www.python.org/dev/peps/pep-0008/#tabs-or-spaces)
4. [Python 3 Module of the Week](https://pymotw.com/3/)

**Practice**

1. [Hacker Rank](https://www.hackerrank.com/)
2. [LeetCode](https://leetcode.com/)
3. [Python Tutorial](https://docs.python.org/3/tutorial/)
4. [Learn Python](http://www.learnpython.org/)

**Chapter 1: Summary of Data Types and Operators**

1. **Data Types**

   | Data Types | Constructor             | Example            |
   | ---------- | ----------------------- | ------------------ |
   | int        | `int()`                 | 5                  |
   | float      | `float()`               | 6.5                |
   | string     | `''` or `""` or `str()` | "this is a string" |
   | bool       | `bool()`                | `True` or `False`  |

2. (i) **Arithmetic Operators**

   | Symbol | Operation        |
   | ------ | ---------------- |
   | +      | addition         |
   | -      | substraction     |
   | *      | multiplication   |
   | /      | division         |
   | **     | exponentiation   |
   | %      | modulo           |
   | //     | integer division |

   (ii) **Assignment Operators**

   | Symbol | Example | Equivalent |
   | ------ | ------- | ---------- |
   | =      | x = 2   | x = 2      |
   | +=     | x += 2  | x = x + 2  |
   | -=     | x -= 2  | x = x - 2  |

   (iii) **Comparison Operators**

   | Symbol | Operation                |
   | ------ | ------------------------ |
   | <      | less than                |
   | >      | greater than             |
   | <=     | less than or equal to    |
   | >=     | greater than or equal to |
   | ==     | equal to                 |
   | !=     | not equal                |

   (iv) **Logical Operators**

   | Keyword | Operation                              |
   | ------- | -------------------------------------- |
   | and     | evaluates if both sides are true       |
   | or      | evaluates if at least one side is true |
   | not     | inverses a boolean type                |

**Keyword in Python Programming Languages**

|        |          |         |          |        |
| ------ | -------- | ------- | -------- | ------ |
| False  | class    | finally | is       | return |
| None   | continue | for     | lambda   | try    |
| True   | def      | from    | nonlocal | while  |
| and    | elif     | global  | not      | with   |
| as     | else     | if      | or       | yield  |
| assert | except   | import  | pass     |        |
| break  | del      | in      | raise    |        |

**Chapter 2:  Data Structures**

| Data Structure | Ordered | Mutable | Constructor       | Example List          |
| -------------- | ------- | ------- | ----------------- | --------------------- |
| List           | Yes     | Yes     | `[]` or `list()`  | `[5.7,4,'yes',5.7]`   |
| Tuple          | Yes     | No      | `()` or `tuple()` | `(5.7,4,'yes',5.7)`   |
| Set            | No      | Yes     | `{}`* or `set()`  | `{5.7,4,'yes'}`       |
| Dictionary     | No      | No**    | `{}` or ``  dict() `` |`{'Jun':75,'Jul':89}`|

*You can use curly braces to define a set like this: `{1,2,3}`. However, if you leave the curly braces empty like this: `{}` Python will instead create an empty dictionary. So to create an empty set, use `set()`.

** A dictionary itself is mutable, but each of its individual keys must be immutable.