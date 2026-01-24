
## Level 5 → Level 6

## Goal 
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

human-readable
1033 bytes in size
not executable

## Solution

### Commands Used
```bash
cd inhere
find . -readable -size 1033c ! -executable
cd maybehere07
cat .file2 

```

### Explanation
I knew that the find command is used to search for certain files, but i had to research how to use the find command with multiple parameters 

### Key Concepts
- using the find command 
- applying multiple commands to find command 
