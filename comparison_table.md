# Comparison: Hashing vs Linear Search

| Feature | Hashing | Linear Search |
|---|---|---|
| Data structure | Hash Table | Array/List |
| Average search | O(1) | O(n) |
| Worst-case search | O(n) | O(n) |
| Insertion | O(1) average | O(1) at end / depends on representation |
| Extra space | O(m) | O(1) additional |
| Search 105 | 1 operation | 1 comparison |
| Search 525 | 1 operation | 5 comparisons |
| Search 840 | 1 operation | 8 comparisons |
| Search 999 | 1 operation | 8 comparisons |
| Collision handling | Required when collisions occur | Not required |
| Suitable for frequent ID searching | Yes | Less efficient for large datasets |

## Observation

Hashing directly calculates the position of a key using the hash function.

Linear search checks elements sequentially from the beginning.

For the given dataset, hashing requires fewer operations for the selected searches.
