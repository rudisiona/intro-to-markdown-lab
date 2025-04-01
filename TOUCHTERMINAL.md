# Creating Directories and Files in the Terminal
![Coding Jumble](https://t3.ftcdn.net/jpg/02/68/01/34/360_F_268013450_C4s36OMiM74loZJtIL2lemLCbcCwhsIk.jpg)
Though using your terminal to create files and directories may seem more complicated or timely at first, when everything is layed out it can be quite easy.

## 1. Basics of the Terminal

`pwd` -> this command tells you the directory you are in, and the path to get there </br>

**Example:**
```
➜  ~ pwd
/Users/your-user
```

`cd` -> this command, along with a directory of your choosing, will switch into that directory.

**Example:**
```
➜  code cd ga
➜  ga
```

## 2. Making a directory

`mkdir` -> this command will make a direcotry, in the directory you are currently located in.

**Example:**
```
➜ ga mkdir labs
```
***TIP: Use `ls` to check that the directory has been made!***

```
➜  ga ls
labs
```
 ## 3. Making a file

`touch` -> this command will create  file in the directory you are currently in.

**Example:**

```
➜  labs touch README.md 
```
***TIP: The file must have a file (.md) extension. Use `ls`  again to check that the file has been made.***

```
➜  labs ls
README.md     
```