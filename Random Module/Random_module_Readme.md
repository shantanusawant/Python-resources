> ## This is the Readme file for the Random module working in Python.

----
- This is a program that teaches most of the Python random module.
- First we have to import the random module in our file to be able to use all the inbuilt module functions.
- We do this by **"import random"**.
- Now we can use all the functions inside it.
----
1.] The first function is a function that generates any random interval in the inputed range.

	   random.randint(initial value, limit value)

2. This is the syntax for random integer.
3. The next statement prints the random number.

----

1.] The next function is to generate a random number between a perticular interval by skipping some numbers in between.
		
		random.randrange(3,30, 3)
2. This is the syntax for it.
3. The range starts from 3 to 30, and it skips 2 numbers betweeen every number.
4. Like this range(3,30,3) will be like this, 3,6,9,12,15,18,21,24,27,30.
5. Now this function will select any random integer in this range 3,6,9,12,15,18,21,24,27,30.
6. The next statement prints the random number.

----

1.] The next function is to generate a random number within the range 0-1.
		
		random.random() 
		
2. This is the syntax for it.
3. Then I have multiplied the nnumber by 100 that makes the decimal point shift two spaces to the right.
4. var3 = random.random() * 100
5. The next statement prints the random number.

----

1.] The next Function selects a random list element from a given list and prints it.
2. First we have to create a list.
		
		list_name = ["List_element_1", "List_element_2", "List_element_3",...]

		random.choice(list_name)
3. This is the function syntax.

		var_name = random.choice(list_name)
		print(var_name)
4. This prints the random list element.
5. This is the syntax for doing so.

----

1.] The next Function shuffles a given list.
2. First we have to create a list.

		list_name = ["List_element_1", "List_element_2", "List_element_3",...]

		random.shuffle(List_name)
3. This is the syntax for shuffling the list.

		print ("Printing shuffled list ", List_name)
4. This is the syntax for printing the list.
