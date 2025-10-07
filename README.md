# Experiment 18 – Queue in C++

**Student:** Rajendra Chaganti  
**PRN:** 24070123150  
**Batch:** B3  

---

## Aim  
To implement **Queue operations using Arrays in C++**.  

---

## Theory  

- A **Queue** is a linear data structure that follows the **FIFO (First In, First Out)** principle.  
- The element inserted first is deleted first.  
- Basic operations in a queue:  
  - **Enqueue** → Insert an element at the rear.  
  - **Dequeue** → Remove an element from the front.  
  - **Display** → Show all elements in the queue.  
- Queue can be implemented using arrays or linked lists.  
- Queue status conditions:  
  - **Overflow** → When queue is full.  
  - **Underflow** → When queue is empty.  

---

## Algorithm  

1. Start the program.  
2. Define a `Queue` class with:  
   - An array `arr[SIZE]`.  
   - Two integers `front` and `back`.  
3. Initialize `front = -1`, `back = -1` in the constructor.  
4. For **Enqueue** operation:  
   - If `back == SIZE-1`, print **Queue Overflow**.  
   - If `front == -1`, set `front = 0`.  
   - Increment `back` and insert value into `arr[back]`.  
5. For **Dequeue** operation:  
   - If `front == -1` or `front > back`, print **Queue Underflow/Empty Queue**.  
   - Otherwise, print and remove `arr[front]`, then increment `front`.  
6. For **Display** operation:  
   - If `front == -1` or `front > back`, print **Queue is empty**.  
   - Otherwise, traverse from `front` to `back` and print all elements.  
7. In `main()`, demonstrate enqueue, dequeue, and display operations.  
8. End the program.  

---

## Conclusion  

- Successfully implemented **Queue operations using Arrays in C++**.  
- Understood that:  
  - **Enqueue** adds an element at the rear.  
  - **Dequeue** removes an element from the front.  
  - **Display** prints all elements present in the queue.  
- Also learned to handle **Overflow** and **Underflow** conditions.  
- These operations form the basis for more advanced queue structures like **Circular Queue, Double-Ended Queue (Deque), and Priority Queue**.  
