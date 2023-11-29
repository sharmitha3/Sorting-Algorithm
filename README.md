# Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: SHARMITHA V
RegisterNumber: 23002259
def selection_sort(nums):
    for i in range(len(nums)):
        min_i=i
        for j in range(i+1,len(nums)):
            if nums[j]<nums[min_i]:
                min_i=j
        nums[i],nums[min_i]=nums[min_i],nums[i]
list_of_nums = eval(input())
selection_sort(list_of_nums)
print(list_of_nums)





```
ii)	#Insertion Sort
```
Program to sort the elements in the list using the Insertion Sort algorithm.
Developed by: SHARMITHA V
RegisterNumber: 23002259
def insertion_sort(nums):
    for i in range(1,len(nums)):
        while i>0 and nums[i-1]>nums[i]:
            nums[i-1],nums[i]=nums[i],nums[i-1]
            i-=1
list_of_nums = eval(input())
insertion_sort(list_of_nums)
print(list_of_nums)

```
## Sample input:
![image](https://github.com/sharmitha3/Sorting-Algorithm/assets/145974496/02e774d0-d8b4-4f87-82d6-e525ce1bf990)
![image](https://github.com/sharmitha3/Sorting-Algorithm/assets/145974496/8e39c404-7ef5-4d76-adcc-8daf6268d0cb)

## Output:
![image](https://github.com/sharmitha3/Sorting-Algorithm/assets/145974496/8f7b700a-7280-41f2-9ad9-70575b3dc502)
![image](https://github.com/sharmitha3/Sorting-Algorithm/assets/145974496/4f3d9d70-708e-4b9c-a2fa-2880e7ba6c81)



## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
