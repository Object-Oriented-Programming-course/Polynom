# Polynom
Introduction to Object Oriented Programming Ex0
In this task we were asked to implement classes that constitute a polynomial and include a number of capabilities such as, addition, subtraction, multiplication, derivative realization and integral.
To realize the polynomial I first implemented the monom class.
 In the monom class the object has two fields, a coefficient and a power, the main constructor in the class receives as a parameter these two variables and with them allows the construction of the object.

![1](https://user-images.githubusercontent.com/44755169/122038413-3de84c80-cdde-11eb-90c6-ed96bee5d4a6.png)




In addition there are a number of functions that allow addition, multiplication, monom value at point X, derivative, and area calculation for a single monom.

  
![2](https://user-images.githubusercontent.com/44755169/122038759-9e778980-cdde-11eb-94f4-ababc28f570b.png)




## Polynomial Department
This class implements a polynomial by a list of several monoms that make up the objects of the list, the data structure of the class is realized by ArrayList, in which the monuments are actually stored and form a polynomial.
The Init constructors

![3](https://user-images.githubusercontent.com/44755169/122038778-a20b1080-cdde-11eb-8d88-fbd0e2a62f58.png)

   
The first constructor creates an empty polynomial and allows the insertion of monomers by the add option that exists in ArrayList by default.
The second constructor gets a String as a parameter (the string structure is)
Disassembles the string by the split function into coefficients (positive and negative) and strong (positive and whole only) and thus inserts the values ​​into individual monomers and attaches them to the polynomial.

## Connection functions 

The first function allows the connection of a single monom to a polynomial.
The second function allows the connection of two polynomials.

![4](https://user-images.githubusercontent.com/44755169/122038798-a7685b00-cdde-11eb-8ba3-b4688fe08b19.png)

## Additional functions:
Area
Calculate the area under the function and above the X-axis by placing two points and the number of rectangles in order to achieve maximum accuracy.

![5](https://user-images.githubusercontent.com/44755169/122038801-a800f180-cdde-11eb-8f46-12a40bf71bea.png)
 
### Root
The ROOT function allows the calculation of the root of a function that constitutes the solution of the function when F (x) = 0, ie the solution of the function is approximately x to Eps.

![6](https://user-images.githubusercontent.com/44755169/122038827-af27ff80-cdde-11eb-86f3-41b248df0881.png)

### Multiply and Subtract
The Multiply function allows the polynomial to be multiplied by another polynomial, when the change is made to the original polynomial, multiplies one monom each time from the polynomial obtained as a parameter with the original polynomial and finally returns the updated polynomial after multiplication.
The Subtract function accepts as another parameter a polynomial, in the first step it converts the polynomial coefficients obtained as a parameter to negative and then makes a connection between the two polynomials.
 
### ToString 
The function prints the polynomial to the screen according to the structure defined for inserting a new polynomial.

![7](https://user-images.githubusercontent.com/44755169/122038831-af27ff80-cdde-11eb-9be8-b03f66c85e68.png)
![8](https://user-images.githubusercontent.com/44755169/122038832-afc09600-cdde-11eb-8e86-d8d9fe871c7b.png)



### Area below
The Area under function calculates the total area of ​​the function when it falls below the X-axis, the function calculates the area by raising Eps once the loop is run.
