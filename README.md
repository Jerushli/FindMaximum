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
## Sample Input and Output





![image](https://github.com/Jerushli/FindMaximum/assets/120041243/bb84516b-a021-4743-a077-69d62c3a3f87)





![image](https://github.com/Jerushli/FindMaximum/assets/120041243/0cc596b4-6c39-47c3-8d5d-811d8461ba4e)




![image](https://github.com/Jerushli/FindMaximum/assets/120041243/69cc60ae-f5a9-4c8d-89ac-121323fabbd6)







## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
