# Complexity Analysis

## Hashing

The Division Method uses:

h(k) = k mod m

where k is the key and m is the hash table size.

### Average Case

Search: O(1)

Insertion: O(1)

### Worst Case

Search: O(n)

Insertion: O(n)

The worst case can occur when many collisions are present.

## Linear Search

### Best Case

O(1)

### Average Case

O(n)

### Worst Case

O(n)

## Space Complexity

For a hash table of size m:

Space complexity = O(m)

## Load Factor

Load Factor = Number of elements / Hash table size

α = 8 / 11

α = 0.727

α ≈ 72.7%

Therefore, the hash table is approximately 72.7% occupied.

## Collision Analysis

For the given song IDs and table size 11, all keys produce different hash indices.

Therefore:

Number of collisions = 0

This results in efficient searching for this particular dataset.
