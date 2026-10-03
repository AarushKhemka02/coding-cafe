# Coding Café - Lab 1 Notes

## Question 1
`pwd` printed:

/Users/shivanikhemka

This is the path of my home directory.

## Question 2
`ls -a` showed hidden files and folders that plain `ls` did not show. These are files whose names begin with a `.` such as `.zshrc` and `.gitconfig`.

## Question 3
The first column in the output of `ls -l` represents the file type and its permissions. For example, `drwx------` shows that the item is a directory and indicates which users can read, write, or execute/access it.

## Question 4
The command `ls coding-cafe/week02` works because `coding-cafe/week02` is a relative path. I was standing in my home directory, where the `coding-cafe` folder exists, so the terminal could follow the path from my current location to the `week02` folder.

## 5 
The first `mv` command moved README-backup.md from the coding-cafe folder into week01. The second `mv` command renamed README-backup.md to old-readme.md.

## 6. 
There are 11 folders/directories on my PATH.

## 7. 
My python3 is located at:
/Library/Frameworks/Python.framework/Versions/3.14/bin/python3

## 8. 
My python3 path may be different from someone else's because different computers can have different Python installations and different PATH configurations.

## 9. 
The shell said "command not found" because it searched through all the directories listed in my PATH for the command I typed, but could not find a matching executable there. In this case, the command also contained a typo.

## 10.
 venv did not appear with plain ls because files and folders that start with a . are hidden. Plain ls does not show hidden files, but ls -a does.

## 11. 
After activating the virtual environment, (.venv) appeared at the beginning of my terminal prompt.

## 12.
  No, it was not the same path. Before activating the virtual environment, python3 pointed to:
   /Library/Frameworks/Python.framework/Versions/3.14/bin/python3
    After activating .venv, it pointed to:
    /Users/shivanikhemka/coding-cafe/.venv/bin/python3
    This shows that activating the virtual environment changed the PATH so that the .venv/bin folder is searched before the system Python location.

## 13.
The second list contained these new packages:
    certifi
    charset-normalizer
    idna
    requests
    urllib3
    These were not in the first list. requests was the package I installed, and the others were installed along with it as dependencies.

## 14.

After deactivating the virtual environment, python3 pointed to:
/Library/Frameworks/Python.framework/Versions/3.14/bin/python3

This is the system Python location instead of the Python inside the .venv folder.

## 15.
The ls -h command makes file sizes easier for humans to read by displaying them using units such as Bytes, KB, MB, GB, etc.

## 16.
Ctrl + C interrupts and stops the program that is currently running. Ctrl + D sends an end-of-file (EOF) signal, which can exit programs like Python when they are waiting for input.