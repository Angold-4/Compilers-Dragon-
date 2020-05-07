# Types of language

### Declarative VS Imperative
**Declarative programming is when you say what you want<br>Imperative language is when you say how to get what you want.**

for example:
```python
# Declarative
small_nums = [x for x in range(20) if x < 5]

# Imperative
small_nums = []
for i in range(20):
    if i < 5:
        small_nums.append(i)
```

In many cases, like in Python. Code will be a mixture of both designs, too, so it's not always black-and-white.

**reference: [Stackoverflow](https://stackoverflow.com/questions/1784664/what-is-the-difference-between-declarative-and-imperative-programming)**
### Scripting Language
**Similar to the script used in acting**<br>Script is actually a series of instructions-the actor sees the instructions and knows what to do and what lines to say<br>The computer sees the instructions and knows what to do. So script is actually a short program used to let the computer automate a series of tasks<br> This type of program does not require compilation, and is usually interpreted and executed.

To give us a better understanding of **Script language**. We need to understand the difference between **Complier** and **Interpreter**:
#### Complier:
* To Compile a language into another
##### Dynamic Complier:
Don't know the type of each variable when compiling. For example:
```python
>>> a = 1
>>> type(a)
<type 'int'>
>>> a = "s"
>>> type(a)
<type 'str'>
```
##### Static Complier:
We Know the type of each variable when compiling<br>
**There is a very special perspective of the diff between Static and Dynamic Compiler:<br>**
For the perspective of Complier, To see whether a language is Static or Dynamic.<br>We often check that when compling, What the complier can do:<br>
* **If the strategy used by a language can solve a problem at compile time. Then we call it Static Language(static policy)**
* **If the strategy used by a language just can make decision at run time. Then we call it Dynamic Language(dynamic policy)**




#### Virtual Machine:
* To Execute a Low-level language as an independent machine

#### Interpreter:
* Generally: **Interpreter** == **Virtual Matchine** + **Dynamic Complier** 

**referecnce: [Zhihu](https://www.zhihu.com/question/30072490/answer/992222309)**

