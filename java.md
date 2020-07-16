### Java Virtual Machine
Java Virtual Machine loads static data-members only on-demand, Thread safe singleton class

### Collections
1. Hashmap performance factors? 1) Initial Capacity 2) Load Factor

### String
1. What is String pool?

### Object oriented programming (OOP)
1. What is difference between Shallow and deep clonning in java
2. Importance of nested and inner classes in java
3. Differenciate Local, Nested, inner, Anonymous and static classes in Java.

### Multithreading & Synchronization
1. Dead lock detection in java

2. Executor API 

  Decouples threads creation and management from application logic.
  
3. Thread pool

  Pool with fixed number of threads, Reuse threads when already running threads
are completed.

4. Callable vs Runnable

  Callable returns Future<Type> while Runnable do not returns any value.
  Callable throws checked exceptions, runnable do not throws any exceptions.
  
5. Synchronization challenges

  - Race condition
  - Deadlock
  - Starvation
  - Livelock
  
### Basic Concepts
1. What is difference between final vs effective final?
2. What is Java Object Graph (https://github.com/bramp/objectgraph)
3. Is Java Pass by value or Pass by reference
4. How Java class loaders works

### J2EE
1. Servlet life cycle `init() -> service() -> destroy()`
2. servlet response redirect vs forward
3. interceptors vs filter [filter is in servlet context & interceptor is spring context]

### Generics

### Memory
1. Difference between Hash memory and Stack memory
2. What is memory leakage and how to prevent. Garbage collector role in memory management. https://www.baeldung.com/java-memory-leaks

### Iterations, Streams, Enumeration
1. Define Fail-fast & Fail Safe

### Design Patterns
1. Dependency Injection (https://github.com/google/guice/wiki/Motivation)

### Links
https://dzone.com/articles/10-tricky-interview-questions-for-java-devs

### Java8 and Beyond
1. What is method reference in Java8?
2. What is 'this' in lambda expression?
3. What is lambda expression in Java?
4. Exception handling in Lambda expression?
