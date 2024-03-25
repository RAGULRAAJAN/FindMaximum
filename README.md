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
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large=max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max



```



## Output:
i) To find the maximum of marks using the list method sort.
![Screenshot 2024-03-25 051956](https://github.com/RAGULRAAJAN/FindMaximum/assets/147473144/ceb10188-f58b-4caa-b58c-56a099118906)

ii)	To find the maximum marks using the list method max().
![Screenshot 2024-03-25 052012](https://github.com/RAGULRAAJAN/FindMaximum/assets/147473144/2c02d8a5-0676-41bc-9775-d9a69e7181c8)

iii) To find the maximum marks without using builtin functions.
![Screenshot 2024-03-25 052027](https://github.com/RAGULRAAJAN/FindMaximum/assets/147473144/7d3a5c85-980a-4d6f-8b64-ac0d4b40ca74)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
