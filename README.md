#ObjectpPortfolio-aenoncunanan

DismathPortfolio-aenoncunanan created by Classroom for GitHub

#SESSION 0 (Wednesday, February 3, 2016):
###Introduction

- Today, I learned that Java Language is being used in Object Oriented Programming.
- I also learned that everything in java are objects.
- I've learned that Java language and C language has almost the same syntax.
- I've learned the differences between Java and C:
  - C Language is faster and more efficient because it is machine dependent, meaning, it can communicate with the machine directly.
  - C Language needs to be recompiled to run in another operating system (OS).
  - Java Language cannot communicate with the machine directly and it needs Java Virtual Machine (JVM) to be able to communicate with the machine.
  - Java is portable, meaning, it can be run in different operating systems (OS). The only requirement is that, the machine should have an installed JVM in it.
- Class and Object were also introduced during the session using the house as an example.
- Class is the blueprint of the house, and the object is the actual thing, the house.
- Public and Private Classes were also discussed:
  - Public Classes can be accessed by other classes while Private Classes is only accessible by a certain Class.
  - Using the Univeristy Building as an example, University Building, classrooms are declraed as private, meaning, only authorized people can access it, while comfort rooms are declared as public, where visitors can access it.
- Basic commands in linux terminal were also explained.
  - ` $ ls ` will list all the files and folders in the directory.
  - ` $ mkdir ` will create a new directory.
  - ` $ cd ` changes directory path
  - ` $ rm ` to erase or remove a file or folder.
  - By pressing the `ctrl+p` on your keyboard, the previous syntax, will be generated automatically.
  - By pressing the `ctrl+c`  or `ctrl+z`, the current process will be terminated.
  - By pressing the `Tab Key` on your keyboard, the syntax you are typing in will be auto completed.
  - ` $ mv ` to move a file.
  - ` $ pwd ` to check if directory exists.
  - ` $ clear ` will clear the terminal.
  - ` $ sudo apt-get install program ` will install a desired program.
  - ` $ javac ` to compile the source code.
  - ` $ java ` to run the source code.
- A [HelloWorld](https://github.com/aenoncunanan/HelloWorld) Java program was also made during this session.


#SESSION 1 (Wednesday, February 3, 2016):
###Introduction

- Having the basic knowledge in Java, I was able to create a [TruthTable](https://github.com/aenoncunanan/BooleanTable).


#SESSION 2 (Wednesday, February 10, 2016):
###Primitives

- In this session, primitives were discussed.
- Primitive data types are byte, short, int, long, float, double, boolean, and char.
- You can modify the user's input like making the characters in an upper case or a lower case.
- Boolean data types can accept only true or false, not 1 or 0.
- Date can also be placed using the Date utility of Java.
- By importing the java.io class from java, you will be able to get inputs from the user.
- Parsing can convert one data type to another data type.
- Exercises [Characters](https://github.com/aenoncunanan/Characters), [SimpleCalculator](https://github.com/aenoncunanan/SimpleCalc), and [StringOutput](https://github.com/aenoncunanan/StringOutput) were made during this session.


#SESSION 3 (Friday, February 12, 2016):
###SyntaxAndFlow

- In this session, Syntax and Flow were discussed.
- [If-else statements](https://github.com/aenoncunanan/Conditional) were used in primitives and complex data types.
- When comparing primitive data types, equal sign, less than sign, and greater than sign can be used
- `.equals("");` syntax should be used in comparing complex data types.
- In Java, you can use strings, enumeration and integers in [switch cases](https://github.com/aenoncunanan/Switch).
- There are four (4) types of [loops](https://github.com/aenoncunanan/Loops) that can be used in java:
  - The conventional For-Loop:
    - ` for (condition){statement} `
  - The Each-For-Loop:
    - ` for(:){statement} `
  - The While-Loop:
    - ` While (condition){statement} `
  - The Do-While-Loop:
    - ` Do {statement} While (condition); `
- [Methods](https://github.com/aenoncunanan/Methods) were also discussed in this session, methods are like functions in C where you can also [pass an argument](https://github.com/aenoncunanan/MethodsWithArgs).
- Method name can be used many times as long as the signatures are different. This is called [Method Overloading](https://github.com/aenoncunanan/MethodOverloading)
- As an output, a second version of [calculator](https://github.com/aenoncunanan/Calculator2) was made.


#SESSION 4 (Monday, February 15, 2016):
###ComplexObjects

- In this session, we were introduced to a complex data types like strings and dates.
- There are two different ways to declare a [string](https://github.com/aenoncunanan/Strings) in java: through the use of an equal sign, and by the use of new instance.
- In comparing strings, you cannot use the equal sign if the string are declared in different ways.
- The best way to compare string is by the use of `.equals()`.
- `.equals` can compare each character of the strings.
- `.equalsIgnoreCase` is the same with the `.equals` function, but it will ignore the case of the letters.
- You can also convert string into an array of characters using the `toCharArray` function.
- Java also allows you to add a preset string on user's input through the use of [String Builders](https://github.com/aenoncunanan/StringBuilder).
- It is also possible to get the total length of a string, or get the position of a certain word in the string, or cut the string, using the [parsing method](https://github.com/aenoncunanan/ParsingString).
- In java, you can automatically get or print the current date using the Date Utility.
- You can also change the formatting of the date and even add days on the current day through the use of Gregorian Calendar Utility.


#SESSION 5 (Wednesday, February 17, 2016):
###Debugging

- There are two types of [error](https://github.com/aenoncunanan/Errors) that will be encountered: first is the compile time error, where the error occurs during the compiling process, and the second one is the run time error, that occurs while the program is running.
- Using the IDE called IntelliJ, debugging the error can be easier becasue it helps you find the bug.
- One way of debugging is by the use of [try-catch](https://github.com/aenoncunanan/Exceptions) method.
- [Try-Catch](https://github.com/aenoncunanan/Exceptions) is the same with the If-Else method where it will try to execute the statement but outputs a message when a bug has occured and has been caught.
- Catching the error can be placed in a separate method by [throwing execptions](https://github.com/aenoncunanan/ThrowingExceptions).
- Java IDEs has a cool feature for [debugging](https://github.com/aenoncunanan/Debugger), where you can place a red dot to stop the runnig program on a certain line to identify where the bug is coming from.


#SESSION 6 (Friday, February 19, 2016):
###Collections

- Just like in C language, Java also has an [array](https://github.com/aenoncunanan/Arrays) data type.
- You can declare an array in different ways, first is placing the solid brackets after the data type but before the variable name: `int[] name` , and the other way is after placing the solid brackets after the variable name: `int name[]`.
- Java also supports [Multi-dimensional Arrays](https://github.com/aenoncunanan/2DArrays) like 2D arrays to be specific.
- Some arrays can be decalred with fix memory size.
- Just like a linked list, [array list](https://github.com/aenoncunanan/ArrayList) makes a dynamic array.
- Array List is more easier than Linked List.
- [Hash Map](https://github.com/aenoncunanan/HashMap) is like a combination of 2d Array, and Array List.
- In HashMap, the terms map and cap is important for this is the way to acess the value inside the hash map.
- Using the [iterator](https://github.com/aenoncunanan/Iterators), you will be able to list down the values inside an array list or a hashmap.


#SESSION 7 (Friday, February 19, 2016):
###CustomClasses

- To be able to minimize the lines of codes in your program, place the methods in a separate [class](https://github.com/aenoncunanan/CustomClasses).
- By making a [custom class](https://github.com/aenoncunanan/CustomClasses), it will be easier for you to debug the program.
- When there is already a bunch of classes and they work as a group, meaning they need each other to make a program funtion, place them inside a [package](https://github.com/aenoncunanan/Packages) for your codes to be organized.
- Through the use of the [instance method](https://github.com/aenoncunanan/InstanceMethod), the class now works as an object.
- An [instance variable](https://github.com/aenoncunanan/InstanceVariable) is similar to a class variable.
- Instance variable is defined in a class and belongs to an object.
- [Constructors](https://github.com/aenoncunanan/Constructors) helps you create an object.
- Constructor is similar to the instance method, but it does not have a return type.
- In [getters and setters](https://github.com/aenoncunanan/GettersAndSetters), getters are method that gets a private field, while setters are method that sets a new field.
- [Class Variables](https://github.com/aenoncunanan/ClassVariables) is different from instance variables.
- Class Variables are declared to be used by different objects, so if you change a value of a class variable, all of the objects using it, can see the new value.
