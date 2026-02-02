# program-103
# Input count of numbers
count = int(input("Enter the count of numbers: "))

# Initialize total
total = 0

# Loop to input numbers and calculate sum
for _ in range(count):
    x = int(input("Enter an integer: "))
    total += x

# Calculate average
avg = total / count

# Print the result
print("The average is:", avg)
output
Enter the count of numbers: 5
Enter an integer: 4
Enter an integer: 6
Enter an integer: 8
Enter an integer: 10
Enter an integer: 12
The average is: 8.0
