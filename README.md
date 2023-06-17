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
```Pythondef max_marks(marks):

DEVELOPED BY:JERUSHLIN JOSE J B
REG NO:212222240039

''' 
def max_marks(marks):
    marks.sort()
    large = max(marks)
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    # write your code here
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i >max:
            max=i
    return max

```
## Sample  Output :





![image](https://github.com/Jerushli/FindMaximum/assets/120041243/e90cbe0b-fd99-48ad-93de-da550f9a1f65)






![image](https://github.com/Jerushli/FindMaximum/assets/120041243/250476e7-10ad-41a3-a0de-4a2f38f4991f)





![image](https://github.com/Jerushli/FindMaximum/assets/120041243/e95a41be-ba23-4f57-9614-713ce4d747af)







## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
