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
| 16             |[Difference between SPRING CORE & SPRING BOOT?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#16difference-between-spring-core--spring-boot) |
| 17             |[REST API? What’s the benefit of using JSON over XML?](https://github.com/aatul/Java-Interview-Questions-Answers/edit/master/README.md#17rest-api-whats-the-benefit-of-using-json-over-xml) |
| 18             |[What are the different methods of session management in servlets?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#18what-are-the-different-methods-of-session-management-in-servlets) |
| 19             |[Let's talk about SOLID design principles. Could you quickly explain what are the main design principles in the current project?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#lets-talk-about-solid-design-principles-could-you-quickly-explain-what-are-the-main-design-principles-in-the-current-project) |
| 20             |[Difference between wait and notify() work in Java?](https://github.com/aatul/Java-Interview-Questions-Answers/edit/master/README.md#20difference-between-wait-and-notify-work-in-java) |

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

| ServletConfig        | ServletContext      | 
| ------------- |-------------|
|Servlet config object represent single servlet|It represent whole web application running on particular JVM and common for all the servlet|
|Its like local parameter associated with particular servlet|Its like global parameter associated with whole application|
|It’s a name value pair defined inside the servlet section of web.xml file so it has servlet wide scope|ServletContext has application wide scope so define outside of servlet tag in web.xml file.|
|getServletConfig() method is used to get the config object|getServletContext() method is  used to get the context object.|
|for example shopping cart of a user is a specific to particular user so here we can use servlet config|To get the MIME type of a file or application session related information is stored using servlet context object.|

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 16.	Difference between SPRING CORE & SPRING BOOT?

**Spring Framework:**
*	Spring is one of the most widely used Java EE Frameworks for building applications. 
*	For the Java platform, the Spring framework provides an elaborate programming and configuration model. 
*	It aims to simplify the Java EE development and helps developers be more productive at work. 
*	It can be used at any kind of deployment platform.
*	One of the major features of the Spring framework is the dependency injection. 
*	It helps make things simpler by allowing us to develop loosely coupled applications.

**Spring Boot:**
*	While the Spring framework focuses on providing flexibility to you, Spring Boot aims to shorten the code length and provide you with the easiest way to develop a web application. 
*	With annotation configuration and default codes, Spring Boot shortens the time involved in developing an application. 
*	It helps create a stand-alone application with less or almost zero-configuration.
*	Autoconfiguration is a special feature in Spring Boot. 
*	It automatically configures a class based on that requirement.


| Spring        | Spring Boot      | 
| ------------- |-------------|
|Spring Framework is a widely used Java EE framework for building applications.|Spring Boot Framework is widely used to develop REST APIs.|
|It aims to simplify Java EE development that makes developers more productive.|It aims to shorten the code length and provide the easiest way to develop Web Applications.|
|The primary feature of the Spring Framework is dependency injection.|The primary feature of Spring Boot is Autoconfiguration. It automatically configures the classes based on the requirement.|
|It helps to make things simpler by allowing us to develop loosely coupled applications.|It helps to create a stand-alone application with less configuration.|
|The developer writes a lot of code (boilerplate code) to do the minimal task.|It reduces boilerplate code.|
|To test the Spring project, we need to set up the sever explicitly.|To test the Spring project, we need to set up the sever explicitly.|
|It does not provide support for an in-memory database.|It offers several plugins for working with an embedded and in-memory database such as H2.|
|Developers manually define dependencies for the Spring project in pom.xml.|Spring Boot comes with the concept of starter in pom.xml file that internally takes care of downloading the dependencies JARs based on Spring Boot Requirement.|
|Spring is an open-source lightweight framework widely used to develop enterprise applications.|Spring Boot is built on top of the conven
tional spring framework, widely used to develop REST APIs.|

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 17.	REST API? What’s the benefit of using JSON over XML?

**REST API :- ** 

*	REST stands for representational state transfer.
*	A REST API (also known as RESTful API) is an application programming interface (API or web API) that conforms to the constraints of REST architectural style and allows for interaction with RESTful web services.  
*	An API is a set of definitions and protocols for building and integrating application software.  
*	It’s sometimes referred to as a contract between an information provider and an information user—establishing the content required from the consumer (the call) and the content required by the producer (the response). 
*	When a client request is made via a RESTful API, it transfers a representation of the state of the resource to the requester or endpoint. 
*	This information, or representation, is delivered in one of several formats via HTTP: JSON (Javascript Object Notation), HTML, XLT, Python, PHP, or plain text. 

**Benefits of using JSON over XML :- **
*	Less Verbose: JSON has a more compact style than XML, and it is often more readable. The lightweight approach of JSON can make significant improvements in RESTful APIs working with complex systems.
*	Faster: The XML software parsing process can take a long time. One reason for this problem is the DOM manipulation libraries that require more memory to handle large XML files. JSON uses less data overall, so you reduce the cost and increase the parsing speed.
*	Readable: The JSON structure is straightforward and readable. You have an easier time mapping to domain objects, no matter what programming language you're working with.
*	Structure Matches the Data: JSON uses a map data structure rather than XML's tree. In some situations, key/value pairs can limit what you can do, but you get a predictable and easy-to-understand data model.
*	Objects Align in Code: JSON objects and code objects match, which is beneficial when quickly creating domain objects in dynamic languages.
*	JSON Limitations: The limitations in JSON actually end up being one of its biggest benefits. A common line of thought among developers is that XML comes out on top because it supports modeling more objects. However, JSON's limitations simplify the code, add predictability and increase readability.

In comparison to an XML model, a JSON data structure is intuitive, making it easy to read and map directly to domain objects in whatever programming language is being used. 

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 18.	What are the different methods of session management in servlets?

Session is a conversational state between client and server and it can consist of multiple requests and responses between client and server. Since HTTP and Web Server both are stateless, the only way to maintain a session is when some unique information about the session (session id) is passed between server and client in every request and response.

Some of the common ways of session management in servlets are:
1.	User Authentication
2.	HTML Hidden Field
3.	Cookies
4.	URL Rewriting
5.	Session Management API

![image](https://user-images.githubusercontent.com/649439/167678579-d7277e08-3154-479c-bfdf-f36a63af646e.png)

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### Let's talk about SOLID design principles. Could you quickly explain what are the main design principles in the current project?

**SOLID principles** came from an essay written in 2000 by Robert Martin, known as Uncle Bob, where he discussed that a successful application will change and, without good design, can become rigid, fragile, immobile and viscous.

**Rigid —** Things are very fixed. You can’t move or change things without affecting other things, but it’s clear what will break if you make a change.

**Fragile —** Easy to move and change things but not obvious what else might break as a result.

**Immobile —** Code works fine but you can’t re-use code without duplicating or replicating it.

**Viscous —** Everything falls apart when you make a change, you quickly push it back together and get your change working. The same thing happens when somebody else comes along to make a change.

**The SOLID Principles -**

**S — Single Responsibility:**
- A class should have a single responsibility.
- ‘There should never be more than one reason for a class to change’.

**O — Open-Closed**
- Classes should be open for extension, but closed for modification.
- ‘A module should be open for extension but closed for modification’.

**L — Liskov Substitution**
- If S is a subtype of T, then objects of type T in a program may be replaced with objects of type S without altering any of the desirable properties of that program.
- ‘Subclasses should be substitutable for their base classes’.

**I — Interface Segregation**
- Clients should not be forced to depend on methods that they do not use.
- ‘Many client specific interfaces are better than one general purpose interface’.

**D — Dependency Inversion**
- High-level modules should not depend on low-level modules. Both should depend on the abstraction.
- Abstractions should not depend on details. Details should depend on abstractions.
- ‘Depend upon abstractions. Do not depend upon concretions.’

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

### 20.	Difference between wait() and notify() work in Java?

| wait()        | notify()      | 
| ------------- |-------------|
|When wait() is called on a thread holding the monitor lock, it surrenders the monitor lock and enters the waiting state.|When the notify() is called on a thread holding the monitor lock, it symbolizes that the thread is soon going to surrender the lock. Syntax: ```public final void notify()``` |
|There can be multiple threads in the waiting state at a time.|One of the waiting threads is randomly selected and notified about the same. The notified thread then exits the waiting state and enters the blocked state where it waits till the previous thread has given up the lock and this thread has acquired it. Once it acquires the lock, it enters the runnable state where it waits for CPU time and then it starts running.|
|Object.wait() to suspend a thread|Object.notify() to wake a thread up|
|Causes the current thread to release the lock and wait until either another thread invokes the notify() method or the notifyAll() method for this object, or a specified amount of time has elapsed.|Wakes up a single thread that is waiting on this object's monitor. If any threads are waiting on this object, one of them is chosen to be awakened. The choice is arbitrary and occurs at the discretion of the implementation.|

**[Back to Top](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#java-interview-questions-answers)**

---

Wish you all the luck.
