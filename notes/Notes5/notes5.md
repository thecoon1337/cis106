## Notes 5
## LS
- **Usage**
  - `ls` is used for listing the content of a given directory. When no directory is specified, `ls` displays the files in the current working directory.
- **Formula**
  - `ls` + `option` + `directory to list`
- **Examples**
   - List the content of the current working directory:
      - `ls` 
   - List all the files inside the current working directory including hidden files: 
     - `ls -a`
   - List all the files inside a given directory:
     - `ls -a ~/Pictures`
   - Long list all the files inside a given directory recursively:
     - `ls -lR ~/Pictures`

## CD
- **Usage**
  - `cd` is used to change the current working directory. When no directory is given, `cd` changes the current working directory to the home directory of the current user.
- **Formula**
  - `cd` + `destination`
- **Examples**
  - Change from your home directory to your Downloads directory:
    - `cd Downloads`
  - Change from anywhere in the file system to your Downloads directory:
    - `cd ~/Downloads`
  - Change from anywhere in the file system to your Documents directory:
    - `cd /home/$USER/Documents`
  - Go back one or more directories:
    - `cd ../`

## PWD
- **Usage**
  - `pwd` is used for displaying the current working directory. By default, `pwd` behaves as if `-L` were specified.
- **Formula**
  - `pwd`
- **Examples**
  - Print the name of the current working directory.
    - `pwd -L`
  - Print the physical directory, without any symbolic links.
    - `pwd -P`

## What is a variable?

A variable is a container or placeholder for data.

## How do I use a variable?

A variable stores value to it can be reused later
- Example: `name = Daniel` + `echo $name`

## What is an environment variable?

A variable that is used to track specific system information and user information.

## What is a user defined variable?

A variable created by the user.

## What is the root directory?

The top level directory of the Linux FS.

## What does “Parent Directory” mean?

The directory one level above your current location.

## What does “Current working directory” mean?

Current working directory is the directory you are currently working in.

## What is an absolute path? Include an example

An absolute path is the location of a file starting at the root of the file system.

- Example: `/home/john/Downloads/song.mp3`

## What is a relative path? Include an example

A relative path i8s the location of a file starting from the current working directory.

- Example: `Downloads/song.mp3`

### What is the difference between “Your home directory” and “The home directory”?

Your home directory is your personal folder. The home directory contains all users home directories.
