# why do we use big O notation?
we use it to be able to compare the performance of different algorithms. This way we can see how the growth of input values affect the algorithm's efficiency. 

# what does having a complexity of O(1) mean?
it means as the size of input data increases in any ways the performance, aka speed, remains constant.

# give an example of O(1)
for example accessing a specific element of an array is of constant time whether the size is 5 or 5000000 since we have instance access to a requested element

# what does O(n) mean?
an algorith (or a piece of code) having O(n) means the performance is inversely and linearly proportional to the size of input. If we double the size of input the performance drops to half (or the execution time doubles as well)

# an example of O(n)?
linear search: going through all arrays element in order to find a special value; as we iterate through all elements if we the array size increases by ten times, the time it takes to go through all elements goes up by a factor of ten too.

# if an algorithm has three parts like this: 
part_one (O()_1)
part_two(O()_2)
part_three(O()_3)
how we find out the algorithm overall time complexty?
as we ignore lower degree time complexities we only consider the biggest one: if time is O(n^2+n^3+5n) we would say the time complexity is O(n^3)

# if we have three nested 'for's, with an O(1) operation inside the third for, what would be the time complexity?
O(n^3)

# comparison: O(2^n), O(1), O(log n), O(n^m), O(n)
O(1) < O(log n) < O(n) < O(n^m) < O(2^n)

