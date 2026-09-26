# Trace Table – Hashing

## Hash Function

h(k) = k mod 11

## Insertion Trace

| Step | Song ID | Calculation | Hash Index | Collision |
|------|---------|-------------|------------|-----------|
| 1 | 105 | 105 mod 11 | 6 | No |
| 2 | 210 | 210 mod 11 | 1 | No |
| 3 | 315 | 315 mod 11 | 7 | No |
| 4 | 420 | 420 mod 11 | 2 | No |
| 5 | 525 | 525 mod 11 | 8 | No |
| 6 | 630 | 630 mod 11 | 3 | No |
| 7 | 735 | 735 mod 11 | 9 | No |
| 8 | 840 | 840 mod 11 | 4 | No |

## Final Hash Table

| Index | Value |
|------:|-------|
| 0 | EMPTY |
| 1 | 210 |
| 2 | 420 |
| 3 | 630 |
| 4 | 840 |
| 5 | EMPTY |
| 6 | 105 |
| 7 | 315 |
| 8 | 525 |
| 9 | 735 |
| 10 | EMPTY |

## Collision Result

Number of collisions = 0
