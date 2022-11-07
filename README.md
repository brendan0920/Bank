# YOUR PROJECT TITLE : ATM Machine
#### Video Demo:  <URL https://youtu.be/SqhPEQy8p3c>
#### Description: I have created two files called project . py and test _ project _ py under a folder named project. By running this project. py file, you will be able to see five define variables such as 1 def main, 2 def get bank, 3 def get deposit, 4 def get withdraw, 5 def ask transaction. First, on the def main part, you will be able to see variables and functions as bank = get bank, deposit = get deposit, withdraw = get withdraw, balance = deposit - withdraw, message = main messages to be shown by using f function when running the program, then print (message), then ask transaction() for the last. The main message would be like this; f" \n YOUR TRANSACTION BELOW: \n On your '{bank.upper()}' account: \n Deposited: ${deposit:. 2f} \n Withdrawn: $ {withdraw:. 2f} \n Net Available Balance: $ {balance:. 2f} \n" so all the numbers will be shown upto 2 decimal points with $ sign.  Second, from the def get bank part, you will be able to choose your bank from the five major banks in the united states as I listed on the program as following: Chase bank, Wells Fargo bank, Citi bank, US bank and Bank of America. On this function, I have applied list, input with case insensitive using casefold and strip() to get rid of any spaces after users type at the end by accident. If users input banks not listed from the list then a message will be printed with description in order for users to input again like this: "Choose from 5 major banks as following: Chase, Wells Fargo, Bank of America, Citi Bank, US bank". It will keep asking until users the program get the right answer, so I used while loop to keep asking and used try and except to get away from the ValueError. Third, on the def get deposit part, I used the input function with float so users only will be able to type in numbers up to 2 decimal points. And I used if function to make the number only positive including 0. If users type in either negative numbers or any letters or special characters, then it will print as Invalid Amount and will keep asking until the users type in only positive numbers including up to 2 decimal points. Fourth, on the def get withdraw part, as the same as the def get deposit part,  I used the input function with float so users only will be able to type in numbers up to 2 decimal points. And I used if function to make the number only positive including 0. If users type in either negative numbers or any letters or special characters, then it will print as Invalid Amount and will keep asking until the users type in only positive numbers including up to 2 decimal points. Fifth, on the def ask transaction part, I also used the while loop to ask users a question like 'Do you want another transaction? Yes/No' for users to choose to keep using this machine or quit the program afterwards. Users will be able to input either yes, y, no or n with case insensitive and strip() to get away from the users to input any spaces at the end of the answer typed in by accident. And this program will keep running until the users input no to the question at the end of the program. Also I have created test _ project. py using assert to make sure all is working right.