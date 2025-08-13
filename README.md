# Qt-Based-Library-Management-System-
A comprehensive C++ library management application built with Qt Widgets framework, featuring both console-based storage demos and a full GUI interface for managing books and magazines.

## **Features**

### **Console Application**
-Template-based Storage System: Generic Storage<T> class for type-safe data management

-Interactive Testing: Command-line interface for testing storage operations

-Demo Functions: Pre-built demonstrations for books, magazines, integers, and strings

-Memory Management: Proper allocation and deallocation of dynamic objects

### **Gui components**
  Modern Interface: Clean, intuitive GUI built with Qt Widgets
  Library Item Management: Add, borrow, and return books and magazines
  Search & Filter: Real-time search by title/author and filter by item type
  Visual Status: Color-coded items (green=available, yellow=borrowed)
  Sample Data: Pre-loaded with example books and magazines

  ## **Requirements**
-Qt Framework: Qt 6.0 or higher

-Compiler: C++17 compatible compiler (GCC 8+, Clang 10+, MSVC 2019+)

-Operating System: Windows, macOS, or Linux

## **Academic**
This project was developed as part of a C++ programming course focusing on:

Object-oriented programming principles

Template metaprogramming

Qt GUI development

Memory management

Design patterns

## **Customization**

Create new class inheriting from LibraryItem
Implement required virtual methods
Add UI elements in LIBRARYMENU.cpp
Update the storage demos if needed

### **Modifying Storage Behavior**

Edit Storage.h to add new methods

Update Storage.cpp for demo implementations

Modify template specializations as needed

### **GUI Customization**

Modify setupUI() in LIBRARYMENU.cpp

Add new buttons, dialogs, or layouts

Update stylesheets for different visual themes
