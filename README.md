num=[10,20,30,40,50]
print("Original list:",num)
num.append(60)
print("After append(60): ",num)
num.insert(1,15)
print("After insert(1,30): ",num)
num.remove(30)
print("After remove(30): ",num)
num.pop(0)
print("After pop(0): ",num)
num.extend([60,70])
print("After extend(60,70): ")
print("Index of 50: ",num.index(50))
print("Count of 40: ",num.count(40))
num.sort()
print("After sort: ",num)
num.reverse()
print("After reverse: ",num)
copy_lis=num.copy()
print("Copied list: ",copy_lis)
print("Length of the list: ",len(num))
print("Maximum value: ",max(num))
print("Minimum Value: ",min(num))
print("Sum of list: ",sum(num))
print("After Clear: ",num.clear())




OUTPUT:
Original list: [10, 20, 30, 40, 50]
After append(60):  [10, 20, 30, 40, 50, 60]
After insert(1,30):  [10, 15, 20, 30, 40, 50, 60]
After remove(30):  [10, 15, 20, 40, 50, 60]
After pop(0):  [15, 20, 40, 50, 60]
After extend(60,70): 
Index of 50:  3
Count of 40:  1
After sort:  [15, 20, 40, 50, 60, 60, 70]
After reverse:  [70, 60, 60, 50, 40, 20, 15]
Copied list:  [70, 60, 60, 50, 40, 20, 15]
Length of the list:  7
Maximum value:  70
Minimum Value:  15
Sum of list:  315
After Clear:  None
