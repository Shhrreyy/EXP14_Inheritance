# 🏛️ EXP-14: Inheritance in C++

## 🎯 Aim

To understand and implement different types of **inheritance** in C++ such as single, multiple, multilevel, and hierarchical inheritance, along with the role of access specifiers.

---

## 📚 Theory

- **Inheritance**  
  Inheritance is an **Object-Oriented Programming (OOP)** feature that allows a class (derived class) to acquire properties and behaviors (data members and member functions) of another class (base class).  

- **Types of Inheritance in C++**  
  1. **Single Inheritance** – One derived class inherits from one base class.  
  2. **Multiple Inheritance** – A derived class inherits from more than one base class.  
  3. **Multilevel Inheritance** – A chain of inheritance where one class is derived from another derived class.  
  4. **Hierarchical Inheritance** – Multiple derived classes inherit from a single base class.  

- **Access Specifiers**  
  - **Public** → Accessible from outside the class.  
  - **Protected** → Accessible in the class and its derived classes.  
  - **Private** → Accessible only within the class.  

---

## 🧮 Algorithms / Steps

### 1. **Single Inheritance (`Single.cpp`)**
- Define a base class with data members and functions.  
- Derive another class from it using inheritance.  
- Create an object of the derived class to access base class features.  

### 2. **Multiple Inheritance (`Multiple.cpp`)**
- Define two or more base classes.  
- Derive a single class that inherits from all base classes.  
- Show combined functionality in the derived class.  

### 3. **Multilevel Inheritance (`Multilevel.cpp`)**
- Create a chain of inheritance (e.g., `Class A → Class B → Class C`).  
- Each class adds new members/functions.  
- Demonstrate accessing features through the final derived class.  

### 4. **Hierarchical Inheritance (`Hierarchical.cpp`)**
- Define one base class.  
- Derive multiple classes from it.  
- Each derived class has its own additional members.  

### 5. **Access Specifiers (`Access_specifier.cpp`)**
- Demonstrate how `public`, `protected`, and `private` affect inheritance.  
- Show which members are accessible in derived classes and objects.  

---

## ✅ Conclusion

This experiment demonstrates the concept of **inheritance** in C++.  
- It shows how code reusability and hierarchy can be achieved through inheritance.  
- Different inheritance models solve different real-world problems.  
- Access specifiers control the visibility of inherited members, ensuring **encapsulation**.  

---

## 🧵 Topics Covered

- Concept of Inheritance  
- Single Inheritance  
- Multiple Inheritance  
- Multilevel Inheritance  
- Hierarchical Inheritance  
- Role of Access Specifiers in Inheritance  
