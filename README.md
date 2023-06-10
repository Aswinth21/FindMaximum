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
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    l=max(marks)
    return l
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![image](https://github.com/Aswinth21/FindMaximum/assets/120236638/b1a93a93-f690-4882-9c96-5b6c2aa2ae92)

![image](https://github.com/Aswinth21/FindMaximum/assets/120236638/a9c6c855-1ca8-4864-9f4a-b01173b2785b)

![image](https://github.com/Aswinth21/FindMaximum/assets/120236638/3abd9a68-97b2-457a-a190-2122bfe62464)


## Output:
![image](https://github.com/Aswinth21/FindMaximum/assets/120236638/fda991ff-9f5d-4844-ad3f-46e21d72e739)

![image](https://github.com/Aswinth21/FindMaximum/assets/120236638/5837dc46-a8fe-4c53-b09d-d18cbf440b3c)

![image](https://github.com/Aswinth21/FindMaximum/assets/120236638/00347c7e-deaa-42e5-af36-f25942aef485)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
