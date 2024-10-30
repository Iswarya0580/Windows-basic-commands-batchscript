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

## COMMAND AND OUTPUT

mkdir %userprofile%\Desktop\MyLab



![image](https://github.com/user-attachments/assets/39147a55-da23-4c2a-8137-f619f868e1d2)

## COMMAND AND OUTPUT

cd %userprofile%\Desktop\MyLab




![image](https://github.com/user-attachments/assets/394a609d-c8a7-479b-b4c7-afd6ab6c2eb4)

## COMMAND AND OUTPUT

type nul > MyFile.txt



![image](https://github.com/user-attachments/assets/35857c9c-635c-42e5-b495-8b51fd07bb2e)

## COMMAND AND OUTPUT

dir %userprofile%\Desktop\MyLab



![image](https://github.com/user-attachments/assets/93fba9c5-208d-45f5-b37c-b7f5dff807d8)


## COMMAND AND OUTPUT

mkdir %userprofile%\Desktop\Backup



![image](https://github.com/user-attachments/assets/b0b44447-3cc5-4f07-b0e0-28815fd39a35)

## COMMAND AND OUTPUT
copy MyFile.txt %userprofile%\Desktop\Backup



![image](https://github.com/user-attachments/assets/a7b3289e-1e21-4180-b42e-47786b790df0)

## COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\Documents



![image](https://github.com/user-attachments/assets/28525f78-09a3-4235-90c6-5affed248168)

move MyLab Documents

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```

## OUTPUT
![image](https://github.com/user-attachments/assets/dbef6537-7a1d-486f-a75e-a1978b8f7e7d)

## COMMAND
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```

## OUTPUT
![image](https://github.com/user-attachments/assets/bcbe4d38-fa25-4891-8c8b-e53839d79edc)

# RESULT:
The commands/batch files are executed successfully.

