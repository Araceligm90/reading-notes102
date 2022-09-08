# The Terminal

### What is the terminal? ###

The command line, most commonly known as *the terminal*, is a text based interface to your computer´s system. You can enter commands by typing them and an answer or output will be given to you in a text form underneath the command. 

When you open your computer's terminal, you will be presented with a prompte. E.g. 

    Aracelis-Air:~ araceligarcia$
    
Once you are there, you can enter a command. 

**Basic commands:**

1. pwd (print working directory): this command does just that. It tells you your current or present working directory or folder. E.g.

     /Aracelis-Air:~ araceligarcia$ pwd
    
2. ls (list): this command will tell you what is in your current location. E.g.

    Aracelis-Air:~ araceligarcia$ ls
   
    Applications	Documents	Movies		Public
 
 3. -l after the ls commands for a longer list of what has been shown. This will also give you additional information about the folders or directories. E.g.
 
    Aracelis-Air:~ araceligarcia$ ls -l
    total 0
    drwx------@   3 araceligarcia  staff    96 Nov 20  2020 Applications
    etc.
    Aracelis-Air:~ araceligarcia$ 
    
4. /etc is a command line argument that will tell ls not to list the current directory but to list the directories' content instead. 

    Aracelis-Air:~ araceligarcia$ ls /etc

