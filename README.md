# Java-Interview-Questions-Answers

Looking forward to appear in Java Interview, here are the key Java Interview Questions with Answers only for you.

### Table of Contents
| Sr.No.        | Question      | 
| ------------- |-------------| 
| 1             |[What are new Java8 Features?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#1-new-java8-features) | 
| 2             |[Difference between GET & POST METHODS?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#2-difference-between-get--post-methods) |
| 3             |[Difference between forward() method & SendRedirect() method?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#3-difference-between-forward-method--sendredirect-method) |
| 4             |[Difference between HashMap and HashTable?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#4-difference-between-hashmap-and-hashtable) |
| 5             |[Difference between HashSet and TreeSet?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#5-difference-between-hashset-and-treeset) |
| 6             |[What is meant by Collections in Java?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#6-what-is-meant-by-collections-in-java) | 
| 7             |[What is meant by Ordered and Sorted in collections?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#7-what-is-meant-by-ordered-and-sorted-in-collections) |
| 8             |[Explain about Set and their types in a collection?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#8-explain-about-set-and-their-types-in-a-collection) |
| 9             |[What is the final keyword in Java?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#9-what-is-the-final-keyword-in-java) |
| 10             |[What is a Thread?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#10-what-is-a-thread) |
| 11             |[Explain thread life cycle in Java](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#11explain-thread-life-cycle-in-java) |
| 12             |[Which methods are used during the Serialization and Deserialization process?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#12-which-methods-are-used-during-the-serialization-and-deserialization-process) |
| 13             |[When to use Runnable interface Vs Thread class in Java?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#13-when-to-use-runnable-interface-vs-thread-class-in-java) |
| 14             |[What is the life-cycle of a servlet?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#14-what-is-the-life-cycle-of-a-servlet) |
| 15             |[Differences between ServletContext vs ServletConfig?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#15-differences-between-servletcontext-vs-servletconfig) |

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 1. New Java8 Features

Java 8 provides following features for Java Programming:
*	Lambda expressions - Adds functional processing capability to Java. 
*	Method references - Referencing functions by their names instead of invoking them directly. Using functions as parameters. 
*	Functional interfaces,
*	Stream API - New stream API to facilitate pipeline processing. 
*	Default methods,
*	Base64 Encode Decode,
*	Static methods in interface,
*	Optional class,
*	Collectors class,
*	ForEach() method,
*	+36
*	Parallel array sorting,
*	Nashorn JavaScript Engine - A Java-based engine to execute JavaScript code. 
*	Parallel Array Sorting,
*	Type and Repeating Annotations,
*	IO Enhancements,
*	Concurrency Enhancements,
*	JDBC Enhancements etc.

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 2. Difference between GET & POST METHODS?

| GET        | POST      | 
| ------------- |-------------| 
|Limited amount of data can be sent because data is sent in the header.|Large amount of data can be sent because data is sent in the body.|
|Not Secured because data is exposed in the URL bar.|Secured because data is not exposed in the URL bar.|
|Can be bookmarked|Cannot be bookmarked|
|Idempotent|Non-Idempotent|
|It is more efficient and use than Post|It is less efficient and used|

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 3. Difference between forward() method & SendRedirect() method?

| forward() method        | sendRedirect() method      | 
| ------------- |-------------| 
|forward() sends the same request to another resource.|sendRedirect() method sends new request always because it uses the URL bar of the browser.|
|forward() method works at server side.|sendRedirect() method works at client side.|
|forward() method works within the server only.|sendRedirect() method works within and outside the server.|

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 4. Difference between HashMap and HashTable?

| HashMap        | HashTable      | 
| ------------- |-------------| 
|Methods are not synchronized|Key methods are synchronized|
|Not thread safe|Thread safe|
|Iterator is used to iterate the values|Enumerator is used to iterate the values|
|Allows one null key and multiple null values|Doesn’t allow anything that is null|
|Performance is high than HashTable|Performance is slow|

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 5. Difference between HashSet and TreeSet?

| HashSet        | TreeSet      | 
| ------------- |-------------| 
|Inserted elements are in random order|Maintains the elements in the sorted order|
|Can store null objects|Couldn’t store null objects|
|Performance is fast|Performance is slow|

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 6. What is meant by Collections in Java?

The Collection in Java is a framework that provides an architecture to store and manipulate the group of objects. Java Collections can achieve all the operations that you perform on data such as searching, sorting, insertion, manipulation, and deletion.Java Collection means a single unit of objects. The Java Collection framework provides many interfaces (Set, List, Queue, Deque) and classes (ArrayList, Vector, LinkedList, PriorityQueue, HashSet, LinkedHashSet, TreeSet). 

Collections are used to perform the following operations:
*	Searching
*	Sorting
*	Manipulation
*	Insertion
*	Deletion 

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 7. What is meant by Ordered and Sorted in collections?

**Ordered:**

It means the values that are stored in a collection is based on the values that are added to the collection. So we can iterate the values from the collection in a specific order.

**Sorted:**

Sorting mechanism can be applied internally or externally so that the group of objects sorted in a particular collection is based on properties of the objects.

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 8. Explain about Set and their types in a collection?

**Set**

Set cares about uniqueness. It doesn’t allow duplicates. Here the “equals ( )” method is used to determine whether two objects are identical or not.

**Hash Set:**
*	Unordered and unsorted.
*	Uses the hash code of the object to insert the values.
*	Use this when the requirement is “no duplicates and don’t care about the order”.

Example:
```java
public class Fruit {
  public static void main (String[] args){
    HashSet<String> names = new HashSet <=String>();
    names.add(“banana”);
    names.add(“cherry”);
    names.add(“apple”);
    names.add(“kiwi”);
    names.add(“banana”);
    System.out.println(names);
  }
}
```
Output:

[banana, cherry, kiwi, apple]

Doesn’t follow any insertion order. Duplicates are not allowed.

**Linked Hash set:**
*	An ordered version of the hash set is known as Linked Hash Set.
*	Maintains a doubly-Linked list of all the elements.
*	Use this when the iteration order is required.

Example:
```java
public class Fruit {
  public static void main (String[] args){
    LinkedHashSet<String> names = new LinkedHashSet <String>();
    names.add(“banana”);
    names.add(“cherry”);
    names.add(“apple”);
    names.add(“kiwi”);
    names.add(“banana”);
    System.out.println(names);
  }
}
```
Output:

[banana, cherry, apple, kiwi]

Maintains the insertion order in which they have been added to the Set. Duplicates are not allowed.

**Tree Set:**
*	It is one of the two sorted collections.
*	Uses “Read-Black” tree structure and guarantees that the elements will be in an ascending order.
*	We can construct a tree set with the constructor by using comparable (or) comparator.

Example:
```java
public class Fruits{
  public static void main (String[] args) {
    Treeset<String> names= new TreeSet<String>();
    names.add(“cherry”);
    names.add(“banana”);
    names.add(“apple”);
    names.add(“kiwi”);
    names.add(“cherry”);
    System.out.println(names);
  }
}
```
Output:

[apple, banana, cherry, kiwi]

TreeSet sorts the elements in an ascending order. And duplicates are not allowed.

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 9. What is the final keyword in Java?

**Final variable:**

Once a variable is declared as final, then the value of the variable could not be changed. It is like a constant.

Example:
```java
final int = 12;
```
**Final method:**

A final keyword in a method that couldn’t be overridden. If a method is marked as a final, then it can’t be overridden by the subclass.

**Final class:**

If a class is declared as final, then the class couldn’t be subclassed. No class can extend/inherit the final class.

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 10. What is a Thread?

In Java, the flow of an execution is called Thread. Every java program has at least one thread called main thread, the Main thread is created by JVM. The user can define their own threads by extending Thread class (or) by implementing Runnable interface. Threads are executed concurrently.

Example:
```java
public static void main(String[] args){//main thread starts here

}
```

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 11.	Explain thread life cycle in Java

Thread has the following states:
*	New
*	Runnable
*	Running
*	Non-runnable (Blocked)
*	Terminated

![Thread Life Cycle](https://user-images.githubusercontent.com/649439/167628356-49e0a73f-d0d9-47ce-a643-5288e068a060.png)


*	**New:** In New state, Thread instance has been created but start () method is not yet invoked. Now the thread is not considered alive.
*	**Runnable:** The Thread is in runnable state after invocation of the start () method, but before the run () method is invoked. But a thread can also return to the runnable state from waiting/sleeping. In this state the thread is considered alive.
*	**Running:** The thread is in running state after it calls the run () method. Now the thread begins the execution.
*	**Non-Runnable(Blocked):** The thread is alive but it is not eligible to run. It is not in a runnable state but also, it will return to runnable state after some time. For Example: wait, sleep, block.
*	**Terminated:** Once the run method is completed then it is terminated. Now the thread is not alive.

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 12. Which methods are used during the Serialization and Deserialization process?

ObjectOutputStream and ObjectInputStream classes are higher level java.io. package. We will use them with lower level classes FileOutputStream and FileInputStream.

ObjectOutputStream.writeObject —->Serialize the object and write the serialized object to a file.

ObjectInputStream.readObject —> Reads the file and deserializes the object.

To be serialized, an object must implement the serializable interface. If a superclass implements Serializable, then the subclass will automatically be serializable.

| Serialization        | Deserialization      | 
| ------------- |-------------|
|Serialization is the process which is used to convert the objects into byte stream|Deserialization is the opposite process of serialization where we can get the objects back from the byte stream.|
|An object is serialized by writing it an ObjectOutputStream.|An object is deserialized by reading it from an ObjectInputStream.|

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 13. When to use Runnable interface Vs Thread class in Java?

If we need our class to extend some other classes other than the thread then we can go with the runnable interface because in java we can extend only one class. If we are not going to extend any class then we can extend the thread class.

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 14. What is the life-cycle of a servlet?

There are 5 stages in the lifecycle of a servlet:

1.	Servlet is loaded
2.	Servlet is instantiated
3.	Servlet is initialized
4.	Service the request
5.	Servlet is destroyed

![image](https://user-images.githubusercontent.com/649439/167629455-326556a3-d24c-4c28-88de-c16a40b946de.png)

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 15. Differences between ServletContext vs ServletConfig?

| Serialization        | Deserialization      | 
| ------------- |-------------|
|Servlet config object represent single servlet|It represent whole web application running on particular JVM and common for all the servlet|
|Its like local parameter associated with particular servlet|Its like global parameter associated with whole application|
|It’s a name value pair defined inside the servlet section of web.xml file so it has servlet wide scope|ServletContext has application wide scope so define outside of servlet tag in web.xml file.|
|getServletConfig() method is used to get the config object|getServletContext() method is  used to get the context object.|
|for example shopping cart of a user is a specific to particular user so here we can use servlet config|To get the MIME type of a file or application session related information is stored using servlet context object.|

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

Wish you all the best.
