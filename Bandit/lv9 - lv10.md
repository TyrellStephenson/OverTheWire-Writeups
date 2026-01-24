## Level 9 → Level 10

## Goal 
The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.


## Solution

### Commands Used
```bash
Strings data.txt | grep "="

```

### Explanation
This took a healthy bit of experimentation, at first i tried simply using 
```bash

grep "=" data.txt 

```
this gave me a message "binary file matches". So then i tried the strings command cause i read that it extracts readable text so that gave me an ocean of text to read through . Knowing this i tried using the pipe operator | to sort of join the strings and grep command together , which gave me the password 

### Key Concepts
- using grep on binary files
- using strings command
- using pipe operator 