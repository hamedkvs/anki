# 1. what does deterministic means?
In mathematics, computer science and physics, a deterministic system is a system in which no randomness is involved in the development of future states of the system. A deterministic model will thus always produce the same output from a given starting condition or initial state.

# 2. Operations in hashtables and their run time?
Insert O(1), Lookup O(1), Delete O(1)

# 3. What is the benefit of Set data structure
they don't allow duplication

# 4. when collision takes place in a HashMap
 when different keys map to a same index returned by the hash function

# 5. How collosions should be handled in a HashMap
Chaining (by LinkList) or OpenAddressing

# 6. Linear Probing formula for openaddressing in a hashmap
(hash(key)+i) % table_size

# 7. Linear Probing Problem
after a while clusters will be generated, and we have to pass all the items in the cluster to find empty space, as the cluster grows the insertion takes more time

# 8. Quadratic Probing
(hash(key) + i^2) % table_size

# 9. Quadratic Probing problem? Does linear probing has the same drawback?
infinit loop due to the big jumps. In linear probing we do not encounter the same problem because each time we go to the next slot

# 10. Double Hashing formula in conjuction with open open addressing 
index = (hash1(key) + i * hash2(key))% table_size, where hash2(key) = prime - (key % prime), prime should be a prime number smaller than the table_size, 

# 11. In a HashMap if we add elements with same key what will happen to the first one added
will be replaced by the second one

