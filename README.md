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
#Program to mark the maximum of marks using the list method sort
#Developed by:Dharanish MS
#RegisterNumber: 23011819
def max_marks(marks):
marks.sort()
large=marks[-1]
return large



```

ii)	# To find the maximum marks using the list method max().
```
#Program to find the maximum marks using the list method max().
#Developed by: Dharanish MS
#RegisterNumber: 23011819
def max_marks(marks):
large=max(marks)
return large



```

iii) # To find the maximum marks without using builtin functions.
```
#Program to the maximum marks without using builtin functions.
#Developed by: MS Dharanish
#RegisterNumber: 23011819
def max_marks(list1):
max=list1[0]
for i in list1:
if i>max:
max=i
return max



```
## Output:
i)	# To find the maximum of marks using the list method sort.
![Screenshot 2023-12-21 183659](https://github.com/MSDharanish-23011819/FindMaximum/assets/147139454/e7818293-cfd2-4fcc-9888-99e2cfa9e502)

ii)	# To find the maximum marks using the list method max().
![Screenshot 2023-12-21 183940](https://github.com/MSDharanish-23011819/FindMaximum/assets/147139454/b38fcf71-1af5-4001-9667-cce751246f0e)



iii) # To find the maximum marks without using builtin functions.
![Screenshot 2023-12-21 184043](https://github.com/MSDharanish-23011819/FindMaximum/assets/147139454/9a2f511b-a6e4-4af5-a6d6-80f7d71984cd)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
