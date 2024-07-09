# **Data Structure and Algorithms (DSA)**

### **Programming**
- Programming involves creating a set of instructions that tell a computer how to solve a problem.
- It's all about logic, we can tackle the same problem in multiple ways.
- It becomes essential to find the most efficient method among these approaches. 
- A fundamental concept around which we build our programs.
- You will be able to write code that is not only functional but also highly efficient and scalable.
- The principles of DSA apply universally across all programming languages.

### **Data Structure**
A way of storing data in an organized manner to be accessed efficiently.

**1. Fundamental / Built-in Data Structures:**
- Lists, dictionaries, and sets, in Python—they are the built-in data structures of the language.
- Such data structures are called fundamental data structures.
- Each data structure operates uniquely, and our choice among them depends on our specific requirements.
- e.g. It's better to use dictionaries if we need to work with **key-value** pairs, even though we can perform the same task using a list.
  1. **List** (Ordered Collection | Mutable | Heterogeneous Data Type | Dynamic Array) 
  2. **Tuple** (Ordered Collection | Immutable | Heterogeneous Data Type)
  3. **Set** (Unordered Collection | Mutable | Heterogeneous Data Type)
  4. **Dictionary** (Ordered Collection | Mutable | Heterogeneous Data Type)

**2. Custom Data Structures:**
- Built-in data structures are not enough for writing complex programs. Imagine working on a mapping service like Google Maps.
- If we rely solely on built-in data structures to create a mapping service, our program won't be efficient.
- In such cases, we employ logic to develop custom data structures such as graphs, trees, hash maps, etc.

### **Big O Notation**

- Measure how running time or space requirements for the program grow as the input size increases.
- time = a * n + b  (a and b are Constants | n is Iteration)

Rules :
- Keep Fastest Growing Terms
- Drop Constants

Constant: O(1) | Constant Time Operation

Search By Index | Lookup: O(1)

Loops | Iterations: O(n) (Search an Element in a Sorted Array | Array Traversal)

Insert | Delete (Beginning): O(1) (Add New Element and Shift other Elements to New Memory Address)

Insert | Delete (Ending): O(n) (Add New Element and Shift other Elements to New Memory Address)

Insert | Delete (Middle): O(n) (Add New Element and Shift other Elements to New Memory Address)

Linked List Traversal = O(n)

Accessing Element By Value = O(n)

<h5>2 Iterations: O(n<sup>2</sup>)</h5>

Big Iteration: O(log n) (Binary Search | Unordered Array)

Splitting | Dividing | Merge: O(n log n) (Here n is for Merge)



