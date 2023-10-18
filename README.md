# LabStandards
Coding and Lab Standards
Revised 15-Oct-2023

## Structure 
All labs must follow this pattern.  The application code must be in a shared libary.  And then a main executable that depends upon the shared library.  And then gtest executablet to test the code in the shared library.

## Unit Tests

When you are asked to write unittests, it is expected that at least half of you unit test's per method will not be trivial, i.e. just one call on the method.   As typically you will want to have more complicated cases.  For, example add 3 items to the ADT, and then remove one of them is an example of non-trivial unit test.

## C++ Coding Standards

1. Naming standards must conform to Google OS naming standards - https://google.github.io/styleguide/cppguide.html#Naming
2. all code should be commentend sufficently.  This means all methods, constructors, etcs shoudl have a comment.
3. All classes must be declared in their own header files. And implementation in their own implementation file. 
5. Consistency : Code should follow a consistent style throughout.
6. Indentation and Spacing : Proper indentation and spacing should be used to enhance code readability.
7. Naming Conventions : Variable and function names should follow a consistent naming convention.
8. Comments and Documentation : Adequate comments and documentation should be included to explain the code's logic.

## Lab Report Guidelines

1. Must contain a participation rubric

Participation Rubric
Participation rubric of teammates.  List out for your all team members how much they participated.
```
	             Member1	Member2	Member3
Member1 (opinion)	33	     33	     33
Member2 (opinion)	33	     33	     33
Member3 (opinion)	33	     33	     33
```			
			
Example 			
```
	             Member1	Member2	Member3
Member1 (opinion)	33	     33	     33
Member2 (opinion)	20	     40	     40
Member3 (opinion)	20	     40	     40
```

2. Must contain Group number and group members
