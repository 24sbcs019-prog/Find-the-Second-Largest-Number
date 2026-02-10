# Find-the-Second-Largest-Number
a = []
n = int(input("Enter number of elements: "))

for i in range(n):
    b = int(input("Enter element: "))
    a.append(b)

a.sort()
print("Second largest element is:", a[n - 2])
Output;
Second largest element is: 30
