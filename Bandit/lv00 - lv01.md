# OverTheWire: Bandit Writeups


---

## Level 0 → Level 1

## Goal 
The password for the next level is stored in a file called **readme** located in the home directory.

## Solution

### Commands Used
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls
cat readme
```

### Explanation
The solution for this is simple , using ls to confirm that the readme file was there and then using cat to retrieve the password.Great start.

### Key Concepts
- SSH connection with custom port (`-p 2220`)
- Basic file navigation in Linux
- Using `cat` to read file contents



