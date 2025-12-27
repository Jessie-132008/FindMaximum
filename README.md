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
marks = list(map(int, input("Enter marks: ").split()))

marks.sort()
print("Maximum marks:", marks[-1])


```

ii)	# To find the maximum marks using the list method max().
```
marks = list(map(int, input("Enter marks: ").split()))

print("Maximum marks:", max(marks))


```

iii) # To find the maximum marks without using builtin functions.
```
marks = list(map(int, input("Enter marks: ").split()))

maximum = marks[0]
for m in marks:
    if m > maximum:
        maximum = m

print("Maximum marks:", maximum)


```



## Output:
i)
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/80e0a4ae-e248-476b-9021-2dc8232c3531" />
ii)
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/436357bf-6846-486d-87a1-975e90e140ac" />
iii)
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/183bacab-98ab-4b4c-aec8-7607cc45c9ae" />


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
