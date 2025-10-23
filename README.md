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

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\MyLab
```
<img width="772" height="48" alt="445703244-67d57631-ab66-4d22-a146-8115a2e3c0f4" src="https://github.com/user-attachments/assets/9195b904-3c91-4b4c-a450-ce386a0ce60a" />

## COMMAND AND OUTPUT
```
cd %userprofile%\Desktop\MyLab
```
<img width="763" height="117" alt="445703361-6a1baf0b-2a0f-4dc2-b4c0-6da8d2fe315d" src="https://github.com/user-attachments/assets/d44117bf-a7eb-4ae2-8b56-c0ee3358da5a" />

## COMMAND AND OUTPUT
```
type nul > MyFile.txt
```
<img width="775" height="106" alt="445703809-0d23b56d-83f1-4e68-adb4-ae3070678ba0" src="https://github.com/user-attachments/assets/9a80bbe1-41a5-4b88-b040-6b28f96e04c6" />

## COMMAND AND OUTPUT
```
dir %userprofile%\Desktop\MyLab
```
<img width="775" height="309" alt="445703997-0611f82e-d1ac-4b1d-9a41-731ffdcb67f9" src="https://github.com/user-attachments/assets/72e56153-fba2-4a76-a8d6-0b96215f0d63" />

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup
```
<img width="778" height="95" alt="445704243-00649aa1-e258-434c-bdc2-0ce6d179002d" src="https://github.com/user-attachments/assets/9f4b6912-a31f-4ef1-8bba-dcdc5cdf381c" />

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup
```
<img width="769" height="115" alt="445704416-99132b9c-85df-4396-8b03-7a0b2645ef0a" src="https://github.com/user-attachments/assets/3232747e-ab71-4eea-a150-c68c95bf810a" />

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Documents
move MyLab Documents
```
<img width="775" height="118" alt="445704666-6f9b1899-fd65-445c-9c2e-ffba94e00cfe" src="https://github.com/user-attachments/assets/3b3d8e27-7a43-476e-b93a-629efc853b7f" />


## COMMAND AND OUTPUT
List out all the associated file extensions

## COMMAND AND OUTPUT
Compare the file hello.txt and rose.txt

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
<img width="770" height="201" alt="445704927-46d023d2-940c-4839-a208-3eefc012d8df" src="https://github.com/user-attachments/assets/6656ea40-e63f-4fd8-99da-910d33b1ba42" />

## OUTPUT
```
  @echo off
  mkdir %userprofile%\Desktop\DocBackup
  copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
  del %userprofile%\Documents\*.docx
  echo Backup and deletion completed successfully!
```
<img width="778" height="196" alt="445705011-28aa0f55-9265-4f30-a30d-76685778ae97" src="https://github.com/user-attachments/assets/3e4b69ec-7590-4896-822e-97039687fbb0" />

# RESULT:
The commands/batch files are executed successfully.

