#  Answer to each question in details (You can google to find answers)

- What is Java and what are its key features? 
Java is a programming language with some key features like being simple, secure, and object oriented. 
- How do you declare and use variables in Java? 
You declare variables by labeling them by what they are, an integer will use the label int, a string will use String, and so on.
You use these variables after labeling them with the correct type by referring to them or calling them in things such as equations.
- What is a class in Java and how do you define one? 
A class is used to create objects, variables, and methods. The class is defined by using the word class in front of whatever you want to call it by.  
- What is encapsulation and how is it achieved in Java? 
Encapsulation is the use of all methods and variables needed for an object to work while being contained in the same object.
- How do you create objects in Java and what is their role in the program? 
You create objects in java by declaring it and creating a new keyword that is created by the object. This is then called by within a constructor which will initialize it.
Objects are useful as they can be edited and used in different types of methods.
- What is the difference between a method and a constructor in Java? 
A method and a constructor are very similar, but the main difference being that constructors are used mainly to initialize objects. 
- How do you implement inheritance in Java and what are its benefits? 
Inheritance is when a class is inheriting the fields and methods of another class, this is done by using the extends keyword.
The benefits are when you are working with very similar classes with slight differences. The reusability of the code makes it faster.
- What is abstraction and how is it achieved in Java?  
 Abstraction is when you are hiding certain details and showing only essential information. It is achieved when you use abstract class or interfaces like
when using inheritance.
- How do you work with arrays and ArrayLists in Java and what are their differences?
Arrays have a fixed amount of data inside of it, and the ArrayLists is does not have a fixed amount of data.
You have to declare how many objects are in an array, but you don't have to declare how many objects 
are in an arraylist since you can add as many as you want.
- How do you use control statements such as if, else, and switch in Java?
These control statements control the flow of execution of a method based on the conditions stated within
the parentheses.
- What is a loop and how do you implement it in Java?
A loop is used to run a part of the method several times. It is used by a for(), while() do{}while() loop.
it checks if the condition is ture. If it is true, it runs the loop until the conditions returns false.
- What is a method signature in Java and why is it important?
a method signature is at the end of a method header, it states what the method name is and what the parameters are.
- What is a package in Java and how do you create one? 
a package is a way to contain and encapsulates a group of classes, sub-packages, and interfaces. 
Its is created by writing package and then the package name afterwards or importing built-in Java packages.
- How do you use the String class in Java and what are some of its useful methods? 
a String class in java are used by defining the object with String in front of it. Useful methods
are int .length() it returns the length of the string and .replaceAll() it replaces the substring with whatever new string you want
- What is a constructor in Java and how is it used to create objects? 
It is similar to a method. It is called when an instance of the class is created, and when the constructor
is called it constructs the values at the time of object creation.
- How do you implement encapsulation in Java and why are they important in OOP?
It is implemented by making instance variables private, so only the class can use the data and 
using getters and setters to retrieve and change the values of the instance variables.
Encapsulation preserves code-reusablilty, and can hide certain data from the user. 
- What is object-oriented programming and what are its main principles?
It is a better programming style because you need not write code that needs to run anytime. Instead, 
you can create classes and define functions within them and call those function by creating an object of them.
The main principles of OOP are abstraction, encapsulation, inheritance, and polymorphism.
- What is the difference between a class and an object in OOP?
A class is like a blueprint that contains values(data) and some set of rules(methods). Whereas the
objects are created from these classes.
- What are the access modifiers in Java and how are they used to control access to class members?
Access modifiers in java have to deal with visibility of fields(static and non-static variables), 
methods, and constructors in a class. They control the access by limiting what can access them like the 
public modifier makes it so that it can be access from everywhere, but a private modifier makes whatever
is within what is being made private only accessible within itself. 
- How do you implement method overloading and overriding in Java?
Method overloading is used to implement static polymorphism. Method overriding is used to implement dynamic polymorphism.
- How do you create and manipulate String objects in Java? 
You create a string by using the String class and then set a variable to equal whatever string you type in.
You can manipulate String objects in Java by making it an object and using a String class method such as
int length().
- What is the purpose of the length() method in the String class? 
The purpose of the length() method in the String class is to return the length of the string.
- How do you concatenate Strings in Java and what is the most efficient way to do so? 
You concatenate strings in Java by adding them together to make on string. The easiest way is to use a +
in-between the strings 
- What is a substring in Java and how do you extract it from a String? 
A substring in Java is portion of the original string. You can extract it by using the substring() method.
- How do you compare Strings in Java and what is the difference between == and equals()? 
You can compare strings in java by using the equals() method, == operator, or compareTo() method.
The difference between == and equals() is that == is used to compare primitive type data, and equals()
is used to compare two different object on the basis of their memory locations such as data heap.
- What is the role of the char data type in Java and how is it used? 
char data type is used to store one character. It can be used by holding the unsigned 16-bit Unicode characters.
- What is Unicode and how does it relate to the char data type in Java? 
a Unicode is a unique code given to characters using the hexadecimal system. its is related to char data types
because you can use the code to return a certain character using the char data type. 
- How do you convert a char to a String in Java and vice versa?
You can use the character toString() method to convert character to the string, and you can convert a 
string by using a loop and charAt() method then adding the character from each loop iteration. 
- What is the difference between char and Character in Java? 
char is a primitive data type and Character is a class.
- What are escape sequences and how are they used with characters in Java?
Escape sequences are used to signal an alternative interpretation of a series of characters.
- How do you create a char array in Java and what are its uses? 
You create a char array by declare it and initializing it. The uses are that you can store the characters
in a row with an index.
- What is the ASCII code and how is it related to the char data type?
ASCII code is the most common character encoding format for text data in computers and on the 
internet. It is related to char data types because every char has an ASCII code that is assigned to it.
- How do you convert a character to its corresponding ASCII value in Java? 
You can use casting or just simply use the int data type for a variable and set it equal to the character
you want to convert. 
- What is a Unicode character and how is it represented in Java? 
a Unicode is a unique code given to characters using the hexadecimal system. it is represented by using
a \u infront of the code for the character.
- How do you determine the type of a character in Java?
The isDigit() function can be used to check whether a character is a digit or not. It has to be either or.
- How do you perform case conversion on a character in Java? 
You can use the toUpperCase()to make it upper case or toLowerCase() method to make it lower case.
- What are some of the useful methods available in the Character class in Java? 
some useful methods are equals(), isDigit(), and toString().
- How do you compare characters in Java and what is the difference between == and equals() when used with characters?
You can compare characters in java by using the equals() method, == operator, or compareTo() method.
The difference between == and equals() is that == is used to compare primitive type data, and equals()


