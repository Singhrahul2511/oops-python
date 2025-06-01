# 🐍 Object-Oriented Programming in Python – From Zero to Hero

Welcome to this repository where we master **Object-Oriented Programming (OOP)** concepts in Python step-by-step — from beginner to advanced level. Each concept includes clear explanations and Python code examples.

---

## 📚 Table of Contents

1. [What is OOP?](#what-is-oop)
2. [Class and Object](#1-class-and-object)
3. [Constructor (`__init__` Method)](#2-constructor-__init__-method)
4. [`self` Keyword](#3-self-keyword)
5. [Instance Variables vs Class Variables](#4-instance-vs-class-variables)
6. [Encapsulation](#5-encapsulation)
7. [Inheritance](#6-inheritance)
8. [Types of Inheritance](#7-types-of-inheritance)
9. [Method Overriding](#8-method-overriding)
10. [Method Overloading](#9-method-overloading)
11. [Polymorphism](#10-polymorphism)
12. [Abstraction](#11-abstraction)
13. [Static Method and Class Method](#12-staticmethod-and-classmethod)
14. [Magic Methods / Dunder Methods](#13-magic-methods--dunder-methods)
15. [Practice Projects](#14-practice-projects)
16. [Resources](#resources)

---

## What is OOP?

**Object-Oriented Programming (OOP)** is a programming paradigm where code is organized using objects — bundles of related data and behavior. It helps make code reusable, modular, and easy to maintain.

---

## 1. Class and Object

```python
class Car:
    def __init__(self, brand):
        self.brand = brand

car1 = Car("Toyota")
print(car1.brand)
