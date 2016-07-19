http://docs.python-guide.org/en/latest/writing/structure/
    

1. Structure of Code is Key
    > Give an example of multiple and messy circular dependencies.
    > Why are circular dependencies a bad thing?
    > Should multiple classes be communicating by manipulating global state or context? Why?
    > What is spaghetti code?
    > How does spaghetti code affect a reader and the logic flow of a script?
    > What type of code is known for having many similiar little pieces of logic?

2. Modules
    > What statements may be used to bring another module into the scope of the current module?
    > What is common practice for naming modules?
    > Upon the desired module being found, how does Python handle the module?
    > When retrieving other modules, what may a person use the asteriks (*) for?

3. Packages
    > What file is used to set directories as python projects?
    > What is the purpose of the special files?
    > What is considered good practice in terms of these special files?
    > What syntax may be used to conveniently import nested packages?

4. Object-Oriented Programming
    > Is everything an Object in Python?
    > With respect to OOP, what is the difference between Java's and Python's approach?
    > What are implicit contexts and side-effects?
    > What are some of the benefits of Pure functions?

5. Decorators
    > What is an example of functionality that is well-handled by a decorator?

6. Context Managers
    > What is the syntax of a context manager?
    > What different statements in a context manager correlate with __init__(), __enter__(), and __exit__()?
    > With what two structures may someone utilize context managers?
    > What library is utilized in one of the two structures?
    > Which approach is best?

7. Dynamic Typing
    > Is the following code considered good practice?
        a = 3
        a = "quiz"
        def a():
            pass
    > Is effiency gained from reusing variable names?
    > What kind of consequences can reusing variable names have?

8. Mutable and Immutable Types
    > Give examples of mutable types and immutable types.
    > What are some methods that are used to mutate mutable types?
    > What effects can properly using mutable and immutable code have on a script?
    > Since strings are immutable, what is a more efficient way to accumulate and handle manipulating strings?
    > Which is more performant, creating a list via a for loop or creating a list via list comprehensions?
    > Should .join() be always be used to join lists? What scenarios lend themselves to .join()?
    > What method is suggested when formatting strings?
    