Author: 	TJ Christian (Thomas Christian)
Program:	BasicBudgetBuilder

This program was written for the WinterWonderHack 2020 event by TJ Christian alone.




BasicBudgetBuilder lets you build a basic month-by-month budget that you can keep track of!  Simply run the 
application file in this folder to launch it and get started making your own budgets!  



The other .txt files in this directory are important for the program and are how it remembers things.
Feel free to take a look at them, but be careful about altering them as the program reads and writes to them in
a very specific format.

Here's how the filesystem is setup:
	There is a "ListOfBudgets.txt" file that contains the name of every "budget file" the program remembers.
	if you ever have a problem reading a certain file or want to delete it, remove it (and the line its on)
	from the "ListOfBudgets.txt" file as well.

	The other files are all "budget files" and share the same name as the budgets they represet.  each file
	contains the list of transactions the program assosiates with that budget.
	It stores this infomation in the form: [amount] [month] [year] [name] where the month is represented by
	a number ranging from 0-11 corresponding to each month out of the year.  

	The other files were related to the construction of the application file and are there for reference.


How to use the program: 
	Start by running the BasicBudgetBuilder application and either creating a new budget, or using the empty
	"NewBudget" budget that's already included.  Next, use the "add income" and "add expense" buttons to add
	sources of income and expenses.  Give them a name and input some numerical value for them.  Faulty inputs
	don't have much protection as i was running out of time to add more, so inputing a string into the amount
	section (or something similar) might break the program.  The program automatically launches on the current
	month, but you can use the "Next Month" and "Previous Month" buttons to navigate between different months.
	Make sure to press the save button when you're done or none of your changes will save.





