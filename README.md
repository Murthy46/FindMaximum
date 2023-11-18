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
Developed by: Sundaramurthy M
RegisterNumber: 23010238
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    max=marks[-1]
    return maxv



```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: Sundaramurthy M
RegisterNumber: 23010238
'''
def max_marks(marks):
    # write your code here
    max_marks=max(marks)
    return max_marks



```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i>max:
            max = i
    return max        



```


## Output:
<img width="1440" alt="Screenshot 2023-11-18 at 9 47 03 AM" src="https://github.com/Murthy46/FindMaximum/assets/145112768/80ed792a-5d03-4a4d-9791-6a8156bad528">

<img width="1440" alt="Screenshot 2023-11-18 at 9 47 11 AM" src="https://github.com/Murthy46/FindMaximum/assets/145112768/46654e3a-1be6-48de-96ab-65cd6ede7c86">


<img width="1440" alt="Screenshot 2023-11-18 at 9 47 17 AM" src="https://github.com/Murthy46/FindMaximum/assets/145112768/896faeb7-c7c7-4bcd-85d4-d99d64d5a279">



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
