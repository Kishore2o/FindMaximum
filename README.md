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
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
    #Write your code here

ii)	# To find the maximum marks using the list method max().

def max_marks(marks):
    large=max(marks)
    return large


iii) # To find the maximum marks without using builtin functions.

def max_marks(list1):
    maximum=list1[0]
    for i in list1:
        if i>maximum:
            maximum=i
    return maximum



```

## Output:
![image](https://user-images.githubusercontent.com/118679883/214565780-94865bcf-14f9-4b17-b4f7-ff1c975714ed.png)
![image](https://user-images.githubusercontent.com/118679883/214565824-69339720-556b-404d-a0ab-a318e2fcfa27.png)
![image](https://user-images.githubusercontent.com/118679883/214565982-b709f447-7f67-438b-b108-dba0a3a61cc3.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
