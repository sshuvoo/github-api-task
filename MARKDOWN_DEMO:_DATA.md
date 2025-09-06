Markdown Demo: Data Structures

# Markdown Demo: Data Structures

## 📚 What is Markdown?

Markdown is a lightweight markup language that you can use to add formatting elements to plain text. It is commonly used for documentation.

---

## 📦 Data Structures Overview

Data structures are ways of organizing and storing data so they can be used efficiently.

### 1. Linear Structures

* **Array**: Fixed-size collection of elements.
* **Linked List**: Nodes connected with pointers.
* **Stack**: Last-In-First-Out (LIFO).
* **Queue**: First-In-First-Out (FIFO).

### 2. Non-Linear Structures

* **Tree**: Hierarchical data model.
* **Graph**: Network of connected nodes.

---

## ⏱ Time Complexity Table

| Operation | Array | Linked List | Stack | Queue | Hash Table |
| --------- | ----- | ----------- | ----- | ----- | ---------- |
| Access    | O(1)  | O(n)        | O(n)  | O(n)  | O(1)       |
| Search    | O(n)  | O(n)        | O(n)  | O(n)  | O(1)       |
| Insertion | O(n)  | O(1)        | O(1)  | O(1)  | O(1)       |
| Deletion  | O(n)  | O(1)        | O(1)  | O(1)  | O(1)       |

---

## ✅ Key Takeaways

* Choose the right data structure based on **access patterns** and **operations**.
* Arrays are great for random access, but linked lists are better for frequent insertions/deletions.
* Trees and graphs are essential for hierarchical and networked data.

---

## 📖 Example Code

```typescript
class Stack<T> {
  private items: T[] = []
  push(item: T): void {
    this.items.push(item)
  }
  pop(): T | undefined {
    return this.items.pop()
  }
}
```

---

## 🧠 Summary

Data structures are the **foundation of algorithms**. Mastering them leads to writing more efficient and elegant code.