# Command Line Practice Exercises

These exercises will help you learn basic command line operations. For each task, try to figure out the correct command. If you need help, click the hint dropdown below the task. You can actually also practice these commands in the terminal on your own machine.

## Starting State
```
home/
└── user/             # You start here
```

Each task below will modify this structure. Watch how it grows!

## Task 1: Create a Directory
Create a new directory called "practice_folder"

After this task:
```
home/
└── user/
    └── practice_folder/     # New directory created
```

<details>
<summary>💡 Hint</summary>
Use the `mkdir` command to create a new directory.
</details>

Answer: 

## Task 2: Navigate Directories
Navigate into the practice_folder directory

After this task:
```
home/
└── user/
    └── practice_folder/     # You are now here
```

<details>
<summary>💡 Hint</summary>
Use the `cd` command to change directories.
</details>

Answer: 

## Task 3: Check Your Location
Display your current working directory path to confirm you're in the right place

<details>
<summary>💡 Hint</summary>
The `pwd` command will show your current directory path.
</details>

Answer: 

## Task 4: Create a File with Content
Create a text file called "notes.txt" and write "Hello World" into it

After this task:
```
home/
└── user/
    └── practice_folder/     # You are here
        └── notes.txt        # New file with "Hello World"
```

<details>
<summary>💡 Hint</summary>
Use `echo "Hello World" > notes.txt` to create and write to a file.
</details>

Answer: 

## Task 5: View File Contents
Display the contents of notes.txt

<details>
<summary>💡 Hint</summary>
The `cat` command will show you the contents of a file.
</details>

Answer: 

## Task 6: Create Another Directory
Create another directory inside practice_folder called "backup"

After this task:
```
home/
└── user/
    └── practice_folder/     # You are here
        ├── backup/          # New directory
        └── notes.txt
```

<details>
<summary>💡 Hint</summary>
Use `mkdir` again to create the backup directory.
</details>

Answer: 

## Task 7: Copy Files
Copy notes.txt into the backup directory

After this task:
```
home/
└── user/
    └── practice_folder/     # You are here
        ├── backup/
        │   └── notes.txt    # Copied file
        └── notes.txt        # Original file
```

<details>
<summary>💡 Hint</summary>
The `cp` command copies files from one location to another.
</details>

Answer: 

## Task 8: List Directory Contents
List all contents of your current directory to confirm you see both the file and the backup folder

<details>
<summary>💡 Hint</summary>
The `ls` command lists directory contents.
</details>

Answer: 

## Task 9: Rename Files
Move notes.txt to a new name called important_notes.txt

After this task:
```
home/
└── user/
    └── practice_folder/     # You are here
        ├── backup/
        │   └── notes.txt
        └── important_notes.txt    # Renamed from notes.txt
```

<details>
<summary>💡 Hint</summary>
The `mv` command can rename files.
</details>

Answer: 

## Task 10: View File Preview
Display the first 10 lines of important_notes.txt

<details>
<summary>💡 Hint</summary>
The `head` command shows the beginning of a file.
</details>

Answer: 

---

## Solutions

<details>
<summary>🔍 Click here to see all solutions</summary>

1. `mkdir practice_folder`
2. `cd practice_folder`
3. `pwd`
4. `echo "Hello World" > notes.txt`
5. `cat notes.txt`
6. `mkdir backup`
7. `cp notes.txt backup/`
8. `ls`
9. `mv notes.txt important_notes.txt`
10. `head important_notes.txt`

</details>