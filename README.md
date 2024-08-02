# Low Level Design Notes

## Table of Contents

1. [Introduction](#introduction)
2. [Requirements Gathering](#requirements-gathering)
3. [Architecture Design](#architecture-design)
4. [Low-Level Design](#low-level-design)
5. [high-level Design](#high-level-design)
6. [SOLID Principles](#solid-principles)

## Introduction

Provide a brief introduction to your project. Explain what the project is about, its main features, and its purpose.

## Requirements Gathering

### Key Activities
1. **Requirement Gathering**: Collecting and documenting the requirements from stakeholders.
2. **Architecture Designing**: Designing the overall system architecture.
3. **Component Design**: Defining the components and their interactions.
4. **Defining Protocols**: Establishing message structure and communication protocols.
5. **Creating UML Diagrams**: Visualizing the design through UML diagrams.
6. **Reviewing the Design**: Conducting design reviews to ensure accuracy and completeness.
7. **Refining the Design**: Iteratively improving the design based on feedback.

## Architecture Design

Describe the high-level architecture of the system. Include diagrams and explanations of the key components and their interactions.

## Low-Level Design

Low-level design is a component-level design process that follows a step-by-step refinement process. This section should detail the specific components, their responsibilities, and how they interact at a granular level. about the internal design of the individual modules identified during the hld phase. includes the detailed specifications of the code level, including algorithms, interface designs, procedural details and complete data models. encompasses the nitty gritty details that developers need to follow while coding.

## High-Level Design

focus on system architecture and overall framework. outlining the major components and their interactions with one another. designers and architects identify the software modules and their high level functionalities along with data flow, infrastructure and communication with third party services. defines the macro-level structure which is crucial for stack holder to understand.

## SOLID Principles

### S - Single Responsibility Principle (SRP)
A class should have only one reason to change, ensuring that each class addresses a single concern. In other words, a class should only have one job or responsibility.

### O - Open/Closed Principle (OCP)
Classes should be open for extension but closed for modification. This promotes scalability by allowing new functionality to be added without changing existing code.

### L - Liskov Substitution Principle (LSP)
Objects of a superclass should be replaceable with objects of a subclass without affecting the application. Use inheritance only when the subclass truly is a type of the superclass.

### I - Interface Segregation Principle (ISP)
Multiple specific interfaces are better than a single general-purpose interface. This ensures that implementing classes only need to be concerned with methods that are of interest to them.

### D - Dependency Inversion Principle (DIP)
One should depend upon abstractions, not concretions. High-level modules should not rely on low-level modules directly but rather on interfaces or abstract classes. This promotes decoupling and a more modular, loosely coupled architecture.



