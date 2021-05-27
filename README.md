# Master_DSI_Notes
Relevant Links
* [Master Schedule `DSI Premium Prep` for class](https://github.com/GalvanizeOpenSource/dsi-premium-prep)
*



#
# Day 3 (May 26, 2021)
## OverView

* evaluation patterns
* types 
* abstractions
	* variables
	* functions
	* classes	

* control flow
    * conditions

* loops
    * for
    * while

#
# Duck Typing - if it walks like a duck.. quacks.. then it must be a duck

        # Add 5 and 7.2, multiply the result by 6, divide that result by 3, then square the result 

            # operation = ((((5 + 7.2) *6) /3)**2)

            # print(operation)

# 
int, float, bool, str

    print(float(4))
    casting to any number (int, float, bool, str)

# 
If 3 letter carriers must deliver the same exact number of letters, and there are 299 letters, how many letters will not be delivered? Write a Python expression that answers this question.

    a = 299 % 3
    print(a)

# 
If you have 5 bank tellers and 28 people waiting to be served, what is the least number of people who will not be served if it takes exactly 4 minutes to serve each person and the bank MUST close in 20 minutes? Write a Python expression that answers this question.

    b = (28 - (20 // 4 * 5))
    print(b)

#
    some_var = "some expression"

    print(some_var)

    a = 10
    b = 15
    c = (a**2 + b**2)**(1/2)
    d, e = 6, 7

#
Give it a good name

    Replace spaces with _
    this_is_a_variable = 8

# Boolean Operators
    < greater then
    <= greater then or equal
    > less then
    <= less then or equal
    == equals or is equivalent
    != does not equal

        print( 4 == 4)
        print( 4 == 5)
        print( 4 != 5)
        print( 4 < 4)
        print( 4 > 4)
        print( 4 <= 5)

        etc...

# Logical Operators
Operator Precedence: not, and, or

    print( True and True )
    print( False and True )
    print( True and False )
    print( False and False )

    print( True or True )
    print( False or True )
    print( True or False )
    print( False or False )

    print( not True )
    print( and False )

#
        a = 4
        b = 27

        print(a > b or a**2 > b / 2)

# Breakout

    not 7 > 2
    3 >= 2 or 5 < 1
    not 8
    bool('') and 5 != 3
    bool('') and 5 != 5

    False
    True
    False
    False
    False

# Control Flow

## if

    if some_condition:
        # execute this code
    else:
        # execute this code

    
    a = 100
    b = 20
    if a < b:
        print("a is les then b")

    elif a == b:
        print("a is greater than b")
    else: 
        print("a is greater than b")


# Day 4 (May 27, 2021)
##
