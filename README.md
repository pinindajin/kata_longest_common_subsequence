
## PROBLEM:

Write a function that can determine the longest common subsequence (LCS) among
two unique sequences. A subsequence is a sequence that can be derived 
from another sequence by deleting some or no elements without changing 
the order of the remaining elements.
 

## EXAMPLE CASES

```
['Dog', 'Yam', 'Dog', 'Tattoo', 'Ginger', 'Shoe']
['Yam', 'Dog', 'Shoe', 'Yam', 'Dog', 'Ginger']
=> 
['Dog', 'Yam', 'Dog', 'Ginger']
```

```
['Dog', 'Ludacious', 'Ludacious', 'Anakin', 'Dog', 'Yam']
['Ludacious', 'Spyro', 'Anakin', 'Spyro', 'Dog', 'Plum', 'Yam'] 
=>
['Ludacious', 'Anakin', 'Dog', 'Yam']
```

```
['Dog', 'Dog', 'Dog', 'Dog']
['Dog', 'Dog']
=>
['Dog', 'Dog']
```

```
If there is a unique sequence with no elements, the LCS is nothing. 
['Tea', 'Tea', 'Tea']
[]
=> 
[]
```

```
['Dog', 'Yam', 'Yam', 'Dog']
['Dog', 'Yam', 'Trout', 'Dog', 'Yam', 'Dog'] 
=> 
['Dog', 'Yam', 'Yam', 'Dog']
```

```
If there is a tie for the LCS, return the LCS whose first element
is the closest to the beggining of the first unique sequence.
['Ginger', 'Dog', 'Spyro', 'Yam', 'Tea']
['Dog', 'Yam', 'Ginger', 'Spyro', 'Tea']
=>
['Ginger', 'Spyro', 'Tea']
```
