# Windows-basic-commands-batchscript
# Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

<img width="524" height="117" alt="image" src="https://github.com/user-attachments/assets/b7cc64c4-4b32-4dd6-b174-b74ae25f7283" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="535" height="163" alt="image" src="https://github.com/user-attachments/assets/97786413-45f1-48a6-a701-a9818a756522" />

## COMMAND AND OUTPUT


Create the file Rose.txt

<img width="777" height="443" alt="image" src="https://github.com/user-attachments/assets/c7fc4098-16e5-49ef-b0b0-fcefae82b820" />

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

<img width="695" height="151" alt="image" src="https://github.com/user-attachments/assets/8561e0bc-fe3b-4fdb-8a2e-8d881fa35b90" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="587" height="89" alt="image" src="https://github.com/user-attachments/assets/816e496e-f11a-40ba-9474-1855e25b020f" />

## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="463" height="51" alt="image" src="https://github.com/user-attachments/assets/e34d8433-b7ee-4209-9604-d1da5b5704cd" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="632" height="194" alt="image" src="https://github.com/user-attachments/assets/ae6ae9cc-5052-4aa5-b2f3-7c10f944c8b3" />

## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="466" height="830" alt="image" src="https://github.com/user-attachments/assets/7aab2dd4-e750-4a24-8ce9-b8e838095fb6" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

<img width="521" height="233" alt="image" src="https://github.com/user-attachments/assets/04a5fcfd-eb5b-44db-894f-c5223cc8e542" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="487" height="104" alt="image" src="https://github.com/user-attachments/assets/e32cfca6-cfe1-407e-8137-4f35f8b6aed1" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="594" height="200" alt="image" src="https://github.com/user-attachments/assets/4b32e002-0fbe-46ba-ae32-07d9515a5700" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="406" height="196" alt="image" src="https://github.com/user-attachments/assets/0a7f3ec6-3d41-487b-87aa-c1752726f024" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="703" height="229" alt="image" src="https://github.com/user-attachments/assets/c17dda20-c9f5-456a-83e0-92552d8a0173" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="486" height="376" alt="image" src="https://github.com/user-attachments/assets/3fbe5998-e10c-4bb6-a044-33d7aefb483a" />



# RESULT:
The commands/batch files are executed successfully.

