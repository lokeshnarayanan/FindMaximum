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
Developed by:Lokesh N 
RegisterNumber:212222100023 

def max_marks(marks):
    #Write your code here
    marks.sort()
    return(marks[-1])
```
ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: Lokesh N
RegisterNumber: 212222100023

def max_marks(marks):
    # write your code here
    large=max(marks)
    return large;
```
iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: Lokesh N
RegisterNumber: 212222100023

def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
 ```


## Output:
i)	# To find the maximum of marks using the list method sort.

![image](https://user-images.githubusercontent.com/119393019/235291641-34c08f39-416d-41b2-8df6-94d8a19494df.png)

ii)	# To find the maximum marks using the list method max().

![image](https://user-images.githubusercontent.com/119393019/235291665-14944b68-e1ea-4cd7-a6fe-d1dd215047ae.png)

iii) # To find the maximum marks without using builtin functions.

![image](https://user-images.githubusercontent.com/119393019/235291673-9ae60361-cdce-4cd0-8bdc-8f943a3d51fc.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
