# 📚 Linked List Implementation in Java

A simple **Linked List** implementation in **Java**, demonstrating core data structure operations such as insertion, deletion, traversal, and search.  
This project is ideal for learning or interview preparation.

---

## 🚀 Features

- Singly Linked List implementation  
- Add node (at head, tail, or specific position)  
- Delete node (by value or position)  
- Search for a node  
- Display all nodes  
- Fully commented and easy to understand  

---

## 🧩 Project Structure


- **Node.java** → Represents a single node in the linked list  
- **LinkedList.java** → Contains all core linked list operations  
- **Main.java** → Demonstrates usage of the linked list

---

## 🧠 Example Code

```java
// Node.java
public class Node {
    int data;
    Node next;

    public Node(int data) {
        this.data = data;
        this.next = null;
    }
}
