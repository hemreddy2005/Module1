
# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
Add Code here
```python
expressions = {
    "True + True": True + True,
    "True * False": True * False,
    "False - True": False - True,
    "(True + False) * 5": (True + False) * 5,
    "True == 1": True == 1,
    "False == 0": False == 0,
    "True and False": True and False,
    "True or False": True or False,
    "not True": not True,
    "not False": not False,
    "True + True * False": True + True * False
}

print("Evaluating Boolean and Arithmetic Expressions:\n")
for expr, result in expressions.items():
    print(f"{expr} => {result}")

```
## Output

![image](https://github.com/user-attachments/assets/4acef516-bb61-4cb9-9f8a-3987c420c654)

## Result
Hence the program is executed successfully.
