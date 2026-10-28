# OOPS INTRODUCTION:
Object Oriented Programming:
It is something like combination of Data and Code. Data is Attribute, Properties and Code is Procedures, Methods.
Objects are instance of class means 1 class have more than 1 objects.

# Procedure VS Object OP
1. Program is divided into Functions || Program is divided into Objects.
2. No inheritence || Inheritence.
3. Top down Approach || Bottom down Approach.
4. No Virtual Function || Virtual Function.
5. No Code Reusability || Reusability.
6. Less Secure (no data hiding) || Encapsulation is used to hide data.
7. Not easy to add new data || Easy to add new data.

# Features of OOP:
1. Classes and Objects:
Class is a user defined data types as user can define the class as per their needs which can have data memeber and function member and these respective things can be used by creating an instance of class.
Ex: class DOG:               ## it is our class.
          name = "babu"      ## this is our attribute for the class. In python attribute can be accessed using (.) dot.
   Lets create an object using this class.
   multiple objects can be created from each class, each with its own unique attribute.
   dog_1 = DOG()
   print(dog_1.name) --> babu as output
   class's attribute is shared across all instance of class.

**Desi m smjho ab tk kya pdha:**
hmari class ke pass 1 property thi ki name kya h babu so ish class se sbhi objects ka naam babu he hoga or baki properties jese age, color and baki sb object ke hisabh se alag alg ho skti h bt jo class ka attribute h vo sb share krte h. That's why we say Objects are instance of class.

2. Encapsulation:
means combine Data variable and Functions (methods) into single unit.
**Point to be noted that these are the same functions or methods which is used to manipulate our data or variable.** and this promotes security by data hiding.
This is because no others function of different class cant manipulate data of my class.

3. Abstraction:
Hiding the details and show only essential info.

4. Polymorphism (many forms):
ex: Function exhibit different behavior in different instances.
Function Overloading and Operator Overloading in Polymorphism.

5. Inheritance:
It allows a class to inherit attribute and methods from the another class.
ex: Animal : eat, sleeps:
almost every animal do so it is something like reusing something from another class and they also have thier individual inherits or features. Then it gives rise parent and child class.

6. Dynamic Binding:
Dynamic means Runtime not compile time and binding means connecting or linking, it is also late binding.
We will study Virtual Functions in this topic.
The Code associated with a given procedure call is not known until the time of call(Runtime).

7. Message Passing:
Objects communicate with each other as the request for a procedure execution.
it should contain: Name of object, Name of function, Information to be sent.

# Benefits of OOP: 
1. Reusability
2. Data Hiding
3. Message Passing
4. Security
5. Updates/Changes Easy
