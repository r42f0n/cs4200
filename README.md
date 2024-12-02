java c  Task 1:
In this assignment, you will write the code that manages the product categories on any website, such as Alibaba (Use another website). To get started:
• Create a new Java project called Project1 in IntelliJ.
• In the src directory, create a new class called AssignmentOne.
• In the AssignmentOne class, create the main method.
 Assessment Brief
2

  Module 1 - Advanced class design
The following part of the assessment covers the content in Module 1.
Part 1 – Creating abstract classes and interfaces
Go to the website you choose and explore all the different categories of products that they sell. While you are doing this, have a look at the different product categories as they go from more general to more specific. At the top level of the Inheritance hierarchy, you need a generic product. In your Java project:
• Create a new interface called Product with at least two generic methods that are suitable for ALL product categories on the the website you choose.
Alibaba sells physical and digital products. Therefore, in the inheritance hierarchy, under products, you would need to handle physical products and digital products. In your Java project:
• Create an abstract class called PhysicalProduct that implements the interface called Product.
• Create an abstract class called DigitalProduct that implements the interface called Product.
The PhysicalProduct and DigitalProduct abstract classes must have the following at a minimum that are suitable for ALL physical OR digital product categories on the Alibaba website:
• At least two instance variables
• A default constructor
• A second constructor that sets all the instance variables
• At least one abstract method
• At least one non-abstract method
• Any other methods or variables that you feel are necessary for the class to be usable in the program
Part 2 – Using abstract classes and interfaces
On the Alibaba website, choose one physical product category and one digital product category. In your project:
• Create one concrete class that extends the PhysicalProduct abstract class.
• Create one concrete class that extends the DigitalProduct abstract class.
The classes should match the physical product category and digital product category you chose on the Alibaba site and have the following at a minimum:
 Assessment Brief
3

  • At least two instance variables (one of these variables must be a boolean as a boolean instance variable is required in a later section of the assignment)
• A default constructor
• A second constructor that initialises all the instance variables (including the instance variables in the abstract superclass)
• A method that prints the Product details, e.g. "The product details are:" followed by all instance variables formatted for readability
(including the instance variables in the abstract superclass)
• Any other methods or variables needed so that your products match the physical product category and digital product category you
chose on the Alibaba site.
For each class, in the class comments, you MUST provide a link to the product category on Alibaba that you based
your class on. In the main method:
• Add the following comment - // Part 2 – Using abstract classes and interfaces
• Create an object for the concrete class that extends the PhysicalProduct abstract class using the constructor that sets all instance
variables.
• Create an object for the concrete class that extends the DigitalProduct abstract class using the constructor that sets all instance
variables.
• Add the following code - System.out.println(" -------------------- ");
Part 3 – Polymorphism
In the AssignmentOne class, write a method called demonstratePolymorphism that takes one parameter. The parameter type can be either a: • Product
• PhysicalProduct • DigitalProduct
In the main method:
• Add the following comment - // Part 3 – Polymorphism
• Add a second comment that explains how you are going to use the method you just created to demonstrate your understanding of
polymorphism
• Write the code to create an object and use the method you just created to demonstrate your understanding of polymorphism
• Add the following code - System.out.println(" -------------------- ");
 Assessment Brief
4

  NOTE: Do not remove the code in the main method for Part 2 (or any other part of the assignment). You can comment it out when you are developing; however, when you submit your assignment, the main method must contain all the code required for all parts of the assignment, i.e., your marker should be able to run your main method, and all parts of your assignment should run in one go.
Module 2 – Generics and lambdas
The following part of the assessment covers the content in Module 2.
In Part 2 of this assessment, you created a concrete class that extends the PhysicalProduct abstract class. For the remainder of this
assessment, this class will be referred to as yourClass as, in theory, all students should have a different name for this class.
Part 4 – Generic classes
In this part of the assignment, you are going to write the code for an ArrayList that can store instances (objects) of yourClass. In the main method, write the code to:
• Add the following comment - // Part 4 – Generic classes
• Declare an ArrayList
• Add at least 5 instances of yourClass to the ArrayList
• Add the following code - System.out.println(" -------------------- ");
Part 5 – Generic methods
In this part of the assignment, you are going to sort the ArrayList that we created in part 4.
In yourClass, implement the Comparable interface. When you implement the compareTo() method from the Comparable interface, you must use at least two instance variables in the comparison.
Once you have implemented the Comparable interface in the main method:
• Add the following comment - // Part 5 - Generic methods
• Write the code to sort the ArrayList that you created in Part 4.
• Add the following code - System.out.println(" -------------------- ");
  Assessment Brief
5

  Part 6 – Wildcards
In the AssignmentOne class, create a method called DemonstrateWildcards that takes an ArrayList generic parameter . In the method, call one of the methods from PhysicalProduct abstract class.
In the main method:
• Add the following comment - // Part 6 - Wildcards
• Add a second comment that explains how you are going to use the method you just created to demonstrate your understanding of wildcards
• Write the code to create an object and use the method you just created to demonstrate your understanding of wildcards
• Add the following code - System.out.println(" -------------------- ");
Part 7 – Simple lambda expressions
In the As代 写program、 Java
代做程序编程语言signmentOne class, create a method called DemonstrateLambdas that takes an ArrayList of yourClass and a Predicate as a parameter. In the method, test the Boolean instance variable from yourClass and print a suitable message based on whether it is true or false. In the main method:
• Add the following comment - // Part 7 - Simple lambda expressions
• Write the code to pass the Arraylist that you created in Part 4 to the DemonstrateLambdas method
• Add the following code - System.out.println(" -------------------- ");
 Assessment Brief
6

  Task 2
In this assignment, you will write the code that could form part of a management system for a school.
To get started:
• Create a new Java project called Project2 in IntelliJ.
• In the src directory, create five classes called:
o Person
o Staff
o Member
o Classroom
o AssessmentTwo
In the system you are creating:
• The Staff class is used to track the School staff, e.g., trainers, reception, etc.
• The Member class is used to track the School members.
• The Classroom class is used to track the classes offered at the School, e.g., Math, English, OOP, etc.
In the Person class:
• Add at least 3 instance variables suitable for a person
• Add a default constructor and a second constructor that sets the instance variables using parameters
• Add getters and setters for all Person instance variables
In the Staff class:
• Extend the Person class
• Add at least 2 instance variables suitable for School staff
 Assessment Brief
7

  • Add a default constructor and a second constructor that sets the instance variables (Staff and Person) using parameters
• Add getters and setters for all Staff instance variables •
In the Member class:
• Extend the Person class
• Add at least 2 instance variables suitable for a School member
• Add a default constructor and a second constructor that sets the instance variables (Member and Person) using parameters
• Add getters and setters for all Member instance variables
In the Classroom class:
• Add at least 3 instance variables suitable for a Clasrooms. One of these instance variables must be of type Staff, i.e. used to track the trainer running the Classroom.
• Add a default constructor and a second constructor that sets the instance variables using parameters.
• Add getters and setters for all Classroom instance variables.
In the AssessmentTwo class add the following code:
public class AssessmentTwo {
public static void main(String[] args) { }
public void partOne(){
}
public void partTwo(){
}
public void partThree(){
}
public void partFour(){
}
public void partFive(){
}
public void partSix(){
}}
 Assessment Brief
8

  Module 3 - Advanced Collections
The following part of the assessment covers the content in Module 3.
Part 1 – Lists
The Classroom class is missing the ability to store a collection of Members who have signed up for the Classroom. For this part of the assignment:
• Using a LinkedList, update Classroom so that a Classroom object can store a collection of Members (i.e. datatype Member) who have signed up for the
Classroom.
In addition to adding a LinkedList, you need to add the following methods to Classroom that work with the LinkedList:
• A method to add a Member to the Classroom.
• A method to check if a Member is in the Classroom.
• A method to remove a Member from the Classroom.
• A method that returns the number of Members in the Classroom.
• A method that prints the details of all Members signed up for the Classroom (you must use an Iterator or you will get no marks).
Note: Make sure all the above methods print suitable success/failure messages. Demonstration
In the partOne method in the AssessmentTwo class:
• Create a new Classroom object.
• Using the methods you created:
o Addaminimumof5MemberstotheLinkedList. o CheckifaMemberisintheLinkedList.
o RemoveaMemberfromtheLinkedList.
o PrintthenumberofMembersintheLinkedList. o PrintallMembersintheLinkedList.
 Assessment Brief
9

  Part 2 – Collection Class
There is no way to sort the Members who have signed up for a Classroom. For this part of the assignment:
• Create a class (you can choose the name) that implements the Comparator interface. When you implement the compare method from the Comparator interface, you must use a minimum of two of the instance variables in your comparison.
• Create a method in the Classroom class that sorts the LinkedList using the sort(List list, Comparator c) method in the Collections class. Note: You MUST use the Comparator interface. You CAN NOT use the Comparable interface.
Demonstration
In the partTwo method in the AssessmentTwo class:
• Create a new Classroom object.
• Using the methods you created:
o Addaminimumof5MemberstotheLinkedList.
o PrintallMembersintheLinkedList.
o SorttheLinkedList
o PrintallMembersintheLinkedListagaintoshowthattheLinkedListhasbeensorted.
Part 3 – Queue Interface
As most School classes would have a maximum number of members that can sign up, the program needs the ability to keep track of Members who are waiting to join the School class and the order in which they joined the waiting list, i.e., first in first out.
For this part of the assignment:
• Using a Queue, update the Classroom class so that a Classroom can store Members (i.e., Member objects) who are waiting to join the Classroom.
In addition to adding a Queue, you need to add the following methods to the Classroom class that work with the Queue:
• A method to add a Member to the Queue.
• A method to remove a Member from the Queue.
• A method that prints all the details for all Members in the Queue in the order they were added.
Note: Make sure all the above methods print suitable success/failure messages. Assessment Brief
10
 
  • •
Demonstration
In the partThree method in the AssessmentTwo class:
Create a new Classroom object. Using the methods you created:
o Addaminimumof5MemberstotheQueue.
o Remove a Member from the Queue. Print all Members in the Queue.
 Assessment Brief
11

  Submission
Submission ZIP file via USB drive (U盘) (Name+ Complete student number + Assignment 1) You are required to submit Three items for this assessment, including:
• Project 1
• Project 2
• A 10 minutes video explain Project 1 and Project 2
Assessment Criteria
• Java code compiles with Java 17 LTS.
• Use of correct coding style, including the use of comments.
• Accuracy of coding.
• Use of suitable coding structures.
• Correct submission and naming conventions of assessment items as required.
 Assessment Brief
12

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
