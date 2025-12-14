1. We drop the constants in big O notation
2. We also drop non dominant notations
    Eg: O(n2 + n) => O(n2)

3. O(1) is a constant time

4. Eg of O(log n): dividing an array into halves till we reach the last number. [divide and conquer]
5. Its graph is pretty flat (not as flat as O(1)).

6. O(n log n): has a graph less steap than O(n2).

7. If a function has 2 parameters then its O notation can only be simplified to 2 varaibles and so on.

8.  nested loops => multplication of time constraint
    side by side loops => addition of time constraint

9. LISTS:
    .append() .pop() : O(1)
    .insert(a, b) .pop(a): O(n)

    because changing something in the middle of a list means reindexing.