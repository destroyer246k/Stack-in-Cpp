# Stack-in-Cpp  

**Aim:** To study the concept of **Stack** in C++ and implement operations like push, pop, and display.  
**Tools:** GNU g++ compiler for local compilation or any online C++ compiler.  

# Theory  
A **Stack** is a linear data structure that follows the **LIFO (Last In, First Out)** principle.  
- The last element inserted is the first one to be removed.  
- It has two main operations:
  1. **Push** – add an element to the top of the stack.  
  2. **Pop** – remove the top element from the stack.  

### Representation  
- Can be implemented using **arrays** or **linked lists**.  
- Requires a pointer/index (`top`) to keep track of the top element.  

# **Program: Stack Implementation Using Array**

### Logic:  
A `Stack` class is created with an array to store elements and an integer `top` to track the top position.`push()` adds a new element at the top of the stack.  
`pop()` removes the top element. `display()` traverses and prints all stack elements.   Overflow and underflow conditions are handled using checks on `top`.  

### Algorithm:  
1. Start  
2. Define a class `Stack` with array and `top` index.  
3. Initialize `top = -1` (empty stack).  
4. **Push Operation**:
   - Check if `top >= MAX-1` → Overflow  
   - Else increment `top` and insert value  
5. **Pop Operation**:
   - Check if `top < 0` → Underflow  
   - Else remove element and decrement `top`  
6. **Display Operation**:
   - Traverse array from `0` to `top` and print elements  
7. In `main()`, perform multiple push and pop operations.  
8. End  



# **Conclusion**  
Stacks are simple and useful for tasks like expression evaluation, function call tracking, and undo operations. Using arrays, we can efficiently implement stack operations while handling overflow and underflow conditions.
