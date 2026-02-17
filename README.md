numbers=list(map(int,input("Enter numbers: ").split()))
big=numbers[0]
for i in numbers:
    if i>big:
        big=i
print("Largest:",big)
Output
Enter numbers: 3 7 2 9 1
Largest: 9
