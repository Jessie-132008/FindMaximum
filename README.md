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
marks = list(map(int, input("Enter marks: ").split()))

marks.sort()
print("Maximum marks:", marks[-1])


```

ii)	# To find the maximum marks using the list method max().
```Python
marks = list(map(int, input("Enter marks: ").split()))

print("Maximum marks:", max(marks))


```

iii) # To find the maximum marks without using builtin functions.
```Python
marks = list(map(int, input("Enter marks: ").split()))

maximum = marks[0]
for m in marks:
    if m > maximum:
        maximum = m

print("Maximum marks:", maximum)


```



## Output:
i)
<img width="1920" height="1080" alt="Screenshot 2025-12-27 182832" src="https://github.com/user-attachments/assets/1fe03772-9a48-4173-a25c-4d743d6a24fe" />

ii)
<img width="1920" height="1080" alt="Screenshot 2025-12-27 182711" src="https://github.com/user-attachments/assets/57a745ed-a77c-4411-bb2e-eb84e54c8303" />

iii)
<img width="1920" height="1080" alt="Screenshot 2025-12-27 182952" src="https://github.com/user-attachments/assets/d54824c6-9eac-4f93-8a4c-fea0977ea9d1" />

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
