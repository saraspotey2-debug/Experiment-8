# Experiment-8
# Aim
Study of for loop in python.
# Theory
1. A for loop in Python is a control statement used to repeat a block of code multiple times. It is mainly used when the number of iterations is known or when you want to iterate over a sequence like a list, string, tuple, or range.
2. A for loop executes a group of statements for each item in a sequence.
3. It works as-Python takes the first value from the sequence, Assigns it to the loop variable, Executes the code inside the loop, Moves to the next value and Repeats the process until the sequence is finished.
4. The range() function generates a sequence of numbers.
5. Important Features of for Loop-Used for sequences (list, tuple, string, range, etc.), Automatically stops after last element, No need to manually update loop variable and Makes code simple and readable.
6. for Loop with else-Python allows an else block with a for loop.
7. Advantages of for Loop-Easy to use, Less chance of infinite loop, Clean and readable code and Works directly with collections.
8. Range- The range() function in Python is used to generate a sequence of numbers. It is commonly used in loops like the for loop.
# Algorithm-1
1. Start
2. Initialize a loop variable i to iterate from 1 to 5 using range(1,6)
3. Repeat the following steps for each value of i:
4. Print the value of i
5. Stop when the loop ends (after i = 5)
6. End
# Algorithm-2
1. Start
2. Input a number n from the user
3. Initialize a variable total = 0
4. Start a loop from i = 1 to n (using range(1, n+1))
5. For each value of i, do:
6. Add i to total, total = total + i
7. Repeat step 5 until the loop ends
8. Display the value of total as the sum
9. End
# Algorithm-3
1. Start
2. Define a 3×3 matrix A with given elements
3. Initialize outer loop with i = 0 to 2 (for rows)
4. For each row i, do the following:Initialize inner loop with j = 0 to 2 (for columns)
5. Print the element at position A[i][j] with a space
6. Repeat until all columns of that row are printed
7. After finishing each row, print a new line
8. Repeat steps 4–5 until all rows are completed
9. End
# Algorithm-4
1. Start
2. Define matrix A (3×3)
3. Define matrix B (3×3)
4. Initialize result matrix Result with all elements as 0 (3×3 matrix)
5. Use three nested loops:Outer loop i from 0 to 2 (rows of A), Middle loop j from 0 to 2 (columns of B) andInner loop k from 0 to 2 (for multiplication and addition)
6. For each position (i, j) in Result:Multiply corresponding elements→ A[i][k] * B[k][j]
7. Add to Result[i][j] Result[i][j] = Result[i][j] + A[i][k] * B[k][j]
8. Repeat until all rows and columns are processed
9. Print each row of the Result matrix
10. End
# Algorithm-5
1. Start
2. Set the range of numbers from 2 to 49 (using range(2, 50))
3. For each number num in this range, do the following:Check divisibility of num by all numbers from 2 to num-1
4. For each value i in range(2, num):If num % i == 0 num is not prime and Exit the inner loop using break,If the inner loop completes without finding any divisor
(i.e., no break occurred), then:num is a prime number
5. Print num
6. Repeat steps for all numbers in the range
7. End
# Algorithm-6
1. Start
2. Initialize a loop variable i from 5 down to 1(using range(5, 0, -1))
3. For each value of i, do the following:
4. Print "*" repeated i times "*" * i
5. Move to the next value of i (decrease by 1 each time)
6. Stop when i becomes 0
7. End
# Algorithm-7
1. Start
2. Initialize variable rows = 5
3. Start a loop with i from 1 to rows (using range(1, rows+1))
4. For each value of i, do:Calculate number of spaces → (rows - i),Calculate number of stars → i.
5. Print:Spaces " " * (rows - i),Followed by stars "* " * i and then it Move to the next value of i
6. Stop when i exceeds rows
7. End
# Conclusion
A for loop in Python is used to iterate over sequences and execute a block of code repeatedly. It is simple, efficient, and widely used for processing data collections.
