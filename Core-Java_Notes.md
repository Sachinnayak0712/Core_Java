# Core JAVA 
![learn_java_on_mac](https://github.com/Sachinnayak0712/Core_Java/assets/66566069/ccdeb405-b964-4b9f-83d6-7a3a728dbcf1)

## features of java
•	It is compiled.\
•	It is Robust.\
•	It is highly secured language.\
•	It is simple and easy to understand.\
•	High performance.\
•	Multithreaded.\
•	It is platform independent.

## History
james gosling-1991-greentalk(.gt) -oak(symbol of sterngth-N tree of germany)- 1995(legal issue)- java

## EXECUTION
![how-does-java-programming-language-work](https://github.com/Sachinnayak0712/Core_Java/assets/66566069/5e2f354e-16f0-47fd-b9d7-036a04975f1d)
write Java program in notepad it also called as source code which is human readable format once after writing the save the program without Java extension in the below to convert JAVA for human readable format into machine learning we go to prompt in functions Java C and Java Java for Java compilation which converts Java file into class file for Syntax rules and translated Java class file class file is a intermediate from which is not cannot be understood by human machine class is given input as and input to the interpreter here it will read line by line execute translate from class to binary format if Syntax or rules we get compile time error if you find any abnormal statement like automatic exception we get runtime error.\
JIT(just in time) convert .class to binary formate.\
JVM(java virtual mishine) exeute java program.\
JRE(java runtime environmenet) provide setup to run java program.\
JDK(library file and utility to execute java program)

## Basic Difination 
identifier = name given in java program.\
leterals = value used in java program(num, char, string, boolean).\
operator = symbol used to perform some operation on operands (unary(), arithmetic, shift, relational, bitwise, logical, ternary, assignment)

## Variable
Named memory location which is used to store some data and it can change N no of time. \
variable of 2 type.\
	1) Primitive type :-byte,short,int,long,double,char, boolean.\
	2) Non primitive type:-String,Array

#### Primitive Data Typre
type = default = length(byte)\
byte = 0 = 1\
short = 0 = 2\
int = 0 = 4\
long = 0 = 8\
float = 0.0f = 4\
double = 0.0d = 8\
char = '/u0000 = 2\
boolean = false = 1 bit\
string = null

## Local Variable
Any variable declared within the method is called as local variable\
Scope of local variable is from begin of method to end of the method\
It can not be default\
It cannot be static or non static\
It should be initalized before utilizing\

## Global Variable
Any variable declared within the class is called as global variable\
Scope of local variable is from begin of class to end of the class\
It can be default\
It can be static or non static\
It should be initalized before utilizing\

## Keyword
![JavaKeywords](https://github.com/Sachinnayak0712/Core_Java/assets/66566069/c85aed31-7b58-4296-98e5-fe61aa00917c)

## Method
Block of statement which will get executed whenever it is called or invoked\
There are 3 member\ 
1) Variable or function member\
2) Method or data member\
3) Constructor\

## Static Member of the class
Any member declare with key word static is called as static member of the class\
Static is one copy\
Static is always asociated with class\
When ever we want access atatic from one class to another class\
We have to use class_name.varaible_name\ 
or\      
class_name.method_name\

## Non-static Member of the class
Any member declare without key word static is called as non-static member of the class\
Static is multiple copy\
Static is always asociated with object\
When ever we want access non-static to another static\
We have to use object.varaible_name \
or\
object.method_name


## Constructor
This is a special member of the class used to intialize data member
Rule\
Constructor name should be same as class name\
Constructor will not have any return type\
Constructeo will not return any value\
Constructor is always non static\
When ever object is created constructor will get invoked

### This keyword
Then ever local and global variable name is same to differentiate between them we use this keyword\
This keyword is default reference variable\
Cannot be used in static context

## Conposition
A class haveing object of another class\
It also called as HasA relationship

## Block
#### SIB(Static Initalization Block):
Any block declared with keyword static
SIB will execute before main method\
We can have N no of SIB order of execution is sequential

#### IIB(Instance Initalization Block):
Any vlock declared without keyword static \
SIB will executed when ever object is created\
We ca have N no of SIB order of execution is sequential

## Array
It is linear data structure which is used to store homogennious type of data

## Method overloading
Developing multiple method with same name but variation in argument list is called as method overlaoding\
Variation in argument list\
1)variation in data type\
2)variation in order of occurance\
3)variation in length of the argument

#### rule
method name should be same\
variation argument list\
no ristrication on access specifier\
common operation we go for method overlaoding\
we can override static, non static and main method

#### program:-
class Order_par{\
static void order(int cost){\
SOP("order by cost " + cost);\
}\
static void order(String name){\
SOP("order by name " + name);\
}\
static void order(int cost, String name){\
SOP("order by cost " + cost +"and name " +name);\
}\
static void order(String name ,int cost){\
SOP("order by name " + name + "and cost"+cost);\
}\
}\
\
class Amazon_search{\
PSVM(----){\
Order_par.order(50000);\
Order_par.order("Oneplus 8T");\
Order_par.order(50000 ,"Oneplus 8T");\
Order_par.order("Oneplus 8T",50000);\
}\
}

## Method overriding
Developin a amethod in subclass with same name and signature as in super class but difference in implementation in sub class is called as method overriding

#### Rules
Method should be nonstatic\
Is a relationship\
Method name and signature should be sameas in the super class

## Super keyword
This is used in method overriding\
whenwver we need along with subclass implementation if we need super class implementation then we should go for Super keyword

## TYPE Casting
Converting from one type to another type is called as Type casting\
There are 2 type of type casting\
	1) Primitive type casting\
	2) Class type casting

### Primitive Type Casting
Converting from one primitive data type to another primitive data type is called as Primitive type casting\
There are 2 type of Primitive type casting
1) Widening\
2) Narrowing

#### Widening 
Converting from smaller primitive data type to any of its bigger primitive data type is called as Widening\
Widening can be done by both implisitly and explisitly\
double x=20; \					
SOP(x)\

double x=(double)20;\
SOP(x)

#### Narrowing 
Converting from bigger primitive data type to any of its smaller primitive data type is called as Widening \
Widening can be done only by explisitly\
double x=(double)41.4d\
SOP(x)

### Class Type Casting
Converting from one class object to another class type is called Type casting or derived type casting\
There 2 type of class casting\
	1) Up casting\
	2) Down casting

#### Up casting
Up casting converting subclass object to super class type is called Up casting\
It can be done implicitly and explicitly

#### Down casting 
Up casting converting super class object to sub class type is called Up casting\
It can be done explicitly

# OOPS
![java-oops](https://github.com/Sachinnayak0712/Core_Java/assets/66566069/bba7082e-13ff-44d1-8c27-e484b24f5e4f)

Class and Object\
Inheritance\
Polymorphism\
Encapsulation\
Abstraction\


## Class
Is a blue print to create object
## Object
Is real time entity which ahs state(nonstatic variable) and behaviour(nonstatic method)\
State:- what dat it can hold\
Behaviour:-the way it behave

## Inheritance
Inherting the property from one class to another class

### single level Inheritance
A subclass inheriting the property from only one super class
### multilevel level Inheritance
A subclass inheriting the property from only its super class intern super class inherting property from its super class
### Hierarchical Inheritance
Multiple sub calss inheriting property from only one super class
### Multiple Inheritance
A subclass inheriting the property from multiple super class
### Hyberid inheritance
Combination of single,multilevel,hierarchical inheritance

## Polymorphism
An object showing different behaivor at different stages of life cycle\
2 type of polymorphism\
	1) compile time polymorphism\
	2) run time polymorphism

### Runtime Polymorphism
Method declaration getting binded to it defination at runtime by the JVM based on the object created is called as Run time polymorphism\
Since method declaration gets binded at run time hence it is called as late binding\
Once method declaration gets binded to its defination it can be rebinded hence it is called dynamic binding\
Method overriding is an example

### Compiletime Polymorphism
Method declaration getting binded to it defination at compiletime by the compiler based on the arguments passed is called as Compile time polymorphism \
Since method declaration gets binded at run time hence it is called as late binding\
Once method declaration gets binded to its defination it can be rebinded hence it is called static binding\
Method overriding is an example


## Abstract class
1)concrete method:-any mehtod which has both declaration and defination\
2)concrete class:-any class which has only concrete method\
3)abstract method:-any method is declared with keyword abstract\
4)abstract class:- any class declared with keyword abstract\
5)if class consist of abstract method then compulsarily class should be declared as abstract but visa versa is not true\
6)an abstract class can have concrete and abstract method\
7)class which provide implementation to the abstract method is called as implentation class\
8) we cannot declare abstract method as static final and private\
9) if any one of the abstract method is not overridden in the subclass the subclass should be declared as abstract\
10) we can not create object for object class and interface throught abstract class we can achive upto 100% abstraction

## Abstraction:-
Hide the complexity of the system and exposing only required functionality to the end user

How to achive abstracton
To achive abstraction declare all essential property ininterface and provide implementation in The subclass. Create reference variable of interface type initialize the reference variable with the implementation class object this is how we can achive abstraction through interface we can achive 100% abstraction

## Encapsulation
Wraping of daata and function member into single unit is called as encapsulation

It is one of the oops principle in java\
Java is by default encapsulation\
we can not declare any variable outside the class\
we can not have any print statement outside the method\
declare the data member as private ristrict the direct acess outside the class and provide in direct acess through public services called getters and setters is called as encapsulation
there  is no rules it should be get and set\ 
get is used to get the value\
set is used to set the value\
*****************************************************************************************************************************************************************************************

## Interface
interface is java type. it is a pure abstract body\
2 member variable and method\
variable is by default public static and final\
method is by default default public and abstract\
interface is by default abstract\
interface doen't support constructor\
implements is keyword used to inherit property from interface to class\
if anyone of the abstract method is not overridden in sub class then that metod should be declared as abstract\
we can not create object for interface\
each and every class extends object class, object class is super most class\
interface is supermost class\
through interface we can achive multiple inheritance\
throught interface we can achive 100% abstraction\
classs which provide implementation for the abstract method is called as implementation

## Package: 
it is a folder structure which is used to store similar kind of file. package should be created in reverse order of URL
Ex:-  www.google.gmail.com\
	com-\
	    gmail-\
		  google-\
			 www\
    
Jave provide a akeyword called import which is used to import files from one package to another package
In any java file 1st statement should be package ststement\
2nd statement should be import statement we can have N no of import Statement\
3rd statement should be the java Type\
(class type, interface, enum and anotation

## Access Specifier
PUBLIC:-it can be accessd anywhere/by anyone
PROTECTED:-it can be accessed within the package and outside the package with isArelationship
DEFAULT:-It can be Accessed within the package within the class
PRIVATE:-can be accessed only within the class
##### note:
members of the class can have all 4 access specifier
the class can have only 2 access specifer (Public and Default)
we can develop multiple classes in a asingle file ehich ever class is declared with keyword public only that class is eligible to have main method


