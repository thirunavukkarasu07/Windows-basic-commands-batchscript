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


![Screenshot 2025-05-27 083726](https://github.com/user-attachments/assets/ec3af740-1dd5-41de-b5d8-c87c1c635f49)



## COMMAND AND OUTPUT

Remove the directory "my-folder"

![Screenshot 2025-05-27 083726](https://github.com/user-attachments/assets/7abdc357-7b54-4621-b4cd-ccfc34039d6a)


## COMMAND AND OUTPUT


Create the file Rose.txt


![Screenshot 2025-05-27 083726](https://github.com/user-attachments/assets/4fffab21-7f37-41d0-a1de-9f1628c8f6cd)


![Screenshot 2025-05-27 083803](https://github.com/user-attachments/assets/6581c30e-d8e4-41ee-bd32-27b23c3c0ee5)



## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection


![Screenshot 2025-05-28 172901](https://github.com/user-attachments/assets/5316977e-0421-4f2e-8603-3448d4d4cda8)



## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt


![Screenshot 2025-05-28 172901](https://github.com/user-attachments/assets/f5bbb5ce-a491-4da4-a11e-0f4893d51eeb)


## COMMAND AND OUTPUT

Remove the file hello1.txt



![Screenshot 2025-05-28 172901](https://github.com/user-attachments/assets/840fe17c-1838-4420-8516-f60e7017ec94)




## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

List out all the associated file extensions 



![Screenshot 2025-05-28 172901](https://github.com/user-attachments/assets/850bebb3-ec48-408c-a793-406e54ac07a6)




## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt




![Screenshot 2025-05-28 173131](https://github.com/user-attachments/assets/313bd046-0dc4-4dbd-8ec0-efa6789e193e)




## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT






![Screenshot 2025-05-28 173244](https://github.com/user-attachments/assets/c35778d0-1771-4aca-bdfc-da3ff33b93ab)





![Screenshot 2025-05-28 173613](https://github.com/user-attachments/assets/7b233be7-c67c-40f9-aff9-1dca3db99b73)





Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT



![Screenshot 2025-05-28 173822](https://github.com/user-attachments/assets/2573c6ec-5c2b-4942-99f0-49db7af0c1e6)





![Screenshot 2025-05-28 173858](https://github.com/user-attachments/assets/98e23462-5e58-41dd-a4b0-1e8399facb15)

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




![Screenshot 2025-05-28 174118](https://github.com/user-attachments/assets/4a7b2830-33e2-49fd-83f8-19e87489331c)




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT






![Screenshot 2025-05-28 174306](https://github.com/user-attachments/assets/d9ef730f-0969-447b-bb2a-eee25cb9bc12)






Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



![Screenshot 2025-05-28 174610](https://github.com/user-attachments/assets/7e5292b8-5deb-423d-b538-bbf7c23e7a74)




# RESULT:
The commands/batch files are executed successfully.

