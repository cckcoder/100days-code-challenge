# 100 Days Code Challenge.

## Day 3

### List

it's collection of items in a particular order.

* include the letters from alphabet
* the digits of numbers from 0-9
* the names of all the people in your family!!

```python
bicycle = ['trek', 'cannodale', 'redline', 'specialized']
print(bicycle)

# output:
['trek', 'cannodale', 'redline', 'specialized']
```

### Accessing elements in a list
can access any element in a list by telling Python the position, or
index, of the item desired

```python
print(bicycle[0])
# output:
trek

print(bicycle[0].title())
# output:
Trek
```

index positions start at 0, not 1

* python has a special syntax for __accessing__ the last element in a list.
By asking for the item at index -1, "Python always returns the last item
in the list" `print(bicycle[-1])`

### Edit value in list

```python
motorcycles = ['honda', 'yamaha', 'suzuki']
print(motorcycles)
# output:
['honda', 'yamaha', 'suzuki']

motorcycles[0] = 'ducati'
print(motorcycles)

# output:
['ducati', 'yamaha', 'suzuki']
```