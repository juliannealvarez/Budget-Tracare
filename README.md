# Final Term Project | LBYEC2B - EL1

## Budget-Tracare

Money has become a very crucial aspect of living as it allows us to buy the necessities of life such as food, clothing, and shelter. It is considered to be significant as, without money, we would not be able to pursue our education, pay for medications, and avail of important services in the market. Generally, money revolves around everything that we do and acquire. 

According to the Cambridge Dictionary, budgeting is the process of calculating how much money you must earn or save during a particular time, and of planning how you will spend it [1]. Students need to learn the basics of budgeting so that they will have sufficient money to buy the things they need in the future. Knowing how to prioritize their needs will also prevent them from buying unnecessary things and therefore lead to saving money. 

With the Budget TraCare program, students will be able to manage their finances properly. It will allow them to input their expenses as well as check if they have exceeded their budget. This program will serve as their stepping stone in organizing and planning their finances. This will also teach them the importance of proper money handling and be able to save money in the future. Furthermore, this program can only be accessed by a specific user as it contains a log-in feature making use of a username and password. <br>

The objective of this program is to utilize and apply the programming concepts learned from the course. The following programming concepts used for Budget Tracare are: <br>
* String, Array of strings, and String processing: Was used to store and declare variables in the program. Moreover, it was utilized during the process of entering the expenses as well as the budget. <br>
* Loop Function: A while loop was utilized to limit the number of inputs (maximum of three inputs only) a user can do in accessing his/her username and password. <br>
* If-else Statement: An if-else statement was used for the user log-in attempt feature. <br>
* File I/O: Created a text file so that the user will remember their breakdown of expenses and comparison of budget to actual. <br>
* OOP: Class Definition and Object Creation: It utilized classes that contain the attributes needed for the expenses and budget.  It also created an object of the two classes. <br> <br>

See the sample outputs below:

| Sample Console Input | Expected Console Output                                                                                                                                                                                                     |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Julianne.A <br>LBYectwob<br>ArmeilaC <br>LByectwob<br>Julianne <br>Alvarez            | Budget Tracare<br><br>Please enter your USERNAME: JulianneA<br>Please enter your PASSWORD: LBYectwob<br>Wrong username or password try again!<br><br>Please enter your USERNAME: ArmeilaC<br>Please enter your PASSWORD: LByectwob<br>Wrong username or password try again!<br><br>Please enter your USERNAME: Julianne<br>Please enter your PASSWORD: Alvarez<br><br>Too many login attempts! The program will now terminate.                                         |
| Julianne.A <br>LBYecTWOb <br>any key<br>100 <br>200 <br>300 <br>400 <br>500 <br>1<br>any key <br>2 <br>200 <br>300 <br>400 <br>500 <br>600 <br>any key<br>3              | Budget Tracare<br><br>Please enter your USERNAME: Julianne.A<br>Please enter your PASSWORD: LBYecTWOb<br><br>Welcome Julianne! Thank you for logging in. You may enter your expenses. :)<br>Press any key to continue.....<br><br>EXPENSES<br>Enter your Shopee/Lazada expenses: 100<br>Enter your Food expenses: 200<br>Enter your Medical expenses: 300<br>Enter your Entertainment expenses: 400<br>Enter your Miscellaneous expenses: 500<br><br>Expenses:<br>1. Breakdown<br>2. Comparison of Budget to Actual<br>3. Exit<br>Choice: 1<br>Press any key to continue.....<br><br>Category   Expenses<br>Shopee/Lazada   100<br>Food   200<br>Medical   300<br>Entertainment   400<br>Miscellaneous   500<br>Total Expenses   1500<br>Press any key to continue.....<br><br>Expenses:<br>1. Breakdown<br>2. Comparison of Budget to Actual<br>3. Exit<br>Choice: 2<br>Press any key to continue.....<br><br>BUDGET<br>Enter your Shopee/Lazada budget: 200<br>Enter your Food budget: 300<br>Enter your Medical budget: 400<br>Enter your Entertainment budget: 500<br>Enter your Miscellaneous budget: 600<br><br>Category   Budget   Expenses   Over(-)/Under<br>Shopee/Lazada   200.00   100.00   100.00<br>Food   300.00   200.00   100.00<br>Medical   400.00   300.00   100.00<br>Entertainment   500.00   400.00   100.00<br>Miscellaneous   600.00   500.00   100.00<br>For the month you are over budget    Php 500.00<br>Press any key to continue.....<br><br>Expenses:<br>1. Breakdown<br>2. Comparison of Budget to Actual<br>3. Exit<br>Choice: 3<br>Press any key to continue.....<br><br>THANK YOU! |
