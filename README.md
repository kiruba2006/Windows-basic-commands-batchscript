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
![Screenshot 2025-05-28 234428](https://github.com/user-attachments/assets/beae5e09-005a-436a-a6cb-9e16eede3361)


## COMMAND AND OUTPUT

Remove the directory "my-folder"
![Screenshot 2025-05-28 234428](https://github.com/user-attachments/assets/b4eccd80-85fc-4427-96a7-c7fa92daa692)

## COMMAND AND OUTPUT


Create the file Rose.txt
![Screenshot 2025-05-28 234428](https://github.com/user-attachments/assets/fc21fe22-ddd3-4e87-a26f-f1ef27794074)
![Screenshot 2025-05-28 234530](https://github.com/user-attachments/assets/e3e1c66d-9853-4e0f-9b82-bfe27c9be982)

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection
![Screenshot 2025-05-28 235001](https://github.com/user-attachments/assets/924f17d0-96b3-44f3-884a-f37c228bc153)


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
![Screenshot 2025-05-28 235001](https://github.com/user-attachments/assets/7cd3575b-275c-4e4a-9447-e987162cf772)

## COMMAND AND OUTPUT

Remove the file hello1.txt
![Screenshot 2025-05-28 235001](https://github.com/user-attachments/assets/f8afbfa8-f0db-408e-b42c-ee02ba546b03)

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
![Screenshot 2025-05-28 235001](https://github.com/user-attachments/assets/1ba0d1fa-8c77-4a16-ba3e-5a500d9d55d8)

## COMMAND AND OUTPUT

List out all the associated file extensions 
![Screenshot 2025-05-28 235001](https://github.com/user-attachments/assets/12147039-5429-4e5f-94f0-28dd8bec946f)

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
![Screenshot 2025-05-28 235152](https://github.com/user-attachments/assets/6ba80407-a561-4ff6-9230-3d52dcd6c4ce)

## COMMAND AND OUTPUT
![Screenshot 2025-05-28 235308](https://github.com/user-attachments/assets/4d6df889-9e20-4c3b-85ee-67d59637a0ac)

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
![Screenshot 2025-05-28 235544](https://github.com/user-attachments/assets/dfc56806-0405-4ef2-8ae2-07882ba54faf)

![Screenshot 2025-05-28 235551](https://github.com/user-attachments/assets/cb75e69a-e43b-4e56-8d75-67c1abac0ac7)


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

![Screenshot 2025-05-29 000008](https://github.com/user-attachments/assets/bde91bb4-6055-4f5a-bb4d-dd85063360e7)

![Screenshot 2025-05-29 000017](https://github.com/user-attachments/assets/7e3b515c-02d3-48dd-a825-a8901cd195cd)


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

![Screenshot 2025-05-29 000055](https://github.com/user-attachments/assets/4ad61ec0-af90-44ed-8141-159fe7ae58a1)



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

![Screenshot 2025-05-29 000114](https://github.com/user-attachments/assets/24822663-506f-423f-9b54-8e1314ebe165)

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

![Screenshot 2025-05-29 000146](https://github.com/user-attachments/assets/37f5d92c-8260-4de6-951f-207d24e8667b)


# RESULT:
The commands/batch files are executed successfully.

