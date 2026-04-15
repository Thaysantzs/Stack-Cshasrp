# 🥞 Stack Implementation in C# (with Doubly Linked List)

This project contains a custom implementation of a **Stack (LIFO)** data structure built from scratch using **C#**.

Instead of using built-in collections, the stack is implemented on top of a custom **Doubly Linked List**, reinforcing core data structure concepts and code reusability.

---

## 📚 Implemented Structures

* 🔗 **Doubly Linked List** (`DoublyLinkedList<T>`)
* 🥞 **Stack (LIFO)** (`NewStack<T>`)

---

## 🧠 Key Concepts

* Generics (`<T>`)
* Linked data structures
* LIFO (Last In, First Out)
* Encapsulation
* Code reuse
* Time complexity optimization

---

## ⚙️ How the Stack Works

The stack uses a **doubly linked list** internally:

* `Push` → adds an element to the top (Head)
* `Pop` → removes the top element
* `Peek` → returns the top element without removing it

---

## 💻 Usage Example

```csharp
var stack = new NewStack<int>();

stack.Push(10);
stack.Push(20);
stack.Push(30);

Console.WriteLine(stack.Peek); // 30

stack.Pop();

Console.WriteLine(stack.Peek); // 20
```

---

## 📊 Time Complexity

| Operation | Complexity |
| --------- | ---------- |
| Push      | O(1)       |
| Pop       | O(1)       |
| Peek      | O(1)       |

---

## 🧪 Unit Tests

This project includes unit tests built with **NUnit**, covering:

* Core operations (Push, Pop, Peek)
* LIFO behavior validation
* Edge cases (empty stack, full stack)
* Generic type support

---

## 📁 Project Structure

```
Stack/
│
├── src/
│   ├── DoublyLinkedList.cs
│   └── NewStack.cs
│
├── tests/
│   └── NewStackTests.cs
│
└── README.md
```

---

## 🎯 Purpose

This project was created to:

* Understand how stacks work internally
* Practice building data structures from scratch
* Improve problem-solving and coding skills in C#
* Reinforce clean architecture and reusable code

---

## 🚀 Future Improvements

* Add more data structures (Queue, Tree, etc.)
* Create a unified data structures library
* Improve test coverage and performance analysis

---

## 👨‍💻 Author

**Thiago Santiago Rodrigues**
Aspiring Full Stack Developer 🚀

---

## ⭐ If you like this project

Give it a star and feel free to explore or contribute!

