# 1. What are binary trees
 Trees that each element can have maximum number of two children

# 2. binary search tree conitions
condition that sould be met by every node: left child value < node value < right child value

# 3. give and example of logarithmic time complexity
 binary search tree. in every step we threw half of our items away

# 4. binary search tree runtimes
Lookup O(Log n), Insertion O(Log n), Deletion O(Log n). I all we have to find the element witch takes O(Log n)

# 5. Tree elements
 nodes(leaf nodes, root node, parent node, child node) and edges

# 6. When you iterate(traverse) through a collection(tree) what variable name suits you for the item in each iteration
current

# 7. what is breath first traversal? give an alternative name for this traversal.
level order traversal - It starts at the tree root and explores all nodes at the present depth prior to moving on to the nodes at the next depth level. Wikipedia

# 8. Depth first types and their node traverse order
 Pre-order <ROOT>, LEFT, RIGHT / In-order LEFT, <ROOT>, RIGHT / Post-order LEFT, RIGHT, <ROOT>

# 9. Witch traversal is better when we want to traverse from its leaves up to the root?
Post-order traversal

# 10. what data structure Java use for implementing recursion?
Stack

# 11. base condition for implementing a factorial by recursion?
if(n==0) return 1

# 12. recursive function 2 main parts
A recursive function definition has one or more base cases, meaning input(s) for which the function produces a result trivially (without recurring), and one or more recursive cases, meaning input(s) for which the program recurs (calls itself). Wikipedia

# 13. what is the height of a tree
height of its root node

# 14. what is the height of a node
The height of a node is the length of the longest downward path to a leaf from that node. Wikipedia

# 15. what is the depth of a node
The depth of a node is the length of the path to its root (i.e., its root path). Wikipedia

