# Java-Interview-Questions-Answers

### Table of Contents
| Sr.No.        | Question      | 
| ------------- |-------------| 
| 1             |[What are new Java8 Features?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#1-new-java8-features) | 
| 2             |[Difference between GET & POST METHODS?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#2-difference-between-get--post-methods) |
| 3             |[Difference between forward() method & SendRedirect() method?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#1-new-java8-features) |
| 4             |[Difference between HashMap and HashTable?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#1-new-java8-features) |
| 5             |[Difference between HashSet and TreeSet?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#1-new-java8-features) |
| 6             |[What is meant by Collections in Java?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#6-what-is-meant-by-collections-in-java) | 
| 7             |[What is meant by Ordered and Sorted in collections?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#1-new-java8-features) |
| 8             |[Explain about Set and their types in a collection?](https://github.com/aatul/Java-Interview-Questions-Answers/edit/master/README.md#8-explain-about-set-and-their-types-in-a-collection) |
| 9             |[What is the final keyword in Java?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#1-new-java8-features) |
| 10             |[What is a Thread?](https://github.com/aatul/Java-Interview-Questions-Answers/blob/master/README.md#1-new-java8-features) |
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
---

### 2. Difference between GET & POST METHODS?
---

### 3. Difference between forward() method & SendRedirect() method?
---

### 4. Difference between HashMap and HashTable?
---

### 5. Difference between HashSet and TreeSet?
---

### 6. What is meant by Collections in Java?

The Collection in Java is a framework that provides an architecture to store and manipulate the group of objects. Java Collections can achieve all the operations that you perform on data such as searching, sorting, insertion, manipulation, and deletion.Java Collection means a single unit of objects. The Java Collection framework provides many interfaces (Set, List, Queue, Deque) and classes (ArrayList, Vector, LinkedList, PriorityQueue, HashSet, LinkedHashSet, TreeSet). 

Collections are used to perform the following operations:
*	Searching
*	Sorting
*	Manipulation
*	Insertion
*	Deletion 
---

### 7. What is meant by Ordered and Sorted in collections?
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

If a class is declared as final, then the class couldn’t be subclassed. No class can extend the final class.


---

### 10. What is a Thread?

In Java, the flow of an execution is called Thread. Every java program has at least one thread called main thread, the Main thread is created by JVM. The user can define their own threads by extending Thread class (or) by implementing Runnable interface. Threads are executed concurrently.

Example:
```java
public static void main(String[] args){//main thread starts here

}
```
---
