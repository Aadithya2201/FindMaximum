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
#Developed by: Aadithya.R
#RegisterNumber: 23006361

def max_marks(marks):
    marks.sort()
    return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```
#Program to find the maximum marks using the list method max().
#Developed by: Aadithya.R
#RegisterNumber: 23006361

def max_marks(marks):
    m=max(marks)
    return m
    
```

iii) # To find the maximum marks without using builtin functions.
```
#Program to the maximum marks without using builtin functions.
#Developed by: Aadithya.R
#RegisterNumber: 23006361

def max_marks(list1):
    a=0
    for m in list1:
        if m>a:
            a=m
    return a
```
## Sample Input and Output
![Screenshot 2023-12-28 153941](https://github.com/Aadithya2201/FindMaximum/assets/145917810/0da67af5-6462-4252-9e95-0a3e16d39e3f)


## Output:
![Screenshot 2023-12-28 153422](https://github.com/Aadithya2201/FindMaximum/assets/145917810/d7bc9643-72d2-4221-8aaf-1657db5b8d44)

![Screenshot 2023-12-28 153441](https://github.com/Aadithya2201/FindMaximum/assets/145917810/4ec653ca-9b51-4b8e-87b6-8e64caa7b64a)

![Screenshot 2023-12-28 153454](https://github.com/Aadithya2201/FindMaximum/assets/145917810/e337f85a-965b-4515-9cff-ca05cfe139b0)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
