# Egyptian Wheat Tracking System

## Overview

The Egyptian Wheat Tracking System is a software application designed to monitor and manage the movement of wheat throughout the Egyptian wheat supply chain. The system tracks wheat from distribution centers through transportation, silos, mills, bakeries, and factories while ensuring quality control and quantity verification at every stage.

The project demonstrates the practical application of software design patterns within a real-world supply chain management scenario.

---

## Project Objectives

* Track wheat movement across multiple stages
* Monitor wheat quality and quantity
* Reduce wheat loss during transportation
* Improve supply chain transparency
* Automate transportation management
* Support flour and product manufacturing processes

---

## Design Patterns Used

### Singleton Pattern

Used for centralized wheat quality and quantity checking.

### Factory Pattern

Used to create different product types such as:

* Bread
* Local Bread
* Penna
* Spaghetti

### Template Pattern

Used to manage flour production processes:

* Flour92
* Flour82
* Flour72

### Observer Pattern

Used for transportation notifications between system stages.

### Iterator Pattern

Used to traverse transportation methods such as:

* Car
* Train
* Ship

---

## Technologies Used

* Java
* Object-Oriented Programming (OOP)
* UML Modeling
* Draw.io

---

## Repository Structure

```text
Documentation/
UML/
Source Code/
Presentation/
README.md
```

---

## System Workflow

1. Distribution receives wheat.
2. Transportation moves wheat to silos.
3. Silos store wheat.
4. Mills process wheat into flour.
5. Bakeries and factories produce final products.
6. Quality and quantity checks are performed throughout the process.

---

## Learning Outcomes

* Software Design Patterns
* Object-Oriented Design
* UML Modeling
* System Analysis
* Supply Chain Simulation
* Software Architecture Design

---

## Academic Purpose

This project was developed as part of the Software Components course and demonstrates the implementation of multiple software design patterns in a practical real-world scenario.
