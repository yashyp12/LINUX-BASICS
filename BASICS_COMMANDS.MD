# LINUX BASIC COMMANDS

- env variables
  patil@Yp MINGW64 ~/Documents/GitHub/SELENIUM-JAVA/LINUX-BASICS (main)
  $ export MY_PATH="Yash"

patil@Yp MINGW64 ~/Documents/GitHub/SELENIUM-JAVA/LINUX-BASICS (main)
$ echo $MY_PATH
Yash

pwd- present working directory

ls -a - shows hidden files with started from .

cd - change directory

. current directory , .. previous directory,

ls -r -> returns all subfolders files

cat - concatinate
used to all the contents which are aval in the file

too create a file with some content

- $ cat > file.txt
- merging with two file - $ cat demo.txt file.txt > merge.txt

-echo ->Write-Output prints whatever we add

- $ echo "hlllo new " > file1.txt

# man command

- used for getting more info about the command

# transalate - tr

- used to translate the characters

$ cat demo.txt | tr a-z A-Z > upper.txt

% // (pipe | ) the output of the first command is act as a input for the second command  
% // (> redirection) -> used to redirect the output

# commands for creating an folder

- mkdir