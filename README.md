# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

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
<img width="687" height="121" alt="Screenshot 2026-05-26 114401" src="https://github.com/user-attachments/assets/b1ceccb4-4494-452e-9309-876ef7afc75d" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="835" height="53" alt="Screenshot 2026-05-26 114408" src="https://github.com/user-attachments/assets/87791dc1-c841-4cd7-91ca-b181eb24baec" />


## COMMAND AND OUTPUT


Create the file Rose.txt
<img width="646" height="110" alt="Screenshot 2026-05-26 114519" src="https://github.com/user-attachments/assets/c518f34b-444c-4a0f-bdad-30ae205edb58" />

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection
<img width="832" height="118" alt="Screenshot 2026-05-26 114456" src="https://github.com/user-attachments/assets/fe6944bb-24f5-48e1-a0e7-a4c2df96dc61" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="699" height="66" alt="Screenshot 2026-05-26 114503" src="https://github.com/user-attachments/assets/accc152c-56e4-4631-bed6-7940160b7afd" />

## COMMAND AND OUTPUT

Remove the file hello1.txt

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="780" height="668" alt="Screenshot 2026-05-26 114510" src="https://github.com/user-attachments/assets/2c5a3137-15cc-46a0-a1f2-377b6c5da279" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
<img width="646" height="110" alt="Screenshot 2026-05-26 114519" src="https://github.com/user-attachments/assets/87c3be47-40b2-4f4d-9ebd-a2b09266f9f0" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="653" height="176" alt="image" src="https://github.com/user-attachments/assets/b683be88-51f2-4208-bec9-e0f5989df8ac" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="441" height="186" alt="image" src="https://github.com/user-attachments/assets/8d1a19af-3520-4bfa-bb72-ceeb185b8094" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="458" height="77" alt="image" src="https://github.com/user-attachments/assets/d4c6bc17-bf1b-4044-a5c2-22befc37d91b" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="458" height="77" alt="image" src="https://github.com/user-attachments/assets/110c828f-2b56-4f7e-933c-c1932842e2a1" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="452" height="172" alt="image" src="https://github.com/user-attachments/assets/85e7ca12-b771-4529-a259-46ffbb8f9b3c" />


# RESULT:
The commands/batch files are executed successfully.

