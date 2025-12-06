# Python-12
Write a python program to find the average of the list of the numbers entered through keyboard.
n=int(input("Enter the limit:"))
s=0
for i in range(1,n+1):
    print("Enter ",i,end='')
    a=int(input("th number;"))
    s=s+a
avg=s/n
print("The sum of entered numbers:",s)
print("The average of entered numbers:",avg)
Output
Enter the limit:55
Enter  1th number;5
Enter  2th number;5
Enter  3th number;2
Enter  4th number;5
Enter  5th number;7
Enter  6th number;8
Enter  7th number;9
Enter  8th number;9
Enter  9th number;7
Enter  10th number;2
Enter  11th number;5
Enter  12th number;0


