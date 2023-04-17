# map,lambda,filter (Assignment)
1.Create a python program to sort the given list of tuples based on integer value using a lambda function. [('Sachin Tendulkar', 34357), ('Ricky Ponting', 27483), ('Jack Kallis', 25534), ('Virat Kohli', 24936)]

```python
players = [('Sachin Tendulkar', 34357), ('Ricky Ponting', 27483), ('Jack Kallis', 25534), ('Virat Kohli', 24936)]

sorted_players = sorted(players, key=lambda x: x[1], reverse=True)

print(sorted_players)

```

    [('Sachin Tendulkar', 34357), ('Ricky Ponting', 27483), ('Jack Kallis', 25534), ('Virat Kohli', 24936)]
    
Q.2> Write a Python Program to find the squares of all the numbers in the given list of integers using lambda and map functions. [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

```python
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

squared_numbers = list(map(lambda x: x**2, numbers))

print(squared_numbers)
```

    [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
    
Q.3> Write a python program to convert the given list of integers into a tuple of strings. Use map and lambda functions Given String: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] Expected output: ('1', '2', '3', '4', '5', '6', '7', '8', '9', '10')

```python
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

string_numbers = tuple(map(lambda x: str(x), numbers))

print(string_numbers)

```

    ('1', '2', '3', '4', '5', '6', '7', '8', '9', '10')
    
Q.4> Write a python program using reduce function to compute the product of a list containing numbers from 1 to 25

```python
from functools import reduce

numbers = range(1, 26)

product = reduce(lambda x, y: x * y, numbers)

print(product)
```

    15511210043330985984000000
    
Q.5> Write a python program to filter the numbers in a given list that are divisible by 2 and 3 using the filter function. [2, 3, 6, 9, 27, 60, 90, 120, 55, 46]

```python
numbers = [2, 3, 6, 9, 27, 60, 90, 120, 55, 46]

filtered_numbers = list(filter(lambda x: x % 2 == 0 and x % 3 == 0, numbers))

print(filtered_numbers)

```

    [6, 60, 90, 120]
    
8.Write a python program to find palindrome in given list of strings using lambda and filter function

```python
strings = ['python', 'php', 'aba', 'radar', 'level']

palindromes = list(filter(lambda s: s == s[::-1], strings))

print(palindromes)

```

    ['php', 'aba', 'radar', 'level']
    


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```
