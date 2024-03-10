arr = input("Enter a list of numbers separated by spaces: ")

# Convert the input string into a list of integers
num = [int(i) for i in arr.split()]

# Calculate the sum of elements in the list
s = sum(num)

# Print the result
print("Sum of elements in the list:", s)
