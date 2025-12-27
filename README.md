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
<img width="1920" height="1080" alt="Screenshot 2025-12-27 182711" src="https://github.com/user-attachments/assets/ac9950c5-7093-46f9-9a59-db9ffa409938" />
ii)
<img width="1920" height="1080" alt="Screenshot 2025-12-27 182952" src="https://github.com/user-attachments/assets/9d4c74ec-be53-4f3d-a724-31e9c43b6ed8" />
iii)
<img width="1920" height="1080" alt="Screenshot 2025-12-27 182952" src="https://github.com/user-attachments/assets/efb742ae-e9cc-49c5-9422-bc006556ee6e" />


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
