# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.
```
mkdir %sec%\Desktop\MyLab
```
![alt text](image.png)

## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
```
cd %sec%\Desktop\MyLab
touch MyFile.txt
```
![alt text](image-1.png)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
dir %sec%\Desktop\MyLab
```
![alt text](image-2.png)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
mkdir %sec%\Desktop\Backup
cp MyFile.txt %sec%\Desktop\Backup
```
![alt text](image-3.png)
![alt text](image-4.png)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
```
mv MyFile.txt MyLab\Documents
```
![alt text](image-5.png)

## COMMAND AND OUTPUT


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

### BackupScript.bat
```
@echo off
mkdir %sec%\Desktop\DocBackup
copy %sec%\Documents\*.docx %sec%\Desktop\DocBackup
del %sec%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!
```




## OUTPUT

![alt text](image-6.png)



# RESULT:
The commands/batch files are executed successfully.

