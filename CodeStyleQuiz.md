http://docs.python-guide.org/en/latest/writing/style/

1. Explicit Code
    > Which of the following function definition is more Pythonic?
        def make_complex(*args):
            x, y = args
            return dict(**locals())

        def make_complex(x, y):
            return {'x': x, 'y': y}

    > What makes the chosen function Pythonic?

2. One Statement per Line
    > Should a programmer write if statements with mutiple comparisons being evaluated in one line?
    > Should a programmer write an if statement and its body in the same line?
    > Should a programmer print mutiple strings in one line?
    > Why?

3. Function Arguements
    > What are the four different ways to pass arguments into a function?
    > For type 1, may the order of arguments passed in be changed? If so, how? What effect does this have on code?
    > For type 2, what is it often used for?
    > For type 3, what is the syntax? What scenarious fit this form of function arguement?
    > For type 4, what is the syntax? What scenarious fit this form of function arguement?
    > For type 3 and 4, what is a simple way to avoid this function argument type?

4. We Are All Responsible Users
    > What does the expression "We are all responsible users" refer to?
    > What is the main convention with respect to private properties and implementation details?
    > As a general rule of thumb, what can be said about publicizing a private property versus privatizing a public property?

5. Returning Values
    > What are the to main cases for returning a value in a function?
    > At what point in a function is it best to check for exceptions? Or to return errors?

6. Idioms
    > What can be done to a list or tuple for which the length is known?
    > What syntax, method, and control structure is often used for this purpose?
    > Python 3 introduced a new syntax for this purpose. Provide an example of this syntax.

    > What idiom may be used to deal with variables that don't intend to be used?
    > What naming convention has been adopted for this purpose?

    > What syntax may be used to create a length-n list of the same thing?
    > Why may not this same syntax be used to create a length-n list of lists?
    > What syntax may be used to create a length-n list of lists?
    > What method may be used to create a string from a list?

    > Which data structure may searched more quickly; sets or lists?
    Note: For a list of data structure efficency, check here: https://wiki.python.org/moin/TimeComplexity?

7. Zen of Python
    > http://artifex.org/~hblanks/talks/2011/pep20_by_example.pdf

8. PEP 8
    Note: The de-facto code style guide for Python. Command line tools pep8 and autopep8 may be installed via pip to verify code format and modify code format.

9. Conventions
    > In an if control structure, should variables be explicitly compared to True, None, 0, etc?
    Note: https://docs.python.org/3/library/stdtypes.html#truth-value-testing

    > What methods should be used to access dictionary elements?
    > What is the syntax for these methods?

    > What methods and statement should be used to work with lists?
    > What is the syntax for the methods and statement stated about?
    > What method should be used to keep track of a count while iterating through a list?

    > What statement should be used to read from files?
    > What does this statement ensure?

    > Line continuations may be handled by utilizing how Python handles parenthesis. Give an example of this.

    Note: Documentation conventions may be found here: https://www.python.org/dev/peps/pep-0257/#id17

10. Logging
    > http://docs.python-guide.org/en/latest/writing/logging/#or-print
    > What two forms of logging are there?
    > When is print() a preferable option to logging?
    > What are the various levels of logging?
    > What is the module that must be imported for logging?