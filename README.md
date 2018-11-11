# Pocket-Booking  
#  Features 
‣ View your entire, color-coded history log of how much, why, where, and when money was spent  
‣ Integrated the application with the Google Maps API to visualize where money was spent when the user travels  
‣ When a user taps on a transaction, the map animates and centers on the location of where the transaction happened  
‣ Create a budget with a name and starting balance  
‣ Spend or add money to any budget, adding to your history  
‣ Check your pie chart to see the net amount spent per budget; every time you view the pie chart it is drawn with 1 out of the 10 color schemes included in my design, offering visibility and clarity on up-to-date data  
‣ View your transaction history within a specified time interval (past week, month, or year) on a bar graph      
– A horizontal line details the average amount spent per day for the specified time interval      
– The user can customize each budget's bar graph with 11 different color schemes  
‣ Manage multiple budgets at once  
‣ Undoing an item in your history or deleting your entire history reverts your balance to its original value  
‣ Rename and delete budgets   

# Design 
‣ Implemented CoreData to store pertinent information unique to the individual budgets  
‣ Designed a class that efficiently populates the x and y axes of the bar graphs  
‣ Constructed a backend design that stores the location information of each transaction  
‣ Developed an efficient method for retrieving data by relying on the fast lookup of Swift dictionaries when dealing with transaction history  
‣ Constructed a dictionary that maps the current date to the total amount spent on that particular day  
‣ Buttons enable and disable dynamically based on the validity of input:      
– Balance must be between $0 and $1,000,000      
– Spend button only enables when your balance is enough based on current input      
– Renaming actions require the new name to be unique  
‣ History of transactions records the date of transaction along with a corresponding color:     
– Red for money spent      
– Green for money added     
– Deleting history essentially reverts the transaction and restores your balance  
‣ Creating names will add (a number) if the name already exists:      
– I.E. if "Mall" is already a budget name, naming new "Mall" budgets results in "Mall (1)", "Mall (2)", etc.  ‣ Number Formatter:      
– Used a regular expression to ensure that user inputs cannot exceed past 2 decimal places      
– Dollar amounts include comma separators and a $ sign in the front  
‣ Programmatically utilized alerts to record user input  
‣ List of budgets and each budget's history is displayed using a UITableview  
‣ Used IBOutlets to programmatically interact with user interface elements  
‣ Defined an IBAction function that corrects button-enabling every time the user types or deletes a character 

Thanks for your support, please continue to use our app, if you have any questions, please send us an email and we will reply you as soon as possible. Thank you
Email: wave190@gmail.com
