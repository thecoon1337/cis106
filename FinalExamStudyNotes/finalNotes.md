#### How to clone a GitHub repository

- *To clone a repository, run the following command in your terminal:*
`git clone` + `<repo-url>`

#### How to use the git commands

- #### `git pull` - synchronizes your GitHub repository to your local machine.
- #### `git add .` - tracks all changes made to your files.
- #### `git commit -m "Your message here"` - Labels all changes made.
- #### `git push` - Sends all changes to your GitHub repository.
- #### `git clone <repo-url>` - Downloads an entire GitHub repository to your machine.

#### How to write a Markdown file that contains images and proper formatting

- *To write a Markdown file that contains images and proper formatting, you need to understand:
- ##### Headings (#)
  - `# Heading 1`
  - `## Heading 2`
  - `### Heading 3`

- ##### Bold & Italics (*)
  - `**bold text**`
  - `*italic text*`

- ##### Links
  - `[description](link)`

- ##### Images
  - `![description](file-name.png)`

- ##### Tables
- `| Column 1 | Column 2 |`
`|----------|-----------|`
`|----------|-----------|`
`|----------|-----------|`

- ##### Lists


#### How to convert a Markdown file to PDF

- *Right click on your file in VS Code and select Markdown PDF: Export*

#### How to compress (zip) a directory/folder in Debian

- Run `sudo apt install zip` to install the zip command. 
- Then, run `zip -r` + `archive.zip foldername/` Where `archive.zip` is the name of your new ZIP  file, and `foldername/` is the folder you want to compress.

#### What are Absolute paths and relative paths? (provide examples with commands. For example, creating a file using an absolute path.)

- Absolute path is the location of the file starting at the root of the file system. Ex: `~/home/john/Downloads/song.mp3`
- Relative path is the locatio of the file starting from the current working directory. Ex: `Downloads/song.mp3`

#### How to work with the manual pages (man command)?

- The `man` command 

#### How to parse (search) for specific words in the manual page

- 

#### How to redirect output (>, >>, and |)

- 

#### How to append the output of a command to a file

- **Use `>>` after a command to add to a file instead of overwriting it's content**

**Usage:** `command` + `>>` + `filename`

**Examples**
- Append a directory listing to a file.
  - `ls -lA >> allmyfiles.txt`
- Add system information to a log file.
  - `uname -a >> system_info.log`
- Add the current date and time to a log file.
  - `date >> system_info.log`

#### How and when to redirect the output of a command to another (pipes)

- 

#### How to use echo and output redirection to create a new file that contains some text

- 

#### How to use wildcards (For copying and moving multiple files at the same time)

- 

#### How to use brace expansion (For creating entire directory structures in a single command)

- 

#### How to create a simple “hello world” shell script

- 

#### How to use variables in a shell script

- 

#### For each of the following commands, include a definition, syntax/formula/usage/, and 2 - 5 well-documented examples.

## `awk`
- **Used to scan and format text data line by line.**

**Formula:** `awk` + `options` + `{awk command}` + `file(s)`

**Example:** `awk` + `'{print $1}` + `~/Documents/Csv/cars.csv`

## `cat`
- **Used to display the content of a file.**

**Formula:** `cat` + `option` + `file(s) to display`

**Example:** `cat` + `~/Documents/sample_files/file.txt`

## `cp`


## `cut`
- **Used  to remove a specific section of each line in a file and display it.**

**Formula:** `cut` + `option` + `file(s) to display`

**Example:** `cut` + `-d ':' -f1 /etc/passwd/`

## `grep`
- **Used to search the text of a file line by line.**  

**Formula:** `grep` + `option` + `search criteria` + `file(s)`

**Example:** 
`grep` + `'dracula'`

## `head`
- **Displays the first N number of lines in a given file. Prints the first 10 by default.**

**Formula:** `head` + `option` + `files(s) to display`

**Examples:** 
`head` + `~/Documents/sample_files/file.txt`

## `ls`
- ****

**Formula**

**Examples:**


## `man`


## `mkdir`
- **Used to create directories**

**Formula:** `mkdir` + `the name of the directory`

**Examples:**
`mkdir` + `wallpapers`
- *Makes directory in the present working directory.*

`mkdir` + `wallpapers/ocean`
- *Makes directory in a different directory using relative path*

## `mv`
- **Used to move and rename directories**

**Formula:** `mv` + `source` + `destination`

**Examples:**



## `tac`
- **Used to display the contents of a file in reverse order.**

**Formula:** `tac` + `option` + `file(s) to display`

**Examples:** 
`tac` + `~/Documents/sample_files/file.txt`

## `tail`


## `touch`
- **Used for creating files.**

**Formula:** `touch` + `filename`

**Examples:**
`touch` + `list`
- *Creates a file called list.*

`touch` + `list_of_cars.txt` + `scripts.py` + `names.csv`
- *Creates several files*


## `tr`
- **Used for translating or deleting characters from standard output**

**Formula:** `Standard Output | tr + option + set + set`

**Example:** 
`cat file.txt | tr '.' ','`
- *Translate one character to another. In this case, changing a period with a comma.*

`cat program.py | tr "[:space:]" '\t'`
- *Translate white space into tabs*

## `tree`
- **Used to list the contents of directories in tree-like format**

**Formula:** `tree` + `(name of directory)`
**Example:** 
``
- **

``
- **

