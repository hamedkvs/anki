# 1. LIFO and FIFO datas tructures?
LIFO: Stacks & FIFO: Queues

# 2. Queue examples in real life
line of people(join from the back, leave from the front), shared resource between consumers

# 3. Queue operations and their runtime
 enqueue, dequeue, peek, isEmpty, isFull, all run in constant time or O(1)

# 4. LinkedList alternative data-structure in Java
ArrayDeque 

# 5. Queue methods to retrive and remove the head element
poll(): Retrieves and removes the head of this queue, or returns null if this queue is empty. remove(): Retrieves and removes the head of this queue. This method differs from poll only in that it throws an exception if this queue is empty.

# 6. Queue methods to insert the specified elements. their differences
add() and offer(). When using a capacity-restricted queue, offer(E) is generally preferable to add(E), which can fail to insert an element only by throwing an exception.

# 7. Queue methodes that retrieve but do not remove?their differences?
1 E peek() Retrieves, but does not remove, the head of this queue, or returns null if this queue is empty. 2. E element(): Retrieves, but does not remove, the head of this queue. This method differs from peek only in that it throws an exception if this queue is empty.

# 8. what is an interface like
Implementing an interface allows a class to become more formal about the behavior it promises to provide. Interfaces form a contract between the class and the outside world, and this contract is enforced at build time by the compiler. The Java TM Tutorial

# 9. best data structure when you need something in reverse order
Stack

# 10. What are priority queues
a priority queue is an abstract data-type similar to a regular queue or stack data structure in which each element additionally has a "priority" associated with it. In a priority queue, an element with high priority is served before an element with low priority. Wikipedia

# 11. run-time complexity of adding an item in priority queues
O(n)
