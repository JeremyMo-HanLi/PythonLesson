# Exercise:

Given a string, display only those characters which are present at an even index number.
For example str = "pynative" so you should display ‘p’, ‘n’, ‘t’, ‘v’.

### Expected Output:
```
Orginal String is  pynative
Printing only even index chars
p
n
t
v
```
# Helen Solution
```
a=input("Input a word:")
for i in range(len(a)):
    if i % 2 ==0:
        print(a[i])
```