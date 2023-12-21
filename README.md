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
''' 
Developed by: B KRISHNAKANTH
RegisterNumber: 23006762
'''
i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python




def max_marks(marks):
        large = max(marks)
        return large
        

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/Krishnakanth23006762/FindMaximum/assets/138849446/8159aabd-20f2-4444-8ba2-f37f766a64ce)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/Krishnakanth23006762/FindMaximum/assets/138849446/500a0b48-3d22-46f7-9dae-0efe3daad1bb)

iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/Krishnakanth23006762/FindMaximum/assets/138849446/dab508dd-e05e-4c4b-8b43-faac4020a4e7)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
