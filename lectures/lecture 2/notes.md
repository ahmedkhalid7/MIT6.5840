# lecture 2 notes

a map is a pointer to some data in heap, meaning that passing a map by value will work as passing it by reference in languages like C++. This is why we pass the map `fetched map[string]bool` to the `Serial` function. While passing `fs *fetchState` to the `ConcurrentMutex` function.

<!-- ---
a map is a pointer to some data in heap, meaning that passing a map by value will work as passing it by reference in languages like C++. This is why we pass the map `fetched map[string]bool` to the `Serial` function. While passing `fs *fetchState` to the `ConcurrentMutex` function.

--- -->
  