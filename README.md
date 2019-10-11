# Functions and Stats - Quiz

We recommend you **do not** use Python to answer these questions. Instead, based on what you have learned in this section, _reason_ the code to choose an expected answer. 

??? 


# Functions, methods, central tendency, and dispersion

? Question 1  


Based on the following commands, what are `len` and `count`?

```python
x = [1, 2, 3, 4, 2, 1, 3] 

len(x)
7

x.count(3)
2
```

( ) Keywords    
( ) `len` is a method but `count` is a function   
( ) Both are methods   
( ) Both are functions   
(X) `len` is a function but `count` is a method    


?: Question 2  


What is the output of this code? 

```python

sport = 'football'

def greeting():
    sport =  'badminton'
    return 'Hello neighbor! Do you want to play {}?'.format(sport)

print('Hello neighbor! Do you want to play {}?'.format(sport))
```


( ) 'Hello neighbor! Do you want to play badminton?' 
( ) An error
( ) 'Hello neighbor! Do you want to play {}?'.format(sport) 
(X) 'Hello neighbor! Do you want to play football?'


?: Question 3  


The function `greater_number()` takes two arguments, `x` and `y`, and returns the greater between the two numbers. Fill in the blank to complete the function header. 


```python
# Complete the function header
___ 
    if x >= y: 
        return x
    else: 
        return y

greater_number(7, 4)
7
```

( ) `function greater_number():` 
( ) `def greater_number(x, y)`
(X) `def greater_number(x, y):`
( ) `def x, y:`



?: Question 4  


What is the output of this code? 

```python

hours_open_remaining = 5
pancakes = 0
while hours_open_remaining > 0: 
    pancakes += 1
    hours_open_remaining -= 1
print('{} pancakes eaten!'.format(pancakes))

```

( ) '6 pancakes eaten!'
( ) An error
(X) '5 pancakes eaten!'
( ) This is an infinite loop
( ) '4 pancakes eaten!'


?: Question 5  


Out of the mean, median, and mode, which is most sensitive to outliers in the data?

( ) Mode 
( ) Median
(X) Mean


?: Question 6  


The summary statistics for two samples of data are: 

|   |Mean   |Variance   |
|---|---|---|
|Sample 1|10   |5   |
|Sample 2|10   |10   |


Which sample has the larger spread of observations?

( ) Sample 1
(X) Sample 2
( ) The spread is equal for both the datasets


???
