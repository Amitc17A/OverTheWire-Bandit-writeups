# Level 0 → Level 1

## 🎯 Level Goal 
Log into the Bandit wargame server for the  first time using SSH to retrieve the password for the next level.

## Prerequisites
* **Target Host:** `bandit.labs.overthewire.org`
* **Port:** `2220`
* **Username:** `bandit0`
* **Password:** `bandit0`
* **Tools Needed:** Terminal (Linux/macOS) or PowerShell / Git Bash / WSL (Windows)

## ✅Solution
 ### Step 1: Open Your Terminal & Connect via SSH 
 ```Bash
   ssh bandit0@bandit.labs.overthewire.org -p 2220
 ```
### Step 2: Enter Password
`bandit0`

### Step 3: Read The Password File
By using `ls` command  list files & Directory

Read the file 
```bash 
cat readme
 ```
### Step 4: Save The Password and Exit
Save the Password in file and Then Exit
```bash
exit
```
## 🗝️Password For Next Level
```bash
6y2kwnwK6grgvwvpvLaa2T1cpFEKOhNR
```

### 📸Screenshot

