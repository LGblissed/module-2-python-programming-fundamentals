##⭐ Raw Notes – Module 2

###Decisions and Selections Statements
####Code to mimic human thought
####control flow
####if statement (true/false concept)
####if-elif-else (multiple conditions to evaluate)
####elif = else if
####conditions evaluated sequentially until encountering a true condition
####and / or / not (logical operators in game)

###Smarter code

####modularize code into manageable functions
####use dictionaries for more elegant concise solutions
####reduce code complexity and gain clarity
####dictionary mapping → concise, readable, easier to update
####libraries like numpy and pandas → optimized functions (arrays, dataframes)
####goal = improve efficiency while reducing time and effort

###Loops and Conditional Statements

####for loop example: for i in range(1, 11): print(i) → prints 1 to 10
####while(true condition) / while not(false condition) → executes while condition is true
####good for quick games: guess a number until correct
####loops eliminate repetition, enable iteration, they automate

###World Applications

####data analysis
####web development
####game development
####machine learning

###Best Practices

####do not overuse loops or conditionals
####must be concise, easy to debug, easy to understand

###Alternatives

####lists or lambda functions can provide efficient shortcuts
####lambda = tiny, one line, throwaway function

###Operators

####== equal
####!= not equal
####> greater than
####< smaller than
####>= greater than or equal
####<= less than or equal

####conditionals = logic = binary
####for loop = defined range
####while loop = undefined until condition is met
####for i in range(start, stop, step) → always stops before stop

###Lists + Loops Together

####energies = ["subtle", "higher", "lower"]
####divine = energies[1]
####meditative = energies[0]
####human = energies[2]

###Looping styles

####index-based: for i in range(len(energies)) → print(i, energies[i])
####value-based: for energy in energies → print(energy)
####enumerate: for i, energy in enumerate(energies) → print(i, energy)
####enumerate(list) → returns (index, value) pairs

###Lists: Core Notes

####.append() → always adds at the end
####takes exactly one argument
####list grows by 1 each time
####lists can hold many data types
####indexes start at 0

###Matrix

####when you have lists of lists → matrix
####matrix = [[1,2,3], [4,5,6]]
####print(matrix[1][2]) → row 1, column 2

###Random

####import random
####roll = random.randint(1, 6) → includes 6
####roll = random.randrange(1, 6) → goes 1 → 5
####While Loop with Lists
####numbers = [1, 2, 3, 4, 5]
####index = 0
####while index < len(numbers):
####  if numbers[index] % 2 == 0: print(numbers[index])
####  index += 1

###Nested Loops

####for i in range(1, 11):
####  for j in range(1, 11):
####    print(i, "*", j, "=", i * j, end="\t")
####  print() # new line

###Loop + Condition Example

####max_value = 50
####for number in range(max_value + 1):
####  if number % 3 == 0 and number % 4 == 0: print(number)

###Flow Concept

####control flow = flexible
####mimics human logic and reasoning
####creates smart, clear sequences

###Even / Odd Example

####numbers = [3, 9, 1, 10, 5, 2, 8]
####for number in numbers:
####  if number % 2 == 0: print(number, "is even")
####  else: print(number, "is odd")
  
###List Methods

####list.append(x) → add at end
####list.insert(i, x) → insert at index
####list.remove(x) → remove first occurrence
####list.sort() → ascending order
####list.reverse() → reverse order
####list.count(x) → count occurrences
####len(list) → number of items
####x in list → membership check
####list.index(x) → position of first x

####lists are not static
