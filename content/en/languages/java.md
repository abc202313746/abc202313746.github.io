---
title: Java
summary: Object-Oriented Task Management System
date: '2024-01-01T00:00:00Z'
type: page
searchable: true
tags: [Java, Object-Oriented, OOP, Programming Language]
---

<div class="justify-text">

# ☕ Java

## Overview
**Object-Oriented Task Management System**

A full-featured task management application built with Java, applying object-oriented programming principles including inheritance, polymorphism, and encapsulation. The system features user authentication, task scheduling, and data persistence using file I/O operations.

## Key Features

### 👤 User Management
- **User Authentication**: Login/logout system
- **Permission Management**: Role-based access control
- **Profile Management**: User information editing

### 📋 Task Management
- **Task Creation**: Add new tasks
- **Task Modification**: Edit existing tasks
- **Status Management**: Progress tracking
- **Priority Setting**: Importance-based classification

### ⏰ Scheduling
- **Date Management**: Deadline setting and notifications
- **Recurring Tasks**: Automatic periodic task creation
- **Calendar View**: Visual schedule management

## Object-Oriented Design

### 🏗️ Class Structure
- **User Class**: User information encapsulation
- **Task Class**: Task data model
- **TaskManager Class**: Task management logic
- **FileHandler Class**: Data persistence

### 🔄 OOP Principles Applied
- **Inheritance**: Reuse of common functionality
- **Polymorphism**: Interface-based design
- **Encapsulation**: Data protection and hiding
- **Abstraction**: Complexity reduction

## Technology Stack

- **Language**: Java 11+
- **IDE**: IntelliJ IDEA, Eclipse
- **Build Tools**: Maven, Gradle
- **Testing**: JUnit 5
- **Data Storage**: File I/O (JSON, CSV)

## Core Class Structure

### Task Class
```java
public class Task {
    private String id;
    private String title;
    private String description;
    private Priority priority;
    private Status status;
    private LocalDateTime dueDate;
    
    // Constructor, getters, setters
}
```

### TaskManager Interface
```java
public interface TaskManager {
    void addTask(Task task);
    void updateTask(String id, Task task);
    void deleteTask(String id);
    List<Task> getAllTasks();
}
```

## Learning Outcomes

Through this project, I learned how to apply Java's object-oriented programming principles to real-world applications and built a foundation for large-scale software design.

### Key Learning Points
- Object-oriented design pattern application
- Interface and abstract class utilization
- Exception handling and error management
- File I/O and data persistence

</div>
