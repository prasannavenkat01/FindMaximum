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
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Prasanna v
RegisterNumber: 23006873
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
    

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Prasanna v
RegisterNumber: 23006873
'''
def max_marks(marks):
    max_marks=max(marks)
    return max_marks


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Prasanna v
RegisterNumber: 23006873
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-12-26 123807](https://github.com/prasannavenkat01/FindMaximum/assets/150702500/1530d85b-f8a6-46df-8951-b92fbecf6187)

![Screenshot 2023-12-26 123827](https://github.com/prasannavenkat01/FindMaximum/assets/150702500/41a809da-749b-442e-9a5f-6656679af0f0)

![Screenshot 2023-12-26 123839](https://github.com/prasannavenkat01/FindMaximum/assets/150702500/493b08b5-70fa-4bd7-8627-6b041003ae84)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
