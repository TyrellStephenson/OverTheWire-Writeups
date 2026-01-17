
## Level 6 → Level 7

## Goal 
The password for the next level is stored somewhere on the server and has all of the following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size

## Solution

### Commands Used
```bash
cd / 
find . -user bandit7 -size 33c -group bandit6 2>/dev/null
```

### Explanation
since it said that the file was somewhere on the server , i navigated to the root directory using cd / and then searched the entire server with a find command fitting the required parameters, ensuring to use 2>dev/null to get rid of error messages 

### Key Concepts
- navigating to the root directory 
- discarding error messages with 2>/dev/null
- finding users by group and user 
