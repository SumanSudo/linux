# 📘 Basic Linux Commands

This file contains essential Linux commands for navigation and file/directory handling.

---

## 🔹 1. pwd (Print Working Directory)

**Description:**
Shows the current directory path.

**Syntax:**
pwd

**Example Output:**
/home/suman

---

## 🔹 2. ls (List Files)

**Description:**
Lists files and directories in the current location.

**Syntax:**
ls [options]

**Common Usage:**
ls # basic list
ls -l # detailed list
ls -a # hidden files
ls -la # detailed + hidden

---

## 🔹 3. cd (Change Directory)

**Description:**
Used to navigate between directories.

**Syntax:**
cd [directory]

**Examples:**
cd folder_name # go inside folder
cd .. # move one level up
cd ~ # go to home directory
cd / # go to root directory

---

## 🔹 4. mkdir (Make Directory)

**Description:**
Creates a new directory (folder).

**Syntax:**
mkdir directory_name

**Examples:**
mkdir test
mkdir my_folder

---

## 🔹 5. touch (Create File)

**Description:**
Creates a new empty file.

**Syntax:**
touch file_name

**Examples:**
touch file.txt
touch app.js

---

## 🔹 6. rm (Remove Files / Directories)

**Description:**
Deletes files or directories.

**Syntax:**
rm file_name
rm -r directory_name

**Examples:**
rm file.txt # delete file
rm -r test_folder # delete folder

⚠️ Warning:
Deleted files cannot be easily recovered.

---

## 🔹 7. clear (Clear Terminal)

**Description:**
Clears the terminal screen.

**Syntax:**
clear

---

## 🔹 8. cat (View File Content)

**Description:**
Displays the content of a file.

**Syntax:**
cat file_name

**Examples:**
cat file.txt

---

## 🔹 9. echo (Print / Write Text)

**Description:**
Prints text to terminal or writes into a file.

**Syntax:**
echo "text"

**Examples:**
echo "Hello World"

echo "Hello World" > file.txt # overwrite file
echo "New Line" >> file.txt # append to file

---

## 🔹 10. nano (Edit File)

**Description:**
Opens a file in a simple text editor.

**Syntax:**
nano file_name

**Examples:**
nano file.txt

---

## 🔹 11. cp (Copy Files / Directories)

**Description:**
Copies files or directories from one location to another.

**Syntax:**
cp source destination

**Examples:**
cp file.txt copy.txt # copy file
cp -r folder1 folder2 # copy folder

---

## 🔹 12. mv (Move / Rename Files)

**Description:**
Moves or renames files and directories.

**Syntax:**
mv source destination

**Examples:**
mv file.txt newfile.txt # rename file
mv file.txt /home/user/ # move file
mv folder1 folder2 # rename folder

---

## 🔹 13. ls -l (View File Permissions)

**Description:**
Shows detailed file information including permissions.

Example:
ls -l

---

##🔹 14. File Permissons
Types of permissions:
r -> read
w -> write
x -> execute

Permission Groups:
Owner
Group
Others

---

## 🔹 15. chmod (Chnage Permissions)

**Description**

Syntax:
chmod permissions file_name---

Examples (symbolic):
chmod +x file.sh # add execute permission
chmod -w file.txt # remove write permission

Examples (numeric):
chmod 755 file.sh

Meaning of 755:

7 → rwx (owner)
5 → r-x (group)
5 → r-x (others)

---

# 📌 Notes

- Linux is case-sensitive
- Use `Tab` for auto-completion
- Use ↑ ↓ keys for command history
