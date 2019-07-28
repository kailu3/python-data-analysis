# Tuples, Lists, and Dictionaries

As an interactive way to learn about these collection data types, first consider these three problems:

1. Let's say we also wanted to store a long list of information in a variable that changes over time? For instance, the names of all your cats. You might get new kittens and some cats unfortunately might die. You will need to make updates to your list each time something happens.

2. Let's say we wanted to store a long list of information in a variable that doesn't change over time? For example, the names of the days of the week don't change at all.

3. Let's say we wanted to create a phonebook with every CIS105 student's name and phone number. You would need a list of names and a list of phone numbers and some way to find the student's phone number when only given his or her name.

## The Solution - Tuples, Lists, and Dictionaries

For each of these three problems, there are in-built data types in Python to solve them.

### Lists

Using Lists would solve the first problem. A List is essentially a list of values and are mutable, which means that they can be modified. Lists can also contain different datatypes.

```python
some_cat_list = ['haku', 'nagi', 'poki', 20]

```
Now suppose we were looking through our `some_cat_list` and we realized we wanted to remove `20` as it might've been a happy little accident. To do that, we simply can type

```python
some_cat_list.remove(20)
```
Suppose we didn't know the item we wanted to remove but knew the index. If we wanted to remove an item in `20`'s location, we can type

```python
del some_cat_list[3]
```

