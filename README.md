# Python Mini Project CIA-1

## Topic:

You can manage your finances with the help of a unique tool like the Python expense tracker project. It's like keeping a digital journal where you can record everything you spend money on. Additionally, you can categorize your spending by types of expenses, such as food, entertainment, and transportation.

You will find it simpler to understand where your money is going thanks to the project. It generates reports and graphs that display your spending in each category so you can better understand your spending patterns. It can also assist you in establishing spending thresholds in each category to prevent overspending.

Your ability to manage your finances and make wiser choices regarding your spending will be made easier thanks to this project. It's like having a personal assistant who manages your finances and keeps track of your outgoings. With the help of this tool, you can become more conscious of your spending patterns and make changes to help you save money and achieve your financial objectives.

## Description:

We decided to work on a Python expense tracker project because  we wanted to develop a practical tool that enables people to manage their money more skilfully. It can be difficult to keep track of expenses, and it's simple to lose track of where our money goes. We want to offer a solution that streamlines this procedure by creating an expense tracker application.

Users of the application can enter their expenses, classify them, and establish budgets for various spending categories. Users can use this to better understand their spending habits and make wise financial decisions. Additionally, the app generates charts and reports that give users a visual representation of their expenses, making it simpler to spot areas where they can make savings or make concessions.

The app can be useful for small businesses or freelancers who need to track their expenses for tax purposes or budget planning, in addition to helping people manage their finances.


## Main Function (List of functions):

The try-except block is used to detect and handle potential errors that could happen while the code is being executed. We can handle any errors that arise and give the user the proper error messages by enclosing the main code logic within the try block.
The user is prompted to enter the budget and the number of months to track expenses inside the try block of the code. Since the input must be converted into integers because these values are expected to be integers, the int() function is used. A ValueError will be raised if the user enters a non-integer value, and the except block will handle it.
Until a valid positive integer is provided, the while loop is used to repeatedly request the amount spent. The raise statement raises a ValueError if the user enters a negative number. The while loop's try-except block detects the ValueError and outputs an error message that asks the user to enter a valid positive integer value.
The amt_list list stores the entered amounts, and the total_amt variable accumulates the total amount spent each month.
The total amount spent is displayed after entering all of the monthly expenses, and it is then compared to the allocated amount. A message indicating the need to control spending is displayed if the overall sum exceeds the budget. If not, a message stating that the budget is being kept is shown.
The amt_list's expense totals are plotted using Matplotlib's plt.plot() function. The user is shown the resulting expense chart.
The except block will catch any exception that arises within the try block. The error message will be displayed along with the specific type of error and any relevant information, indicating that an error has occurred.
The code makes sure that the programme handles potential errors gracefully and gives the user informative error messages by incorporating the try-except block and the while loop.











## Sample Output:
1)	Normal inputs
  ![image](https://github.com/AkanshahChristLavasaaaaa/ExpenseTracker_CIA1_DALmb/assets/118894850/ce289cc8-311e-40a2-951c-93135d760093)
  ![image](https://github.com/AkanshahChristLavasaaaaa/ExpenseTracker_CIA1_DALmb/assets/118894850/cc4a96ab-339b-4f42-a362-03238fe6855d)


 


3)	When negative values are entered:
    ![image](https://github.com/AkanshahChristLavasaaaaa/ExpenseTracker_CIA1_DALmb/assets/118894850/2fa080fa-8787-4be7-b5f6-ce97e5701071)


 



