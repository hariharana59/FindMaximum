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

Program to mark the maximum of marks using the list method sort
Developed by: Hariharan A
RegisterNumber: 23012392

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```


ii)	# To find the maximum marks using the list method max().

```
Program to find the maximum marks using the list method max().
Developed by: Hariharan A
RegisterNumber: 23012392

def max_marks(marks):
    maximum= max(marks)
    return maximum
```

iii) # To find the maximum marks without using builtin functions.

```
Program to the maximum marks without using builtin functions.
Developed by: Hariharan A
RegisterNumber: 23012392

def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```

## Output:
i) # To find the maximum of marks using the list method sort.
![output](https://github.com/hariharana59/FindMaximum/assets/144980130/163c43bd-5b4e-4183-ab26-7274e676dd51)


ii) # To find the maximum marks using the list method max().
![output](https://github.com/hariharana59/FindMaximum/assets/144980130/0914770d-6263-4101-b65c-a88f5a75fb79)


iii) # To find the maximum marks without using builtin functions.
![output](https://github.com/hariharana59/FindMaximum/assets/144980130/00a71961-7ac1-49cc-ae15-11b1b05a6512)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
