# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Bharath.N
RegisterNumber: 23003413
'''
def max_marks(marks):
    marks.sort()
    highest =marks[-1]
    return highest


```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: Bharath.N
RegisterNumber: 23003413
'''
def max_marks(marks):
    return (max(marks))


```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Bharath.N
RegisterNumber: 23003413
'''
def max_marks(list1):
    highest=0
    for mark in list1:
        if mark > highest:
            highest = mark
    return highest

```
## Sample Input and Output
![max_marks1](https://github.com/BHARATHNATRAJAN/FindMaximum/assets/147473529/6edeb4f4-022f-41d5-bdf2-41536a532077)
 
![max_marks2](https://github.com/BHARATHNATRAJAN/FindMaximum/assets/147473529/9ccb6697-7852-4ee3-b518-5396a7ec7646)


## Output:
![max-mark-output1](https://github.com/BHARATHNATRAJAN/FindMaximum/assets/147473529/ec2c7e0d-2fd6-4a79-b7f3-819ef5097323)

![max-mark-output2](https://github.com/BHARATHNATRAJAN/FindMaximum/assets/147473529/cc1dabd0-6b24-47b7-b6aa-fc41ad031e14)

![max-mark-output3](https://github.com/BHARATHNATRAJAN/FindMaximum/assets/147473529/16e37c2f-33b1-46cb-a345-82a9317f7897)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
