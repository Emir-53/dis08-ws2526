# Linux Journey Quiz Answers

## Question 1
**What is the exact output to the display when you type `echo Hello World`?**  
Answer:  
Hello World

echo Hello World

Output:
Hello World

text

---

## Question 2
**How do I find what directory you are currently in?**  
Answer:  
Use the `pwd` command to print the current working directory.

pwd

Output:
/home/username

text

---

## Question 3
**If you are in `/home/pete/Pictures` and wanted to go to `/home/pete`, what’s a good shortcut to use?**  
Answer:  
Use `cd ..` to move to the parent directory.

cd ..

Now in /home/pete
text

---

## Question 4
**What command would you use to see hidden files?**  
Answer:  
Use `ls -a` to list all files, including hidden ones (those starting with a dot).

ls -a

Output: . .. .hiddenfile visiblefile
text

---

## Question 5
**How do you create a file called `myfile`?**  
Answer:  
Use the `touch` command to create an empty file.

touch myfile

text

---

## Question 6
**What command can you use to find the file type of a file?**  
Answer:  
Use the `file` command followed by the filename.

file myfile

Output: myfile: empty
text

---

## Question 7
**What's a good way to see the contents of a file?**  
Answer:  
Use the `cat` command to display the file content.

cat myfile

Output: (file contents)
text

---

## Question 8
**How do you quit out of a `less` command?**  
Answer:  
Press `q` to quit less.

---

## Question 9
**What is the command to clear the terminal?**  
Answer:  
Use the `clear` command.

clear

text

---

## Question 10
**What flag do you need to specify to copy over a directory?**  
Answer:  
Use the `-r` flag with `cp` for recursive copy.

cp -r sourcedir targetdir

text

---

## Question 11
**How do you rename a file called `cat` to `dog`?**  
Answer:  
Use the `mv` command.

mv cat dog

text

---

## Question 12
**What command is used to make a directory?**  
Answer:  
Use `mkdir`.

mkdir mydir

text

---

## Question 13
**How do you remove a file named `myfile`? Your answer must be in English and use the exact, case-sensitive command.**  
Answer:  
Use `rm myfile`.

rm myfile

text

---

## Question 14
**What option should I specify for `find` if I want to search by name?**  
Answer:  
Use `-name`.

find . -name "filename"

text

---

## Question 15
**How do you get quick command-line help for built-in Bash commands?**  
Answer:  
Use the `help` command.

help cd

text

---

## Question 16
**How do you see the manuals for a command?**  
Answer:  
Use the `man` command.

man ls

text

---

## Question 17
**What command can you use to see a small description of a command?**  
Answer:  
Use the `whatis` command.

whatis ls

Output: ls (1) - list directory contents
text

---

## Question 18
**What command is used to make an alias?**  
Answer:  
Use the `alias` command.

alias ll='ls -l'

text

---

## Question 19
**How can you exit from the shell?**  
Answer:  
Use the `exit` command.

exit
