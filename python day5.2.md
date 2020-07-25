```python
list2=[10,20,40,60,70,80]
```


```python
list2.sort(reverse=1)
```


```python
print(list2)
```

    [80, 70, 60, 40, 20, 10]
    


```python
list3=[(10,4),(2,4),(6,7),(2,6)]
```


```python
def fun1(x):
    return x[0]+x[1]
list3.sort(key=fun1)

```


```python
print(list3)
```

    [(2, 4), (2, 6), (6, 7), (10, 4)]
    


```python

```
