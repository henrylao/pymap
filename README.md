# HashTables

Glorified fancy data indexing! A short series of exercises/programming motivated by learnings in the deep learning and neural network space as a form of self-review

> "...a data structure that implements a set abstract data type, a structure that can map keys to values. A hash table uses a hash function to compute an index, also called a hash code, into an array of buckets or slots, from which the desired value can be found." - *Wikipedia*

# Core Ideas
- load factor $\text{load factor}(\alpha)=\frac{n}{k}$ st 
	- $n$ number of entries in the table
	- $k$ number of buckets
- collision-resolution
- lookup-table $\text{Set } S$ of $n$-elements defines an __associative array__ $A$ of length $m$ st $m \geq n$
- integer universe assumption


# References
- https://brilliant.org/wiki/hash-tables/#:~:text=The%20hash%20table%20is%20the,and%20other%20time%2Dcritical%20operations.
- https://everythingcomputerscience.com/discrete_mathematics/Data_Structures/Hash_Table.html
- https://algs4.cs.princeton.edu/34hash/
