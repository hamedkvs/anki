# 1. the difference between static and dynamic arrays
static arrays need specifying their size before allocation while dynamic arrays can grow or shrink automatically

# 2. What are run-time complexities of static array?
lookup by index: O(1), lookup by value: O(n), insertion: O(n), deletion: O(n)

# 3. Analize the run-time complexity for finding the index of an item in an array?
Best case: O(1), worst case: O(n), so -> the run-time complexity: O(n) (consider the worst case scenario)

# 4. Vector vs ArrayList in Java
 vectors grow 100% while Arraylists grow 50%. Vector mothods are synchronized

# 5. What are the 2 limitations of arrays?
1.the size of the array have to be known at creation time 2.they are slow when we need to add or remove a lot of items from them 

# 6. array access time complexity? why?
O(1), because memory address is calculated based on its index: array[index]: addr(e[0])+typeSize*index

# 7. runtime complexity of array expansion (increasing the array size)?why?
O(n) since all elements will be copied to a new array with a larger size

# 8. Runtime complexity of element deletion?why?
since by eliminating an element we need to shift others accordingly it's O(n) (worst case scenario)

# 9. when does the worst case scenario of array deletion happen?
when the deleted element is the first element (index == 0)

# 10. difference between Vector and ArrayList in terms of resizing when full
Vector increases the size by 100% while for ArrayList it's 50%

# 11. difference between Vector and ArrayList in terms of synchronization?
Vector is synchronized

# 12. what does it mean when we say X is synchronized?
it means only a single thread has access to its methods

