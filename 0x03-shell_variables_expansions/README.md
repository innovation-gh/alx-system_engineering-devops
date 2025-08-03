# 0x03. Shell, init files, variables and expansions

This project focuses on shell scripting with emphasis on variables, expansions, and initialization files in Bash.

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General
- What happens when you type `$ ls -l *.txt`
- What are the `/etc/profile` file and the `/etc/profile.d` directory
- What is the `~/.bashrc` file
- What is the difference between a local and a global variable
- What is a reserved variable
- How to create, update and delete shell variables
- What are the roles of the following reserved variables: HOME, PATH, PS1
- What are special parameters
- What is the special parameter `$?`
- What is expansion and how to use expansions
- What is the difference between single and double quotes and how to use them properly
- How to do command substitution with `$()` and backticks

### Shell Initialization Files
- What happens when you start a shell
- What are the differences between `/etc/profile`, `/etc/bash.bashrc`, `~/.bashrc`, `~/.profile`, `~/.bash_profile`, and `~/.bash_login`

### Variables
- What is the difference between a local and a global variable
- What is a reserved variable
- How to create, update and delete shell variables

### Expansions
- What are expansions and how to use them
- What is the difference between single and double quotes
- How to do command substitution

## Requirements

### General
- Allowed editors: `vi`, `vim`, `emacs`
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long (`wc -l file` should print 2)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/bin/bash`
- A `README.md` file, at the root of the folder of the project, describing what each script does
- You are not allowed to use `&&`, `||` or `;`
- You are not allowed to use `bc`, `sed` or `awk`
- All your files must be executable

## Files

| File | Description |
|------|-------------|
| `0-alias` | Creates an alias for `ls` command |
| `1-hello_you` | Prints hello followed by current user |

## Usage

To run any script, make it executable first:
```bash
chmod +x script_name
./script_name
```

For alias scripts, you need to source them:
```bash
source ./0-alias
```

## Author

This project is part of the ALX Software Engineering program.

## Repository

- **GitHub repository:** `alx-system_engineering-devops`
- **Directory:** `0x03-shell_variables_expansions`