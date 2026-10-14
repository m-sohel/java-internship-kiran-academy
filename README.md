# <div align="center">☕ Full Stack Java Developer Internship — The Kiran Academy</div>

<div align="center">

[![Java](https://img.shields.io/badge/Core_Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Hibernate](https://img.shields.io/badge/Hibernate_ORM-59666C?style=for-the-badge&logo=hibernate&logoColor=white)](https://hibernate.org/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![React](https://img.shields.io/badge/React_JS-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)

</div>

<div align="center">

[![Program](https://img.shields.io/badge/Program-3--Month_Intensive_Internship-0A66C2?style=flat-square&logo=google-classroom&logoColor=white)](#-internship-executive-profile)
[![Institute](https://img.shields.io/badge/Institute-The_Kiran_Academy_Pune-E02424?style=flat-square)](https://www.thekiranacademy.com/)
[![Track](https://img.shields.io/badge/Roadmap-Full_Stack_Java-success?style=flat-square&logo=target&logoColor=white)](#-the-official-3-pillar-roadmap)
[![Repository Status](https://img.shields.io/badge/Status-Actively_Maintained-brightgreen?style=flat-square&logo=github&logoColor=white)](#-internship-timeline--folder-structure)

</div>

---

## 📌 Executive Summary

Welcome to the central repository documenting my **3-Month Full Stack Java Developer Internship** at **The Kiran Academy**, Pune. 

This repository systematically captures daily practical assignments, object-oriented software design, database modeling, and modern web application development based on the official **Java Full Stack Roadmap**. The learning trajectory is split across three foundational pillars: **Back-end Engineering**, **Database Management**, and **Modern Front-end Development**, progressing towards modular, enterprise-ready web applications.

---

## 🧭 The Official 3-Pillar Roadmap

Guided by the curriculum of **The Kiran Academy**, the internship is structured across three core architectural layers:

```mermaid
flowchart TD
    subgraph Frontend["🎨 1. Front-end Layer"]
        FE1["HTML5 / Semantic UI"]
        FE2["React JS / Modern Components"]
        FE1 --> FE2
    end

    subgraph Backend["⚙️ 2. Back-end Layer"]
        BE1["Core Java ☕"]
        BE2["Servlets 🌐"]
        BE3["JSP 📑"]
        BE4["Spring Framework 🍃"]
        BE5["Spring Boot 🟢"]
        BE6["Hibernate ORM 🏛️"]
        BE1 --> BE2 --> BE3 --> BE4 --> BE5 --> BE6
    end

    subgraph Database["🗄️ 3. Database Layer"]
        DB1["MySQL Relational DB 🐬"]
    end

    Frontend <-->|"REST APIs / JSON / HTTP"| Backend
    Backend <-->|"Hibernate ORM / JDBC"| Database
```

| Layer | Technologies Covered | Role in Full Stack Architecture |
|:---|:---|:---|
| **1. Front-end** | **HTML5**, **React JS** | Client-side user interface, state management, component lifecycle, REST API consumption |
| **2. Back-end** | **Core Java**, **Servlets**, **JSP**, **Spring**, **Spring Boot**, **Hibernate** | Business logic, request/response lifecycle, MVC design pattern, dependency injection, microservices, ORM mapping |
| **3. Database** | **MySQL** | Relational schema design, normalization, ACID transactions, complex queries, JDBC/JPA persistence |

---

## 📋 Table of Contents

- [Executive Summary](#-executive-summary)
- [The Official 3-Pillar Roadmap](#-the-official-3-pillar-roadmap)
- [Internship Executive Profile](#-internship-executive-profile)
- [Detailed Technical Curriculum & Syllabus](#-detailed-technical-curriculum--syllabus)
  - [Pillar 1: Back-end Engineering](#1-back-end-engineering)
  - [Pillar 2: Database Management](#2-database-management-mysql)
  - [Pillar 3: Front-end Engineering](#3-front-end-engineering)
- [Internship Timeline & Folder Structure](#-internship-timeline--folder-structure)
- [Day 01 Detailed Case Study](#-day-01-detailed-case-study)
- [Local Development & Execution Guide](#-local-development--execution-guide)
- [Engineering Standards & Best Practices](#-engineering-standards--best-practices)
- [Author & Acknowledgments](#-author--acknowledgments)

---

## 📌 Internship Executive Profile

| Field | Details |
|:---|:---|
| **Candidate / Intern** | **Mohammad Sohel** ([@m-sohel](https://github.com/m-sohel)) |
| **Role Title** | Full Stack Java Developer Intern |
| **Training Organization** | **The Kiran Academy**, Pune, Maharashtra |
| **Program Duration** | **3 Months** (October 2026 – December 2026) |
| **Core Architecture** | Multi-Tier Enterprise Web Application (React + Spring Boot + Hibernate + MySQL) |
| **Training Focus** | Practical daily task delivery, clean code discipline, real-world full-stack capstone projects |

---

## 📚 Detailed Technical Curriculum & Syllabus

---

### 1. Back-end Engineering

The backend track forms the primary backbone of the internship, advancing from core Java programming fundamentals to enterprise-grade Spring Boot microservices.

#### ☕ A. Core Java
- **Language Fundamentals:** JVM architecture, Bytecode execution, ClassLoader subsystem, Memory Allocation (Heap vs. Stack vs. Metaspace).
- **Data Types & Operators:** Primitives, Wrappers, Autoboxing/Unboxing, Arithmetic/Bitwise/Logical operators, Type Casting & widening.
- **Control Flow & Logic Building:** Decision making (`if-else`, modern switch expressions), Looping (`for`, enhanced `for-each`, `while`, `do-while`), Nested iterations, Computational algorithms.
- **Object-Oriented Programming (OOP):**
  - **Encapsulation:** Access modifiers, Data hiding, POJOs, JavaBeans standards.
  - **Inheritance:** Single, Multilevel, Hierarchical; IS-A relationship; `super` keyword and constructor chaining.
  - **Polymorphism:** Compile-time Overloading vs. Runtime Dynamic Method Dispatch; method overriding with `@Override`.
  - **Abstraction:** Abstract classes vs. Pure Interfaces, default and static interface methods.
- **Strings & Memory Pool:** `String` immutability, String Constant Pool (SCP), `StringBuilder` and `StringBuffer` performance benchmarks.
- **Exception Architecture:** Checked vs. Unchecked exceptions, `try-catch-finally` blocks, `throw`, `throws`, Custom application exceptions.
- **Java Collections Framework (JCF):** `List` (`ArrayList`, `LinkedList`), `Set` (`HashSet`, `TreeSet`), `Map` (`HashMap` internal hashing & bucket mechanics, `TreeMap`), `Queue`.
- **Java 8+ Features:** Lambda Expressions, Functional Interfaces, Stream API (`filter`, `map`, `reduce`, `collect`), Optional class.
- **Multithreading & Concurrency:** Thread lifecycle, `Runnable` interface, Synchronization, Thread safety and race conditions.

#### 🌐 B. Servlets
- Web Application Architecture, Client-Server model, HTTP Protocol specs (GET, POST, PUT, DELETE).
- Servlet Lifecycle (`init()`, `service()`, `destroy()`).
- Processing HTTP requests and crafting responses via `HttpServletRequest` and `HttpServletResponse`.
- Session Tracking techniques: Cookies, `HttpSession`, URL Rewriting, Hidden Form Fields.
- Servlet Filters and Event Listeners for intercepting request pipelines.

#### 📑 C. JSP (JavaServer Pages)
- JSP Architecture and lifecycle phases (Translation, Compilation, Initialization, Execution).
- JSP Scripting elements: Scriptlets `<% %>`, Expressions `<%= %>`, Declarations `<%! %>`, Directives `<%@ %>`.
- JSP Action tags and standard tag libraries.
- JSTL (JSP Standard Tag Library) and EL (Expression Language) for maintainable presentation logic.
- Classic Model-View-Controller (MVC Architecture) using Servlets as Controllers and JSP as Views.

#### 🍃 D. Spring Framework
- Core Architecture of the Spring Framework.
- Inversion of Control (IoC) Container: `BeanFactory` and `ApplicationContext`.
- Dependency Injection (DI): Constructor Injection vs. Setter Injection patterns.
- Spring Bean Lifecycle, Bean Scopes (Singleton, Prototype, Request, Session).
- Aspect-Oriented Programming (AOP): Aspects, Advice, Pointcuts, Joinpoints.
- Spring MVC: `DispatcherServlet`, Controller mappings, Model attributes, ViewResolvers.

#### 🟢 E. Spring Boot
- Fundamentals of Spring Boot: Opinionated Defaults, Auto-Configuration, Spring Boot Starters.
- Embedded Application Servers (Tomcat, Jetty, Undertow).
- Developing RESTful Web Services: `@RestController`, `@RequestMapping`, `@GetMapping`, `@PostMapping`, `@PutMapping`, `@DeleteMapping`.
- Request payload binding: `@RequestBody`, `@PathVariable`, `@RequestParam`, `@ResponseStatus`.
- Exception Handling: Centralized `@ControllerAdvice`, `@ExceptionHandler`, unified API response structures.
- Spring Boot Actuator for application health metrics and production monitoring.

#### 🏛️ F. Hibernate ORM
- Object-Relational Mapping (ORM) principles and solving impedance mismatch.
- Hibernate Core Architecture: `Configuration`, `SessionFactory`, `Session`, `Transaction`, `Query`.
- JPA (Java Persistence API) Annotations: `@Entity`, `@Table`, `@Id`, `@GeneratedValue`, `@Column`, `@Transient`.
- Entity Relationship Mappings: One-to-One (`@OneToOne`), One-to-Many (`@OneToMany`), Many-to-One (`@ManyToOne`), Many-to-Many (`@ManyToMany`).
- Cascading types (`CascadeType`) and Fetching strategies (`FetchType.LAZY` vs `FetchType.EAGER`).
- HQL (Hibernate Query Language) & Criteria API for type-safe queries.
- Persistence Integration: Spring Data JPA repositories (`JpaRepository`, `CrudRepository`) with automatic query derivation.

---

### 2. Database Management (MySQL)

Enterprise backends rely on clean, normalized, and performant relational databases.

- **Relational Concepts:** Tables, Columns, Rows, Primary Keys, Foreign Keys, Composite Keys, Unique Constraints.
- **SQL Sublanguages:**
  - **DDL (Data Definition Language):** `CREATE`, `ALTER`, `DROP`, `TRUNCATE`.
  - **DML (Data Manipulation Language):** `INSERT`, `UPDATE`, `DELETE`.
  - **DQL (Data Query Language):** Complex `SELECT` queries, `WHERE`, `ORDER BY`, `GROUP BY`, `HAVING`, Aggregate functions (`COUNT`, `SUM`, `AVG`, `MAX`, `MIN`).
  - **DCL & TCL:** `GRANT`, `REVOKE`, `COMMIT`, `ROLLBACK`, `SAVEPOINT`.
- **Relational Joins:** `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `CROSS JOIN`, Self Joins.
- **Database Normalization:** 1NF, 2NF, 3NF, BCNF principles for eliminating redundancy and preserving integrity.
- **JDBC Integration:** Connecting Java applications to MySQL using MySQL Connector/J, executing `Statement` and parameterized `PreparedStatement` to guard against SQL Injection.

---

### 3. Front-end Engineering

Modern full-stack applications require responsive, dynamic, and intuitive user interfaces that seamlessly consume backend REST APIs.

#### 📄 A. HTML5
- Semantic HTML elements (`<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<footer>`).
- Modern Form Controls, validations, and input types (`email`, `number`, `date`, `pattern`).
- Web Accessibility standards (ARIA roles, semantic document hierarchy).
- Tables, Lists, and Rich Media elements (`<img>`, `<video>`, `<audio>`).

#### ⚛️ B. React JS
- Core React Principles: Component-Driven Architecture, Virtual DOM diffing & reconciliation.
- JSX (JavaScript XML) syntax and inline expression binding.
- Functional Components vs. Class Components.
- Component State (`useState`) and Props management (unidirectional data flow).
- Component Side Effects & Lifecycle via the `useEffect` hook.
- Event handling, conditional rendering, and rendering dynamic lists (`map()` with unique `key` props).
- Form handling: Controlled vs. Uncontrolled input components.
- REST API Integration: Consuming Spring Boot endpoints using `fetch` API and `Axios`.
- Single Page Application (SPA) client-side routing using React Router.

---

## 🗂️ Internship Timeline & Folder Structure

The repository is structured chronologically across the 3 calendar months, allowing incremental daily code tracking alongside modular topic packages:

```text
java-internship-kiran-academy/
│
├── 📁 October/                        # Month 1: Days 01 – 30 (30 Days)
│   │                                  # Focus: Core Java Fundamentals, OOP Logic & Computational Math
│   ├── 📁 Day01_Task1/                # Basic Syntax, Arithmetic Operators & Shopping Bill (Completed)
│   ├── 📁 Day02_Task2/                # Conditional Statements & Branching Logic
│   ├── 📁 Day03_Task3/                # Iterative Constructs & Loops
│   └── ... [Day04_Task4 to Day30_Task30]
│
├── 📁 November/                       # Month 2: Days 31 – 60 (30 Days)
│   │                                  # Focus: Advanced OOP, Exceptions, Collections, Servlets & JSP
│   ├── 📁 Day31_Task31/               # Class & Object Architectures
│   ├── 📁 Day32_Task32/               # Constructors & Polymorphic Design
│   └── ... [Day33_Task33 to Day60_Task60]
│
├── 📁 December/                       # Month 3: Days 61 – 90 (30 Days)
│   │                                  # Focus: Spring, Spring Boot, Hibernate ORM, MySQL & React JS
│   ├── 📁 Day61_Task61/               # Spring Boot REST API Construction
│   ├── 📁 Day62_Task62/               # Hibernate Entity Mapping & Persistence
│   └── ... [Day63_Task63 to Day90_Task90]
│
└── 📄 README.md                       # Comprehensive Internship Documentation & Syllabus Tracker
```

---

## 🌟 Day 01 Detailed Case Study

The practical journey started on **Day 01** in [`October/Day01_Task1`](./October/Day01_Task1), setting up disciplined coding conventions, foundational arithmetic logic, and a modular billing calculation:

```
Variables tested:
- Arithmetic: a = 20, b = 3
- Shopping Bill: a = 100, b = 100, c = 100, d = 100, e = 100
```

| Source File | Technical Focus | Formula / Implementation | Verified Output |
|:---|:---|:---:|:---|
| [`Hello.java`](./October/Day01_Task1/Hello.java) | Standard output stream | `System.out.println("Hello World")` | `Hello World` |
| [`Addition.java`](./October/Day01_Task1/Addition.java) | Integer binary addition | `a + b` | `Addition of 20 and 3 = 23` |
| [`Difference.java`](./October/Day01_Task1/Difference.java) | Integer subtraction | `a - b` | `Difference of 20 and 3 = 17` |
| [`Multiplication.java`](./October/Day01_Task1/Multiplication.java) | Integer multiplication | `a * b` | `Multiplication of 20 and 3 = 60` |
| [`Division.java`](./October/Day01_Task1/Division.java) | Explicit double casting | `(double) a / b` | `Division of 20 and 3 = 6.666666666666667` |
| [`Modulus.java`](./October/Day01_Task1/Modulus.java) | Remainder / Modulo operator | `a % b` | `Modulus of 20 and 3 = 2` |
| [`ShoppingBill.java`](./October/Day01_Task1/ShoppingBill.java) | Methods & Multi-tier GST Billing | `GST (18%, 13%, 7%) - 20% Disc.` | `Total after GST = 569.00 \| Discount = 113.80 \| Final payable amount = 455.20` |

---

## 💻 Local Development & Execution Guide

### 1. Development Prerequisites
Ensure the following developer toolchains are installed:
- **JDK (Java Development Kit):** 8 or newer (JDK 17/21 recommended for Spring Boot)
- **MySQL Server & Workbench:** For relational database storage
- **Node.js & npm:** For the React JS frontend layer
- **IDE:** IntelliJ IDEA / Eclipse / VS Code

### 2. Verify Installations
```bash
java -version
javac -version
mysql --version
node -v
npm -v
```

### 3. Clone Repository
```bash
git clone https://github.com/m-sohel/java-internship-kiran-academy.git
cd java-internship-kiran-academy
```

### 4. Running Java Tasks
```bash
# Example: Compiling and executing Day 01 Division Task
cd October/Day01_Task1
javac Division.java
java Division
```

---

## 🧼 Engineering Standards & Best Practices

All code committed across this 3-month internship strictly follows enterprise software engineering guidelines:

1. **Clean Code & Naming Conventions:**
   - Classes use `PascalCase` (`EmployeeService`, `Division`).
   - Variables and Methods use `camelCase` (`calculateBonus()`, `employeeId`).
   - Database tables use `snake_case` (`employee_records`, `order_items`).
2. **Layered Separation of Concerns (MVC Pattern):**
   - **Controller Layer:** Handles incoming HTTP requests and delegates to services.
   - **Service Layer:** Encapsulates business logic and transaction boundaries.
   - **Repository / DAO Layer:** Handles data persistence via Spring Data JPA / Hibernate.
   - **UI Layer:** Independent React components managing presentation and state.
3. **Repository Cleanliness & Version Control Hygiene:**
   - Zero tracked compiler artifacts (`.class` files, `target/`, `node_modules/`).
   - Every program is self-contained, verified, and free of extraneous debug logs.

---

## 👤 Author & Acknowledgments

- **Intern / Developer:** **Mohammad Sohel**
  - **GitHub:** [@m-sohel](https://github.com/m-sohel)
  - **Repository:** [java-internship-kiran-academy](https://github.com/m-sohel/java-internship-kiran-academy)
- **Training Institution:** [The Kiran Academy](https://www.thekiranacademy.com/), Pune, Maharashtra
- **Special Thanks:** Sincere appreciation to the instructors, mentors, and the technical team at The Kiran Academy for their structured curriculum, expert guidance, and continuous encouragement throughout this internship program.

---

<div align="center">
  <b>⭐ Star this repository if you find this Java Full Stack roadmap and code useful! ⭐</b><br>
  <i>Built with consistency, problem-solving passion, and clean code standards.</i>
</div>
