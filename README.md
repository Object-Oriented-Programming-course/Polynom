# Polynom
Introduction to Object Oriented Programming Ex0
In this task we were asked to implement classes that constitute a polynomial and include a number of capabilities such as, addition, subtraction, multiplication, derivative realization and integral.
To realize the polynomial I first implemented the monom class.
 In the monom class the object has two fields, a coefficient and a power, the main constructor in the class receives as a parameter these two variables and with them allows the construction of the object.

![1](https://user-images.githubusercontent.com/44755169/122038413-3de84c80-cdde-11eb-90c6-ed96bee5d4a6.png)




In addition there are a number of functions that allow addition, multiplication, monom value at point X, derivative, and area calculation for a single monom.

  




## Polynomial Department
This class implements a polynomial by a list of several monoms that make up the objects of the list, the data structure of the class is realized by ArrayList, in which the monuments are actually stored and form a polynomial.
The Init constructors

   
The first constructor creates an empty polynomial and allows the insertion of monomers by the add option that exists in ArrayList by default.
The second constructor gets a String as a parameter (the string structure is)
Disassembles the string by the split function into coefficients (positive and negative) and strong (positive and whole only) and thus inserts the values ​​into individual monomers and attaches them to the polynomial.

## Connection functions 
The first function allows the connection of a single monom to a polynomial.
The second function allows the connection of two polynomials.

## Additional functions:
Area
Calculate the area under the function and above the X-axis by placing two points and the number of rectangles in order to achieve maximum accuracy.
 
### Root
The ROOT function allows the calculation of the root of a function that constitutes the solution of the function when F (x) = 0, ie the solution of the function is approximately x to Eps.
### Multiply and Subtract
The Multiply function allows the polynomial to be multiplied by another polynomial, when the change is made to the original polynomial, multiplies one monom each time from the polynomial obtained as a parameter with the original polynomial and finally returns the updated polynomial after multiplication.
The Subtract function accepts as another parameter a polynomial, in the first step it converts the polynomial coefficients obtained as a parameter to negative and then makes a connection between the two polynomials.
 
### ToString 
The function prints the polynomial to the screen according to the structure defined for inserting a new polynomial.


### Area below
The Area under function calculates the total area of ​​the function when it falls below the X-axis, the function calculates the area by raising Eps once the loop is run.
