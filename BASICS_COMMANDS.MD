# Linux Basic Commands

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
$ mv file.txt directory
```




# mv - command moving files




