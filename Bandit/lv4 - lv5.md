
## Level 4 → Level 5

## Goal 
The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.


## Solution

### Commands Used
```bash
ls 
cd inhere
file ./*
cat 
```

### Explanation

woah did i get stressed out here for a little bit , the most important thing to understand here is that the wildcard (*) is essentially a placeholder for the files that will be checked by the file command. Since each file has a special character "-" it will read the files as ./-file00 etc. Once I understood that the password was easy to find as only ASCII text would be the human readable file.

### Key Concepts
- using file command to check file types
- the wildcard as a placeholder 
