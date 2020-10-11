#### Command Line

The command line is an essential tool for software development.
By using commands, you can execute a wide variety of programs on your computer.
Let's learn the fundamental UNIX commands necessary for development


- The command line is a tool for interacting with a computer using only text (also known as a text interface) rather
than other methods like clicking and scrolling. Let's learn these skills thoroughly because they are essential for developing 
websites and applications! **UNIX** command is a type of command that is used in Linux and macOS. Works in Git also



- you can give instructions to the computer by entering commands into what is called a terminal.
Let's start looking at what kind of commands there are in the next slides. There is no need to write $, since it is a symbol often used to 
signify where you can begin typing in commands.

- First, let's look at the command for creating new files, the `touch` command. You can create an empty file by typing "touch file_name" and executing it.


- You can create a new directory using a command as well. A directory is commonly used interchangeably with the term folder. To create a directory, use the mkdir command as follows: mkdir directory_name.

- You can use the cd command to move to other directories.
By entering cd directory_name, you can move to the specified directory.


- In the file structure of a computer, there is a root directory at the very top. The root directory is represented by /.

- On the command line, it is important to know the directory you are currently working in. There is a command called pwd to check that.
When you execute the pwd command as shown below, all directories from the root directory to the current directory are displayed.

- When moving between directories, it would be convenient if we could see the list of files and directories in the current directory.
To do this, you can use the ls command as shown below.

- Note that the ls command will only display the directories and files that are direct children of the current directory.

- We've learned how to use the cd command, but we don't know how to move to the parent directory yet.
If you want to move to the parent directory, you can use a special symbol .., like `cd ..`.

- If you execute cd without specifying a directory, you can move to what is called a home directory.
The home directory is represented by ~ like in the image below.

- The Home directory refers to the base directory for the user.
Since it is important, moving to the home directory is made to be easy.


- Let's start with the command to move a file.
To do this, we use the mv command.
By typing "mv file_to_move destination_directory", you can move a file to the specified directory.


- With the mv command, you can also move directories, not just files.
By entering "mv directory_to_move destination_directory", you can move all the files and directories under that directory.

- The mv command, which we used to move files and directories earlier, can also be used to rename a file.
You can rename a file by typing "mv old_file_name new_file_name."

- Next, let's look at how to copy files.
To do this, we use the cp command.
You can copy a file by entering "cp file_to_copy new_file_name".


- With the cp command, you can also copy a directory by adding the -r (Recursive copy) option, like "cp -r directory_to_copy new_directory_name".


- If you try to copy a directory without adding the -r option, you will get an error and the command will not be executed.


- Next, we'll look at how to remove a file.
To do this, you can use the rm command, like "rm file_to_remove".

- You can also remove a directory by adding the -r option to the rm command, like "rm -r directory_to_remove".
Just like the cp command, you will get an error if you forget to add -r.
