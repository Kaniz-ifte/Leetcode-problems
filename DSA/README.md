# 📚 Common Data Structures in Programming

A categorized overview of frequently used data structures across popular programming languages — **Java**, **Python**, and **C++**.

---

## 🔢 1. Linear Data Structures

| **Structure** | **Description**                      | **Java**          | **Python**        | **C++**            |
|---------------|--------------------------------------|-------------------|-------------------|--------------------|
| Array         | Fixed-size, indexed collection       | `int[]`           | `list`            | `int arr[]`        |
| List          | Dynamic, ordered collection          | `ArrayList`       | `list`            | `std::vector`      |
| Vector        | Resizable array (thread-safe in Java)| `Vector`          | `list`            | `std::vector`      |
| Stack         | LIFO (Last In First Out)             | `Stack` / `Deque` | `list.pop()`      | `std::stack`       |
| Queue         | FIFO (First In First Out)            | `Queue` / `Deque` | `collections.deque` | `std::queue`     |
| Deque         | Insert/remove from both ends         | `ArrayDeque`      | `collections.deque` | `std::deque`     |

---

## 🧩 2. Associative / Mapping Structures

| **Structure**     | **Description**                     | **Java**       | **Python**  | **C++**         |
|------------------|--------------------------------------|----------------|-------------|-----------------|
| Dictionary / Map | Key-value pair storage               | `HashMap`      | `dict`      | `std::map`      |
| Hash Table       | Underlying fast lookup by hash       | `HashMap`      | `dict`      | `std::unordered_map` |

---

## 🌳 3. Tree-Based Structures

| **Structure**        | **Description**                    |
|----------------------|------------------------------------|
| Binary Tree          | Tree with ≤ 2 children per node    |
| Binary Search Tree   | Sorted binary tree (Left < Root < Right) |
| Heap                 | Min/Max priority-based tree        |
| Trie                 | Prefix tree used for strings       |

---

## 🕸️ 4. Graph-Based Structures

| **Structure**     | **Description**                      |
|-------------------|--------------------------------------|
| Graph             | Nodes (vertices) + edges             |
| Adjacency List    | List-based graph representation      |
| Adjacency Matrix  | Matrix-based graph representation    |

---

## 🧮 5. Set-Based Structures

| **Structure** | **Description**                          | **Java**    | **Python** | **C++**          |
|---------------|------------------------------------------|-------------|------------|------------------|
| Set           | Unordered unique elements                | `HashSet`   | `set`      | `std::set`       |
| Ordered Set   | Sorted set (based on BST)                | `TreeSet`   | `OrderedDict` (as substitute) | `std::set` |

---

## ✅ Summary Cheat Table

| Structure Type | Java           | Python         | C++              |
|----------------|----------------|----------------|------------------|
| Array          | `int[]`        | `list`         | `int arr[]`      |
| List           | `ArrayList`    | `list`         | `std::vector`    |
| Stack          | `Stack`        | `list.pop()`   | `std::stack`     |
| Queue          | `Queue`        | `deque`        | `std::queue`     |
| Map / Dict     | `HashMap`      | `dict`         | `std::map`       |
| Set            | `HashSet`      | `set`          | `std::set`       |

---

## 📎 Notes

- `Vector` in Java is synchronized; prefer `ArrayList` for non-threaded use.
- `Deque` (Double-ended Queue) is a flexible alternative to both stacks and queues.
- Tree and Graph structures are more abstract — typically built using classes and pointers/references.
- Use `HashMap` or `dict` when fast lookups are needed via keys.

---

## 📌 Want to Learn More?

You can expand this guide by adding:
- Code examples per language
- Time and space complexity charts
- Real-world use cases

