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
<img width="861" height="101" alt="image" src="https://github.com/user-attachments/assets/5f49eba0-4213-4f50-bd3b-4599b1db9e8a" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="939" height="105" alt="image" src="https://github.com/user-attachments/assets/5ac59a26-45d9-4e9e-b487-1f19057d79a4" />

## COMMAND AND OUTPUT


Create the file Rose.txt
<img width="976" height="65" alt="image" src="https://github.com/user-attachments/assets/ccec716d-7b78-4069-8db1-c120c54885cc" />

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection
<img width="1063" height="36" alt="image" src="https://github.com/user-attachments/assets/f8043d90-54b6-4661-98ff-fc30883fa267" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="990" height="115" alt="image" src="https://github.com/user-attachments/assets/d2cf642f-ed29-46ed-91cf-2e1b0c76e91b" />

## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="848" height="85" alt="image" src="https://github.com/user-attachments/assets/b6173983-5f80-48c6-9764-cf8ebfb43230" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
<img width="944" height="184" alt="image" src="https://github.com/user-attachments/assets/0fedf554-5579-4c05-8c2d-e490ff2a564f" />

## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="788" height="1064" alt="image" src="https://github.com/user-attachments/assets/1ce92bf5-dd9b-44d0-b861-bbac35f64a96" />

<img width="1059" height="1089" alt="image" src="https://github.com/user-attachments/assets/0740d1a5-0fbd-4b92-b4cc-5d1a2a543f90" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
<img width="948" height="161" alt="image" src="https://github.com/user-attachments/assets/b07046b0-557a-4952-80b3-730334032486" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="510" height="97" alt="image" src="https://github.com/user-attachments/assets/5d456cc1-9771-4e71-a1e1-c9e3244dcafd" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="591" height="231" alt="image" src="https://github.com/user-attachments/assets/7c79880c-5cc2-4c1a-b8be-3c2e887eb5fd" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="433" height="197" alt="image" src="https://github.com/user-attachments/assets/c096470c-23c7-4d34-a90a-0d2b1211ea66" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="412" height="62" alt="image" src="https://github.com/user-attachments/assets/61744ce4-8251-40b8-96c7-eeaded51eb64" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="380" height="159" alt="image" src="https://github.com/user-attachments/assets/c022d810-d650-4895-ab09-67041caec33b" />



# RESULT:
The commands/batch files are executed successfully.

