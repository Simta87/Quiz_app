Interview Question 

Ques1 .What is the difference between put and post ?

Ans- The PUT method is used to create a new resource or replace an existing resource with a new representation.

PUT is used to send data to a server to create/update a resource.
PUT is considered idempotent, meaning that making multiple identical PUT requests should have the same effect as a single request.
Usage: When using PUT, the entire representation of the resource is sent in the request payload. If the resource already exists, it is replaced entirely with the new representation sent in the request.

PUT
POST
Replacing existing resource or creating if resource is not exit 
Creating new resource
idempotent
Non idempotent

Q. What is difference between ArrayList and LinkedList?
ArrayList and LinkedList both implements List interface and maintains insertion order. Both are non synchronized classes.


ArrayList
LinkedList
01.
ArrayList internally uses a dynamic array to store the elements.
LinkedList internally uses a doubly linked list to store the elements.
02.
Manipulation with ArrayList is slow because it internally uses an array. If any element is removed from the array, all the bits are shifted in memory.
Manipulation with LinkedList is faster than ArrayList because it uses a doubly linked list, so no bit shifting is required in memory.
03.
An ArrayList class can act as a list only because it implements List only.
LinkedList class can act as a list and queue both because it implements List and Deque interfaces.
04.
ArrayList is better for storing and accessing data.
LinkedList is better for manipulating data.


STRING CONSTANT POOL

String constant pool - it is a place in heap memory where string literal objects are stored.
public static void main(String[] args) {
//STRING CAN BE CREATED USING NEW KEYWORD,IT WILL CREATE TWO OBJECTS, ONE
// IN THE HEAP MEMORY AND ONE IS IN THE
// STRING CONSTANT POOL WHICH WILL REFERENCE BY JVM INTERNALLY.
// STRING CAN BE CREATED BY STING LITERALS. IT WILL CREATE INE OBJECT IN THE STRING POOL
//SCP os not eligible for garbage collection


      String str1 = new String("JAVA");
      String str2 = new String ("JAVA");
      String s1 = "simta";
      String s2 ="JAVA";
      System.out.println(str1.equals(s2));
       System.out.println(str1 == s2);
       System.out.println(s1.concat("kumari"));
}}
Ques. Why Strings are immutable ?

Let us say
String s1 =”delhi”;
String s2 =”delhi”;
String s3 =”delhi”;
String s4 =”delhi”;
String s5 =”delhi”;
Here the ref value of all variables are the same ,so it will not create  5 objects in the SCP, it will point to the same object.

QUES 3. WHAT IS DIFFERENCE BETWEEN == AND EQUALS?

Ans == is used for reference comparison (address comparison).it will check whether both objects point to the same memory location or not .

equals() method is used for content comparison. It will check whether both objects have the same value or not.

Ques 4 .What are different  String constructors?
Ans. 


