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
Method name and signature should be sameas in the super class\

## Super keyword
This is used in method overriding\
whenwver we need along with subclass implementation if we need super class implementation then we should go for Super keyword

## TYPE Casting
Converting from one type to another type is called as Type casting\
There are 2 type of type casting\
	1) Primitive type casting\
	2) Class type casting

### Primitive Type Casting
converting from one primitive data type to another primitive data type is called as Primitive type casting\
There are 2 type of Primitive type casting
1) Widening\
2) Narrowing
\
#### Widening 
converting from smaller primitive data type to any of its bigger primitive data type is called as Widening\
Widening can be done by both implisitly and explisitly\
double x=20;\					
SOP(x)\
\
double x=(double)20;\
SOP(x)

#### Narrowing 
Converting from bigger primitive data type to any of its smaller primitive data type is called as Widening \
Widening can be done only by explisitly\
double x=(double)41.4d\
SOP(x)

### Class Type Casting
Converting from one class object to another class type is called Type casting or derived type casting\
there 2 type of class casting\
	1) Up casting\
	2) Down casting\

#### Up casting
Up casting converting subclass object to super class type is called Up casting\
it can be done implicitly and explicitly

#### Down casting 
Up casting converting super class object to sub class type is called Up casting\
it can be done explicitly



