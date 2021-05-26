# 100 Days Code Challenge.

## Day 1
### Naming and Using Variables
* Variable names can contain only letters, numbers, and underscore
	* `example: message_1 but not 1_message`
* Spaces are not allowed in variable names, but underscores can be used to 
separate words
	* `example: greeting_message it work greeting message will get error`
* Avoid using python keywords and function names as variable name
	* `for example: print`
* Variable names should be short but descriptive.
	* `for example: student_name better than s_n`
	* `name length is better than length_of_persons_name`
* Be careful when using the lowercase and uppercase because
they could be confused.

### Avoid Name Errors when using variable.
```python
message = "Hello Python World!"
print(mesage) #This the thing!!

Then you get an error

Hello Python World!
Traceback (most recent call last):
  File "/mnt/disk_2/tutorial/100days-code-challenge/day1/variable_data_type.py", 
  line 6, in <module>
    print(mesage)
NameError: name 'mesage' is not defined
```
* in this case we found `NameError: name 'mesage' is not defined`
	* python cannot identify the variable provided
	* How to solve that?
		* Just put the right variable `print(message)`

### String
* You can use single or double quotes around your strings like this:

```python
"This is a string."
'This is also a string.'
```

* Example

```python
name = "ada lovelace"
print(name.title())
Output: Ada Lovelace
``` 

### Using Variables in Strings
* Some situations, you'll want to use a variable's value inside a string
	* Example

	```python
	# This is call f-string.
	first_name = "ada"
	last_name = "lovelace"
	full_name = f"{first_name} {last_name}"
	print(full_name)	
	```
	* Note: f-string introduce in Python 3.6.x if you using lower version
	you'll need to use the `format()`

		```python
		full_name = "{} {}".format(first_name, last_name)
		```