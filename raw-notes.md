## decisions and selections statements

#### code to mimic human thought
##### control flow

##### if statement (true/false concept)
##### if-elif-else (multiple conditions to evaluate)
##### elif = else if
##### conditions evaluated sequentially till encountering a true condition
##### and-or-not (logical operators in game)

##### modularize code into manageable functions
##### use dictionaries for more elegant concise solutions
##### reduce code complexity and gain clarity
##### dictionary mapping: more concise, readable and easier to update
##### libraries like numbpy and pandas for optimized functions, like arrays or dataframes
##### its all about improving efficiency while reducing time and effort

## loops and conditional statements
##### for loop, for i in range(1, 11):
 #####    print(i) #i prints 1,2...10. the range between 1 and 11 is 10.
##### while(true condition)/while not(false condition) loop, while condition remains true, execute.(for unknown number of iterations)
##### great for a quick game to guess a number, until the number is not guessed correctly, the loop repeats asking for user input
##### loops eliminate code repetition, enable efficient iteration, they automate.

#### world applications

##### data analysis, web development, game development, machine learning.
##### not overuse loops or conditionals, they must be concise. easy to debug, easy to understand.
##### lists or lambda functions provide more efficient ways to achieve same results as loops or conditionals.
##### A lambda function in Python is just a tiny, one line, throwable function.

#### == equal
#### != not equal
#### > greater than
#### < smaller than
#### >= greater than or equal
#### <= less than or equal
#### conditionals = logic = binary
#### for loop = defined range
#####while loop = undefined until a condition is met
#### for i in range(start, stop, step) it always stops before stop, the loop stops before stop. nice

##### now we have list and loops. here we are actually learning stuff so we have like, energies = ["subtle", "higher", "lower"]
##### and the index starts at 0 so if then i declare
##### divine = energies[1]
##### meditative = energies[0]
##### human = energies [2]

##### for i in range(len(energies)): loops over indexes, gives indexes.
 #####   print(i, energies[i])

##### for energy in energies: loop over the list without no need of index, does not give no index output
 #####   print(energy)

##### for i, energy in enumerate(energies): / enumerate() → index + value at the same time.
  #####  print(i, energy)

##### enumerate(list) → gives you pairs (index, value).
##### .append() always adds at the end.
##### It takes exactly one argument.
##### The list size grows by 1 each time.
##### when you have a list filled by lists, is most commonly defined as a matrix
##### matrix = [[1,2,3],[4,5,6]], now we have row and colums

##### import random
##### roll  = random.randint(1, 6)
##### roll = a random intiger from 1 to 6. it takes the whole range.
##### now
##### roll =random.randrage(1,6).
##### roll= a random intiger from 1 to 5. it has the same stop condition as a for i in range

##### numbers = [1, 2, 3, 4, 5]
##### index = 0
##### while index < len(numbers):
##### if numbers[index] % 2 == 0: # (%(modulus)2 ==0: prints pairs(even) if 2 !=0; prints impairs(odd)
##### print(numbers[index])
##### index += 1

##### nested loops(loop inside a loop)
##### for i in range(1, 11):
##### for j in range(1, 11):
##### print(i, "*", j, "=", i * j, end="\t") # Print the equation...
##### print() # Move to the next line after each row(aesthetic purposes, output readability)

##### max_value = 50
##### for number in range(max_value + 1): # goes 0 → 50
##### if number % 3 == 0 and number % 4 == 0:  # divisible by 3 AND 4
##### print(number)

##### control flow: flexibile, intelligence applied, human logic reasoning style, smart sequence. clear code.

##### numbers = [3, 9, 1, 10, 5, 2, 8]
##### for number in numbers:
##### if number % 2 == 0:
##### print(number, "is even")
##### else:
##### print(number, "is odd")

##### lists can hold many data types.
##### index from the list start at 0
##### two dimensional list = matrix
##### print(index[1][2]) 1, row, 2, column.

#### list methods
##### list.append(x): Adds x to the end of the list.
##### list.insert(i, x): Inserts x at index i in the list.
##### list.remove(x): Removes the first occurrence of x from the list.
##### list.sort(): Sorts the items in the list in ascending order.
##### list.reverse(): Reverses the order of items in the list.
##### list.count(x): Counts how many times x appears in the list.
##### len(list): Tells you how many things are in the list.
##### x in list: Checks if x is in the list.
##### list.index(x): Tells you the position of the first x in the list.
##### lists are not static
