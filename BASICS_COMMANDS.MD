# Linux Basic Commands
doc - https://docs.rockylinux.org/10/books/admin_guide/03-commands/
## Table of Contents
- [Environment Variables](#environment-variables)
- [Directory Navigation](#directory-navigation)
- [File Operations](#file-operations)
- [Text Processing](#text-processing)
- [Manual/Help](#manualhelp)

---

## Environment Variables

Environment variables store configuration data that can be accessed by programs.

### Setting Environment Variables
```bash
export MY_PATH="Yash"
```

### Viewing Environment Variables
```bash
echo $MY_PATH
# Output: Yash
```

---

## Directory Navigation

### `pwd` - Present Working Directory
Shows the current directory path.

```bash
pwd
```

### `cd` - Change Directory
Navigate between directories.

```bash
cd /path/to/directory
cd ..    # Move to parent directory
cd .     # Current directory
```

**Note:** `.` represents current directory, `..` represents parent directory

---

## File Operations

### `ls` - List Files

```bash
ls           # List files in current directory
ls -a        # Show hidden files (files starting with .)
ls -r        # List all files including subdirectories
```

### `cat` - Concatenate
Used to display, create, and merge file contents.

#### Display file contents:
```bash
cat filename.txt
```

#### Create a file with content:
```bash
cat > file.txt
# Type your content, then press Ctrl+D to save
```

#### Merge multiple files:
```bash
cat demo.txt file.txt > merge.txt
```

### `echo` - Print Text
Prints text to the terminal or redirects to a file.

```bash
echo "Hello World"
```

#### Redirect output to a file:
```bash
echo "Hello new" > file1.txt
```

---

## Text Processing

### `tr` - Translate Characters
Used to translate or transform characters in text.

#### Convert lowercase to uppercase:
```bash
cat demo.txt | tr a-z A-Z > upper.txt
```

### Special Operators

- **Pipe (`|`)**: The output of the first command becomes the input for the second command
  ```bash
  command1 | command2
  ```

- **Redirection (`>`)**: Redirects output to a file (overwrites)
  ```bash
  command > output.txt
  ```

- **Append (`>>`)**: Redirects output to a file (appends)
  ```bash
  command >> output.txt
  ```

---

## Manual/Help

### `man` - Manual Command
Displays detailed information about a command.

```bash
man command_name    # Example: man ls
```

---

## Directory Management

### `mkdir` - Make Directory
Creates a new directory/folder.

```bash
mkdir folder_name
mkdir -p parent/child    # Create nested directories
```

Create a new File 
```bash
touch file_name   # creates a file
```

Copy command
```bash
cp file.txt copy_file.txt
```

FOR RENAME THE FILE
```bash
$ mv demo.txt demo4.txt
```

# mv - command moving files
```bash
$ mv file.txt directory
```
Move and rename the file at same time

```bash
$ mv names.txt ../newName.txt
```

# remove the directory - rm [remove-Item]
- remove the file permeanently - not even in the bin 

- rm

```bash
$ rm demox.txt
```

# cp - copying the directory

```bash
$ cp -R test directory
```

# rm - remove files 
```bash
$ rm dir/demol.
```

- if we want to delete folder / directory

```bash
$ rm -R dir
```

- f flag is a force flag

# sudo -> SUPER USER DO

- sudo commands requires administration permissions 

```bash
sudo echo "Hello wrold"
```
-checek disc space usage -- displayes the free disc space
```bash
df  -showing in kb 
```
```bash
df  -m -showing in mb 
```

```bash
df  -h -showing in human readable format
```

```bash
du   -shows the disk usage statistics
```

head - used to view the first liens of the file  by def its 10
```bash
head total.txt 

head -n 4 total.txt // this will how only 4 lines only
```


tail  - sed to shows the last lines in the files 

```bash
tail total.txt
$ tail -n 2 total.txt //shows the last 2 lines from the file
```


diff- used to compare the files line by line 













