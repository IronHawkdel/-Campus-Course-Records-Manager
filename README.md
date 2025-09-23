# Campus Course & Records Manager (CCRM)

A console-based Java SE application to manage campus records such as students, courses, enrollments, grades, transcripts, and file operations.  
Built as a **Java SE standalone application**, demonstrating OOP principles, design patterns, exception handling, Streams, recursion, and CLI workflows.  

---

## 📌 Project Overview & How to Run
- **Language**: Java SE 17+ (works with Java 11 too).
- **Build Tool**: Plain `javac` / `java` (no external dependencies).
- **Run Locally**:
  ```sh

  # Run program
  java edu.ccrm.cli.Main

# Questions Given In the Statement
## Evolution Of Java
1995: Java 1.0 released by Sun Microsystems ("write once, run anywhere").
1998 (Java 2 - J2SE): Introduced Swing, Collections Framework.
2004 (Java 5): Generics, Enums, Autoboxing, Annotations.
2011 (Java 7): Try-with-resources, NIO.2 file APIs.
2014 (Java 8): Streams API, Lambdas, default methods.
2017 (Java 9): Module system (JPMS).
2021+ (Java 17 LTS): Records, sealed classes.
Ongoing: Switch expressions, pattern matching, Project Loom (virtual threads).

## Java ME vs SE vs EE
### Java ME (Micro Edition)
Designed for small, resource-constrained devices.
Used in feature phones (pre-Android) and embedded systems like sensors.
Provides a cut-down set of APIs and a smaller JVM footprint.
Example: Mobile apps for old-school Nokia devices.

### Java SE (Standard Edition)
The core Java platform for general-purpose development.
Includes APIs for OOP, Collections, File I/O, Streams, multithreading, etc.
Used for desktop applications, command-line tools, small to medium server applications.
Example: Our Campus Course & Records Manager (CCRM) project is built on Java SE.

### Java EE (Enterprise Edition, now Jakarta EE)
Extends Java SE with enterprise-level features.
Adds support for Servlets, JSP, Enterprise JavaBeans (EJB), JPA, messaging (JMS), and Web Services.
Targeted at large-scale, distributed, server-side applications (e.g., banking software, e-commerce platforms).
Example: A large university portal with web-based course registration.

## JDK/JRE/JVM

### JVM (Java Virtual Machine)
The engine that runs Java bytecode.
Converts compiled .class files into machine instructions specific to your OS/CPU.
Provides features like automatic memory management (Garbage Collection), security (sandboxing), and platform independence — “Write Once, Run Anywhere.”
Every Java program runs inside a JVM. Without it, your .class files are just useless bytecode.

### JRE (Java Runtime Environment)
The package to run Java applications.
Includes the JVM + a set of standard libraries (core APIs) like java.util, java.io, java.net, etc.
Suitable for end-users who just want to execute Java programs (not write/compile them).
Think of it as the “player” needed to run Java applications.

### JDK (Java Development Kit)
The full development kit for Java programmers.
Includes everything from the JRE (JVM + libraries) plus developer tools such as:
javac → the compiler that turns .java files into .class bytecode.
javadoc → generates documentation.
javap → disassembler for debugging bytecode.
Debuggers, jar packagers, etc.
Required if you are writing or developing Java applications.
In other words, JDK = JRE + development tools.


