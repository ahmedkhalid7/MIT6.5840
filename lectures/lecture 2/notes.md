# lecture 2 notes

a map is a pointer to some data in heap, meaning that passing a map by value will work as passing it by reference in languages like C++. This is why we pass the map `fetched map[string]bool` to the `Serial` function. While passing `fs *fetchState` to the `ConcurrentMutex` function.

---
Go keeps the variables used in a closure or an inner function in the heap instead of stack so that when the outer function returns, that closure or inner function can reference the required data. After that, the garbage collector will handle clearing unused data stored on the heap when that closure or inner function ends.

---
  
