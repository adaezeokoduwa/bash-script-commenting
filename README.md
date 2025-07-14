# bash-script-commenting


# Adding Comments in Bash Scripts â€” Practice Summary

## Overview
Comments in Bash scripts are notes written in the code that are **ignored by the Bash interpreter**. They are used to **explain what the code does**, making the script easier to understand, maintain, and debug â€” both for yourself and for others who might read the code later.

In this practice session, I learned how to write **single-line comments**, use **multiple single-line comments**, and apply **best practices** for writing clear and useful comments in shell scripts.

---

## What I Practiced

### 1. **Understanding Single-Line Comments**
Single-line comments in Bash begin with the `#` symbol. Everything after the `#` on the same line is treated as a comment and not executed.

#### Example Practiced:
```
# This is a single-line comment explaining what the command below does
echo "Hello, you are learning Bash Scripting on DAREY.IO!"
```

I used this format to explain simple commands like `echo`, `apt update`, and `mkdir` in my scripts.

---

### 2. **Using Multiple Single-Line Comments**
Although Bash does not have multi-line comment blocks like other programming languages, I learned to use multiple single-line comments consecutively to explain larger blocks of code.

#### Example Practiced:
```
# This script updates the system
# and installs curl, a command-line tool
# used for making network requests.

sudo apt update
sudo apt install curl -y
```

I used this approach to describe a series of related commands for better clarity.

---

### 3. **Inline Comments**
I practiced placing comments after a command on the same line to describe its purpose quickly.

####  Example Practiced:
```
echo "Hello again!" # This prints a message to the terminal
```

This helped me document quick notes next to short commands.

---

### 4. **Following Best Practices**
I followed the recommended best practices from the guide:
- **Clarity**: My comments explain the *why*, not just the *what*.
- **Maintainability**: I updated comments if I changed the commands.
- **Usefulness**: I focused comments on complex or non-obvious logic.
- **Avoided Overcommenting**: I didn't comment on obvious commands like `echo` unless needed.
  ![](https://github.com/adaezeokoduwa/bash-script-commenting/blob/main/imgs/COMMENT1.jpg?raw=true)

---

## Example Script I Practiced With

Here is a sample script I created while practicing:
```
# This is a single-line comment explaining the next command
echo "Hello, world!"
```

```
# This script shows how to
# use multiple single-line comments
# in Bash scripting.
echo "This command will run"
```


```
#!/bin/bash

# Update the system package index
sudo apt update

# Install curl for making web requests
sudo apt install curl -y

# Notify user that setup is complete
echo "Setup Complete!"

```

I saved this script as `my_script.sh` and added helpful comments before each command.

---

## What I Learned
- Comments make my scripts **readable** and **professional**.
- They help explain logic, especially when I return to old scripts.
- Good comments can **prevent errors** by reminding me what each part of the code is doing.
- In collaborative environments, comments improve **teamwork** and **code review**.
![](https://github.com/adaezeokoduwa/bash-script-commenting/blob/main/imgs/COMMENT2.jpg?raw=true)
