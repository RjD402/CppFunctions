### Combinations
Function to get all combinations 
Get all the combinations of size k from elements (1,n)
list(combinations(range(1, n+1), k))
```
from itertools import combinations

temp = list(combinations(range(1,5),2))
print(temp)

OUTPUT
[(1, 2), (1, 3), (1, 4), (2, 3), (2, 4), (3, 4)]
```
