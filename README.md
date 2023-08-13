# TreeImp

# 2-3-4 Tree Implementation in Java

This project demonstrates the implementation of a 2-3-4 Tree, also known as a 234 Tree, in Java. A 2-3-4 Tree is a self-balancing tree data structure that can handle a variety of operations efficiently. This implementation includes classes for the tree node (`Node`), the tree itself (`Tree234`), and an application to interact with the tree (`Tree234App`).

## Features

- The `Node` class represents nodes in the 2-3-4 Tree and supports operations such as insertion, removal, finding items, and splitting nodes.
- The `Tree234` class encapsulates the logic of the 2-3-4 Tree and includes methods for searching and inserting items.
- The `Tree234App` class provides a simple command-line interface for interacting with the 2-3-4 Tree, allowing you to insert values, find values, and display the tree's structure.

## Usage

The project showcases the usage of a 2-3-4 Tree data structure and its fundamental operations. The `Tree234App` class demonstrates how to interact with the tree by inserting values and searching for them.

Here's a brief example of usage:

```java
Tree234 theTree = new Tree234();
theTree.insert(50);
theTree.insert(40);
theTree.insert(60);
theTree.insert(30);
theTree.insert(70);

while (true) {
    System.out.print("Enter first letter of show, insert, or find: ");
    char choice = getChar();
    // Handle different choices...
}

Feel free to explore the code and extend its functionalities as needed. The 2-3-4 Tree is a balanced tree structure that efficiently manages data.

For more details, refer to the source code files provided in the repository.
