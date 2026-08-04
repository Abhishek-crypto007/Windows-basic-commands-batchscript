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

<img width="1269" height="538" alt="image" src="https://github.com/user-attachments/assets/00fbe915-495c-4c8d-a6c2-6b3da48dcfe6" />


Remove the directory "my-folder"

<img width="831" height="82" alt="image" src="https://github.com/user-attachments/assets/1a3c775a-e89c-44a1-82bb-62f6b2d881cd" />



Create the file Rose.txt

<img width="1754" height="372" alt="image" src="https://github.com/user-attachments/assets/622c5e4f-76f5-46c5-b451-9d6a198fd070" />



Create the file hello.txt using echo and redirection

<img width="1754" height="118" alt="image" src="https://github.com/user-attachments/assets/be6ff521-b6ea-4945-9d72-ed9143e4b414" />


Copy the file hello.txt into the file hello1.txt
<img width="1754" height="130" alt="image" src="https://github.com/user-attachments/assets/2aed7cdc-fa82-4e0a-b156-d4871d6863dc" />


Remove the file hello1.txt
<img width="1754" height="222" alt="image" src="https://github.com/user-attachments/assets/f5312925-1f17-45e2-9b55-b489dbbecf58" />

List out the file hello1.txt in the current directory

<img width="1442" height="775" alt="image" src="https://github.com/user-attachments/assets/ec7822b8-6689-4aa4-b1fc-fc969829a748" />


List out all the associated file extensions 

<img width="1526" height="845" alt="image" src="https://github.com/user-attachments/assets/c0da6273-022a-4002-b5b1-1bd400b5cdb7" />

### Compare the file hello.txt and rose.txt
<img width="686" height="157" alt="image" src="https://github.com/user-attachments/assets/27de5fc2-979c-492c-9357-e310877e29bb" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT
<img width="1110" height="90" alt="image" src="https://github.com/user-attachments/assets/d1391b2a-2524-4546-a6bf-483b494c49b2" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="750" height="263" alt="image" src="https://github.com/user-attachments/assets/efb6f50b-051a-4989-846e-6f74587a9ff4" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="868" height="145" alt="image" src="https://github.com/user-attachments/assets/27c7eba5-416a-458f-bf85-f42e48902ef9" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="871" height="77" alt="image" src="https://github.com/user-attachments/assets/606aea09-0b4c-4e04-ba28-b78cdfa14e0c" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="1192" height="310" alt="image" src="https://github.com/user-attachments/assets/f10346a0-c672-4e9e-9387-a6f9db5eef61" />


# RESULT:
The commands/batch files are executed successfully.

