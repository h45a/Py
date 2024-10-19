import random

def generate_random_matrix(rows, cols):
    matrix = []
    for i in range(rows):
        row = []
        for j in range(cols):
            number = random.randint(1, 100)
            row.append(number)
        matrix.append(row)
    return matrix

def get_column_sum(matrix, column_index):
    total = 0
    for row in matrix:
        total += row[column_index]
    return total

def get_row_average(matrix, row_index):
    total = sum(matrix[row_index])
    average = total / len(matrix[row_index])
    return average

rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))
matrix = generate_random_matrix(rows, cols)

print("Generated Matrix:")
for row in matrix:
    print(row)

column_index = int(input("Enter the column index to sum (0 to " + str(cols - 1) + "): "))
column_sum = get_column_sum(matrix, column_index)
print("Sum of column " + str(column_index) + ": " + str(column_sum))

row_index = int(input("Enter the row index to average (0 to " + str(rows - 1) + "): "))
row_average = get_row_average(matrix, row_index)
print("Average of row " + str(row_index) + ": " + str(row_average))
