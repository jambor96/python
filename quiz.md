### What will be the output of the following Python code?
```
l=[1, 0, 2, 0, 'hello', '', []]
list(filter(bool, l))
```
- [ ] [1, 0, 2, ‘hello’, ”, []]
- [ ] Error1
- [ ] [1, 2, ‘hello’]
- [ ] [1, 0, 2, 0, ‘hello’, ”, []]
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    [1, 2, ‘hello’]
  </div>
</details>


### Which function is called when the following Python program is executed?
```
f = foo()
format(f)
```
- [ ]  str()
- [ ]  format()
- [ ]  \__str__()
- [ ]  \__format__()
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ]  __str__()
  </div>
</details>

### What will be the output of the following Python program?
```
def foo(x):
    x[0] = ['def']
    x[1] = ['abc']
    return id(x)
q = ['abc', 'def']
print(id(q) == foo(q))
```
- [ ]  Error
- [ ]  None
- [ ]  False
- [ ]  True
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ]  True
  </div>
</details>

### What will be the output of the following Python program?
```
z=set('abc')
z.add('san')
z.update(set(['p', 'q']))
z
```
- [ ] {‘a’, ‘c’, ‘c’, ‘p’, ‘q’, ‘s’, ‘a’, ‘n’}
- [ ] {‘abc’, ‘p’, ‘q’, ‘san’}
- [ ] {‘a’, ‘b’, ‘c’, ‘p’, ‘q’, ‘san’}
- [ ] {‘a’, ‘b’, ‘c’, [‘p’, ‘q’], ‘san}
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ] {‘a’, ‘b’, ‘c’, ‘p’, ‘q’, ‘san’}
  </div>
</details>

### What will be the output of the following Python code?
```
print("abc. DEF".capitalize())
```
- [ ] Abc. def
- [ ] abc. def
- [ ] Abc. Def
- [ ] ABC. DEF
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ] Abc. def
  </div>
</details>

### What will be the output of the following Python code?
```
def foo():
    try:
        return 1
    finally:
        return 2
k = foo()
print(k)
```
- [ ] 1
- [ ] 2
- [ ] 3
- [ ] error, there is more than one return statement in a single try-finally block
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ] 2
  </div>
</details>

### Which of the following best describes inheritance?
- [ ] Ability of a class to derive members of another class as a part of its own definition
- [ ] Means of bundling instance variables and methods in order to restrict access to certain class members
- [ ] Focuses on variables and passing of variables to functions
- [ ] Allows for implementation of elegant software that is well designed and easily modified
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ] Ability of a class to derive members of another class as a part of its own definition
  </div>
</details>

### Suppose B is a subclass of A, to invoke the __init__ method in A from B, what is the line of code you should write?
- [ ] A.__init__(self)
- [ ] B.__init__(self)
- [ ] A.__init__(B)
- [ ] B.__init__(A)
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ] A.__init__(self)
  </div>
</details>

### What will be the output of the following Python code?
```
class A:
    def __init__(self, x= 1):
        self.x = x
class der(A):
    def __init__(self,y = 2):
        super().__init__()
        self.y = y
def main():
    obj = der()
    print(obj.x, obj.y)
main()
```
- [ ] Error, the syntax of the invoking method is wrong
- [ ] The program runs fine but nothing is printed
- [ ] 1 0
- [ ] 1 2
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ] 1 2
  </div>
</details>

### What does built-in function type do in context of classes?
- [ ] Determines the object name of any value
- [ ] Determines the class name of any value
- [ ] Determines class description of any value
- [ ] Determines the file name of any value
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ] Determines the class name of any value
  </div>
</details>

### What is the biggest reason for the use of polymorphism?
- [ ] It allows the programmer to think at a more abstract level
- [ ] There is less program code to write
- [ ] The program will have a more elegant design and will be easier to maintain and update
- [ ] Program code takes up less space
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ] The program will have a more elegant design and will be easier to maintain and update
  </div>
</details>

### A class in which one or more methods are only implemented to raise an exception is called an abstract class.
- [ ] True
- [ ] False
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ] True
  </div>
</details>

### Which of the following is the most suitable definition for encapsulation?
- [ ] Ability of a class to derive members of another class as a part of its own definition
- [ ] Means of bundling instance variables and methods in order to restrict access to certain class members
- [ ] Focuses on variables and passing of variables to functions
- [ ] Allows for implementation of elegant software that is well designed and easily modified
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ] Means of bundling instance variables and methods in order to restrict access to certain class members
  </div>
</details>

### What will be the output of the following Python code?
```
sentence = 'we are humans'
matched = re.match(r'(.*) (.*?) (.*)', sentence)
print(matched.groups())
```
- [ ] (‘we’, ‘are’, ‘humans’)
- [ ] (we, are, humans)
- [ ] (‘we’, ‘humans’)
- [ ] ‘we are humans’
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ] (‘we’, ‘are’, ‘humans’)
  </div>
</details>

### What will be the output shape of the following Python code?
```
import turtle
t=turtle.Pen()
for i in range(0,4):
	t.forward(100)
	t.left(120)
```
- [ ] square
- [ ] rectangle
- [ ] triangle
- [ ] kite
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ] triangle
  </div>
</details>

### What does os.close(f) do?
- [ ] terminate the process f
- [ ] terminate the process f if f is not responding
- [ ] close the file descriptor f
- [ ] return an integer telling how close the file pointer is to the end of file
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ] close the file descriptor f
  </div>
</details>

### Which of the following is equivalent to random.randint(3, 6)?
- [ ] random.choice([3, 6])
- [ ] random.randrange(3, 6)
- [ ] 3 + random.randrange(3)
- [ ] 3 + random.randrange(4)
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ]  3 + random.randrange(4)
  </div>
</details>

### What will be the output of the following Python code?
```
x = [[0], [1]]
print((' '.join(list(map(str, x))),))
```
- [ ] (‘[0] [1]’,)
- [ ] (’01’)
- [ ] [0] [1]
- [ ] 01
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ]  (‘[0] [1]’,)
  </div>
</details>

### What will be the output of the following Python code?
```
elements = [0, 1, 2]
def incr(x):
    return x+1
print(list(map(elements, incr)))
```
- [ ] [1, 2, 3]
- [ ] [0, 1, 2]
- [ ] error
- [ ] none of the mentioned
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ]  error
  </div>
</details>

### Which module in the python standard library parses options received from the command line?
- [ ] getopt
- [ ] os
- [ ] getarg
- [ ] main
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ]  getopt
  </div>
</details>

### Which of the following statements are true?
- [ ] When you open a file for reading, if the file does not exist, an error occurs
- [ ] When you open a file for writing, if the file does not exist, a new file is created
- [ ] When you open a file for writing, if the file exists, the existing file is overwritten with the new file
- [ ] All of the mentioned
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ]  All of the mentioned
  </div>
</details>

### What will be the output of the following Python code?

l1=[1, 2, 3, [4]]
l2=list(l1)
id(l1)==id(l2)
- [ ] True
- [ ] False
- [ ] Error
- [ ] Address of l1
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ]  False
  </div>
</details>

###  What will be the output of the following Python code snippet?
```
z=set('abc')
z.add('san')
z.update(set(['p', 'q']))
z
```
- [ ] {‘abc’, ‘p’, ‘q’, ‘san’}
- [ ] {‘a’, ‘b’, ‘c’, [‘p’, ‘q’], ‘san}
- [ ] {‘a’, ‘c’, ‘c’, ‘p’, ‘q’, ‘s’, ‘a’, ‘n’}
- [ ] {‘a’, ‘b’, ‘c’, ‘p’, ‘q’, ‘san’}
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ]  {‘a’, ‘b’, ‘c’, ‘p’, ‘q’, ‘san’}
  </div>
</details>

### What is the difference between threading.Lock and threading.RLock?
- [ ]  Lock is owned by a thread while RLock is owned by many.
- [ ]  Lock is owned by none while RLock is owned by many.
- [ ]  Lock and RLock both primitives are owned by a single thread.
- [ ]  Lock and RLock both primitives are owned by many.
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ]  Lock is owned by none while RLock is owned by many.
  </div>
</details>

### What is the difference between a semaphore and bounded semaphore?

- [ ]  Semaphore holds a counter for the number of release() calls minus the number of acquire() calls, plus an initial value but bounded semaphore doesn't.
- [ ]  Bounded semaphore holds a counter for the number of release() calls minus the number of acquire() calls, plus an initial value but semaphore doesn't.
- [ ]  A bounded semaphore makes sure its current value doesn’t exceed its initial value while semaphore doesn't.
- [ ]  A semaphore makes sure its current value doesn’t exceed its initial value while bounded semaphore doesn't.
<details class="printElement">
  <summary>Click to View Answer</summary>
  <div style="background-color: #007BFF; color: white; padding: 10px; border-radius: 5px; text-align: center;">
    - [ ]   A bounded semaphore makes sure its current value doesn’t exceed its initial value while semaphore doesn't.
  </div>
</details>

## Algorithm 
1. Write a Python function to find the largest element in an array or list.

2. Given an array of integers, find two numbers such that they add up to a specific target sum.


3. Given a string s containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.
An input string is valid if:
    - Open brackets must be closed by the same type of brackets.
    - Open brackets must be closed in the correct order.
    - Every close bracket has a corresponding open bracket of the same type.
    >
    Example 1:
    Input: s = "()"
    Output: true
    Example 2:
    Input: s = "()[]{}"
    Output: true
    Example 3:
    Input: s = "(]"
    Output: false

4.  finding the minimum value in a sliding window of a fixed size in an array





