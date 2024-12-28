# STL- A Toy C++ STL

This project is a custom implementation of a subset of the C++ Standard Template Library (STL). It includes the following data structures:

1. **Vector**
2. **Stack**
3. **Queue**
4. **Dequeue**

The implementation focuses on basic functionalities and is designed for educational purposes.

---

## Data Structures and Usable Methods

### 1. Vector
A dynamically resizable array.

#### Methods:
- **`Vector()`**: Default constructor.
- **`Vector(size_t Capacity)`**: Constructor to initialize with a given capacity.
- **`Vector(const Vector& v)`**: Copy constructor.
- **`VectorType& back() const`**: Returns a reference to the last element.
- **`void push_back(const VectorType& x)`**: Adds an element to the end.
- **`void pop_back()`**: Removes the last element.
- **`VectorType& operator[](int index) const`**: Access element by index (with bounds checking).
- **`size_t size() const`**: Returns the number of elements.
- **`size_t capacity() const`**: Returns the current capacity.
- **`bool empty() const`**: Checks if the vector is empty.
- **`Vector& operator=(const Vector& v)`**: Assignment operator.
- **`void clear()`**: Clears all elements.

### 2. Stack
A Last-In-First-Out (LIFO) data structure.

#### Methods:
- **`Stack()`**: Default constructor.
- **`Stack(size_t Capacity)`**: Constructor to initialize with a given capacity.
- **`Stack(const Stack& s)`**: Copy constructor.
- **`Stack& operator=(const Stack& s)`**: Assignment operator.
- **`StackType& top() const`**: Returns a reference to the top element.
- **`void push(const StackType& x)`**: Adds an element to the top.
- **`void pop()`**: Removes the top element.
- **`size_t size() const`**: Returns the number of elements.
- **`size_t capacity() const`**: Returns the current capacity.
- **`bool empty() const`**: Checks if the stack is empty.
- **`void clear()`**: Clears all elements.

### 3. Queue
A First-In-First-Out (FIFO) data structure.

#### Methods:
- **`Queue()`**: Default constructor.
- **`Queue(size_t Capacity)`**: Constructor to initialize with a given capacity.
- **`Queue(const Queue& q)`**: Copy constructor.
- **`Queue& operator=(const Queue& q)`**: Assignment operator.
- **`QueueType& front() const`**: Returns a reference to the front element.
- **`QueueType& rear() const`**: Returns a reference to the rear element.
- **`void push(const QueueType& x)`**: Adds an element to the rear.
- **`void pop()`**: Removes the front element.
- **`size_t size() const`**: Returns the number of elements.
- **`size_t capacity() const`**: Returns the current capacity.
- **`bool empty() const`**: Checks if the queue is empty.
- **`void clear()`**: Clears all elements.

### 4. Dequeue
A Double-Ended Queue allowing insertion and deletion from both ends.

#### Methods:
- **`Dequeue()`**: Default constructor.
- **`Dequeue(size_t Capacity)`**: Constructor to initialize with a given capacity.
- **`Dequeue(const Dequeue& dq)`**: Copy constructor.
- **`DequeueType& operator[](int index) const`**: Access element by index (with bounds checking).
- **`void push_back(const DequeueType& x)`**: Adds an element to the rear.
- **`void pop_back()`**: Removes the last element.
- **`void push_front(const DequeueType& x)`**: Adds an element to the front.
- **`void pop_front()`**: Removes the front element.
- **`DequeueType& front() const`**: Returns a reference to the front element.
- **`DequeueType& rear() const`**: Returns a reference to the rear element.
- **`size_t size() const`**: Returns the number of elements.
- **`size_t capacity() const`**: Returns the current capacity.
- **`bool empty() const`**: Checks if the dequeue is empty.
- **`Dequeue& operator=(const Dequeue& dq)`**: Assignment operator.
- **`void clear()`**: Clears all elements.

---

## Example Usage
Refer to the `test.cpp` file for comprehensive examples demonstrating the usage of each data structure.


