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
.

## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
````````````````
mkdir ~/Desktop/MyLab
``````````````````````````````
![image](https://github.com/vinodhini-17/Windows-basic-commands-batchscript/assets/145742741/4ddbe858-0ada-4bbd-a1e0-91ff27204d35)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
`````
ls
````````````
![image](https://github.com/vinodhini-17/Windows-basic-commands-batchscript/assets/145742741/45f14fe1-b838-46d7-b602-2cb027874d85)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
``````
cp ~/Desktop/MyLab/* ~/Desktop/Backup/
``````````````````
![image](https://github.com/vinodhini-17/Windows-basic-commands-batchscript/assets/145742741/67f38186-230f-4418-b495-3233752a1999)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

  ````````````
cd
cd ~/Documents
`````````````````````
![image](https://github.com/vinodhini-17/Windows-basic-commands-batchscript/assets/145742741/10ee0887-afa6-47a1-a699-7d707c083db3)

## COMMAND AND OUTPUT
``````````
mv ~/Desktop/MyLab/MyFile.txt ~/Desktop/Backup/
``````````````````
![image](https://github.com/vinodhini-17/Windows-basic-commands-batchscript/assets/145742741/54dbe662-8814-4f9d-b398-eb17a081e694)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


````````
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\DocBackup\*.docx
echo Backup and deletion completed successfully!
```````````````````````




## OUTPUT
![image](https://github.com/vinodhini-17/Windows-basic-commands-batchscript/assets/145742741/6bca819f-f598-4d2d-8be2-29a4efe6d802)





# RESULT:
The commands/batch files are executed successfully.

