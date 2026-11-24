# Mission 2 - Become comfortable with the Terminal

Note: I used an AI assistant to help me understand this mission and draft some of the wording. I ran all the commands on my own computer.

## 1. Task / objective
To practise basic Terminal commands, manage files safely inside my project folder, and understand flags, pipes and package managers.

## 2. Work completed
I ran basic commands to see where I was and list files, created a practice folder and files, copied and renamed a file, and added text to a file without replacing it. I also compared normal and detailed listings, used a pipe, and checked for a package manager.

## 3. Commands / tools used
pwd, ls, ls -l, ls -la, cd, mkdir, touch, cp, mv, cat, echo, head, brew --version. I used the Terminal in VS Code.

## Task 2.1 - Basic Terminal operations

| Operation | Command | What it does | What I observed |
|---|---|---|---|
| Current directory | pwd | Shows the full path of the folder I am in | OBSERVE |
| Directory listing | ls | Lists the files and folders here | OBSERVE |
| Detailed listing | ls -l | Lists them with details like size and date | OBSERVE |
| Change directory | cd .. | Moves up to the parent folder | OBSERVE |
| Create directory | mkdir terminal-practice | Makes a new folder | OBSERVE |
| Create empty file | touch terminal-practice/notes.txt | Makes an empty file | OBSERVE |
| Copy file | cp ... notes-copy.txt | Makes a copy with a new name | OBSERVE |
| Move / rename file | mv ... notes-renamed.txt | Renames the copy | OBSERVE |
| Display file contents | cat terminal-practice/notes.txt | Prints what is inside the file | OBSERVE |

## Task 2.2 - Safe file changes
I made a folder called terminal-practice-2 with notes.txt, wrote "first line" with >, then added "second line" with >>. I displayed the file to confirm both lines were there, made a backup copy and renamed it.

- Replacing vs adding: > replaces everything in the file, while >> adds to the end and keeps the old text.
- Copying vs moving: cp leaves the original and makes a second file. mv moves or renames, so there is still only one file.
- pwd tells me exactly where I am in the folder structure.
- ls is useful because it shows me what is in a folder so I can check my work.

## Task 2.3 - Flags and pipes
- ls shows normal files. ls -la also shows hidden files (names starting with a dot) and details like permissions, size and date. WRITE: one thing you noticed in your own output.
- The | (pipe) takes the output of the command on its left and gives it to the command on its right. In ls -l | head -n 3, ls -l makes the list and head shows only the first 3 lines.

## Task 2.4 - Package managers
I ran brew --version on my Mac and it showed: Homebrew 7.0.7. This means Homebrew is already installed. I did not install or uninstall anything, as the assignment said.

A package manager helps install, update and remove software from one place, and it can check which version is installed. This saves time and avoids downloading things manually from random websites.

## 4. My understanding
In the Terminal I can check where I am with pwd, see what is in a folder with ls, and move between folders with cd. I can create folders with mkdir and empty files with touch, then copy them with cp or rename them with mv. I learned that > replaces what is in a file while >> adds to the end, and that a pipe (|) sends the output of one command into another. The most useful thing for me was being able to create and organise files quickly without clicking around.

## 5. Difficulties faced
No major difficulties.

## 6. How I resolved them
Not applicable.

## 7. Evidence / files
- terminal-practice/ (with notes.txt and notes-renamed.txt)
- terminal-practice-2/ (with notes.txt and notes-backup-renamed.txt)

## 8. Commit details
- Commit message: "Complete Terminal and file management mission"
- Pushed to my public GitHub repository and confirmed it is visible.