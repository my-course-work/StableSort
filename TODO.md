TODO List: Acceptance tests
===
Common test cases
---
 - [x] Sort empty array -> empty array

Integer test cases
---
 - [x] Sort [1] -> [1]
 - [x] Sort [1, 2] -> [1, 2]
 - [x] Sort [2, 1] -> [1, 2]
 - [x] Sort [3, 2, 1] -> [1, 2, 3]
 - [x] Sort [4, 1, 4] -> [1, 4, 4], stable
 - [x] Sort [2, 2, 2] -> [2, 2, 2], stable
 - [x] Sort [6, 6, 5] -> [5, 6, 6], stable
 - [x] Sort [8, 2, 2] -> [2, 2, 8], stable
 - [x] Sort [7, 5, 4, 5] -> [4, 5, 5, 7], stable
 - [x] Sort [5, 3, 5, 4, 3] -> [3, 3, 4, 5, 5], stable

Char test cases
---
 - [x] Sort ['a'] -> ['a']
 - [x] Sort ['a', 'b'] -> ['a', 'b']
 - [x] Sort ['e', 'f', 'h', 'f'] -> ['e', 'f', 'f', 'h'], stable