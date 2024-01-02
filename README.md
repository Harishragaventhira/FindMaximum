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
Program to mark the maximum of marks using the list method sort
Developed by: HARISH
RegisterNumber: 2301571

def max_marks(m):
    #Write your code here
    m.sort()
    l=m[-1]
    return l
```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: harish
RegisterNumber: 23013571

def max_marks(m):
    # write your code here
    l=max(m)
    return l
```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by:harish 
RegisterNumber: 23013571
def max_marks(l):
    # write your code here
    m=l[0]
    for n in l:
        if(n>m):
         m=n
    return m
```
## Output:
![Screenshot 2024-01-02 135622](https://github.com/Harishragaventhira/FindMaximum/assets/145548269/9ef310ab-e1f7-475a-968f-3794f292ef47)
![Screenshot 2024-01-02 135837](https://github.com/Harishragaventhira/FindMaximum/assets/145548269/ce3cc454-05c9-400f-b86a-d72360135b59)
![Screenshot 2024-01-02 135934](https://github.com/Harishragaventhira/FindMaximum/assets/145548269/34d9ac27-3831-4904-980a-eba20bc6ab7e)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
