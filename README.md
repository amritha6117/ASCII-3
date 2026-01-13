# ASCII-3
tpl = eval(input("Enter tuple: "))

length = len(tpl)
total = 0

for i in range(length):
    total += tpl[i]

mean = total / length

print("Given tuple is:", tpl)
print("The mean of given tuple is:", mean)
output:
Enter tuple: (10,20,30,40)
Given tuple is: (10, 20, 30, 40)
The mean of given tuple is: 25.0
