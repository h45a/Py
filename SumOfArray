def sum_of_elements(numbers, exclude_negative=False):
    total = 0
    for num in numbers:
        if exclude_negative and num < 0:
            continue
        total += num
    return total

user_input = input("Enter a list of numbers separated by spaces: ")
numbers = list(map(int, user_input.split()))

exclude_negative = input("Exclude negative numbers? (yes/no): ")

if exclude_negative == "yes":
    exclude_negative = True
else:
    exclude_negative = False

total_sum = sum_of_elements(numbers, exclude_negative)
print("The sum is:", total_sum)
