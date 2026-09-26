# Conclusion

The given song IDs were stored in a hash table using the Division Method.

The hash function used was:

h(k) = k mod 11

Linear Probing was selected as the collision-resolution technique.

The eight song IDs were successfully inserted into the hash table. For the given dataset, all the song IDs produced different hash indices, so no collisions occurred.

The load factor was calculated as:

α = 8/11 = 0.727 ≈ 72.7%

The search operation was also compared with Linear Search. Hashing required fewer operations for the selected searches because the hash function directly gives the location of the key. Linear Search checks the elements sequentially.

The average-case time complexity of hashing is O(1), while Linear Search has an average-case time complexity of O(n).

Therefore, hashing provides efficient searching for applications such as a music application where song IDs need to be searched frequently. The performance of hashing depends on choosing a suitable hash function, table size, and collision-resolution technique.
