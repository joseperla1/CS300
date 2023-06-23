#RUN TIME ANALYSIS:
DATA STRUCTURE	BIG O ANALYSIS
VECTOR	3N+10
HASHTABLE	4N+15
BINARY TREE	4N+2log n+17

#
When comparing the analysis for all the data structures it seems that vectors or binary trees  would be better however understanding the advantages and disadvantages of the different data structures a Hash Table would be the best. While binary trees can operate on log n time if the tree was to be unbalanced, the times can take longer by  a lot and since we are working with course in a department there's a possibility it can be skewed if its ordered by alphanumeric. For example if most courses start with C rather than P and they  are put on opposite sides of the root then it would become heavily skewed to the left side. In order to combat that it would require constant balancing to maintain performance. Vectors on the other hand may easily implement new course elements but when it comes to searching it could take a long time if you’re dealing with a large number of courses and for the sake of a school who might add new courses every school year this could dramatically increase the time it takes for a vector to complete a search. On a normal case Hash Tables have a constant time when searching and in the worst case it can become linear when there's a lot of collisions occurring but if the problem comes from the table size that can always be adjusted based on the number of keys. Also lowering collisions can be done by designing a hash function that distributes those keys evenly.

