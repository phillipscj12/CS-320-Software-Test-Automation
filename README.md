# CS-320-Software-Test-Automation

This repository contains my artifacts and reflections for CS 320.

---

## Project One Artifacts

- `project1/Contact.java`  
- `project1/ContactService.java`  
- `project1/ContactTest.java`  
- `project1/ContactServiceTest.java`  

## Project Two Summary & Reflections

- `project2/project2-summary-reflections.docx`

---

## Module Eight Journal Reflection

**1. How can I ensure that my code, program, or software is functional and secure?**  
I use a combination of rigorous unit testing (covering edge cases in `ContactTest` and `ContactServiceTest`), static code analysis tools (e.g. SpotBugs), and enforce input validation. For security, I avoid hard-coding credentials, use parameterized queries, and review third-party dependencies for known vulnerabilities.

**2. How do I interpret user needs and incorporate them into a program?**  
I start by writing **user stories** (“As a user, I want…”) and then map each story to concrete features or classes. For example, to let users store contacts, I designed `Contact` with only the fields they need and built `ContactService` to enforce the rules we gathered during requirements gathering.

**3. How do I approach designing software?**  
I follow a lightweight, iterative approach:  
1. Sketch UML or simple class diagrams.  
2. Break the problem into small, testable components.  
3. Define unit tests first (TDD).  
4. Use clear naming and single-responsibility classes to keep everything modular.
