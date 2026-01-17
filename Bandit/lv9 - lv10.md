## Level 9 → Level 10

## Goal 
The password for the next level is stored in the file data.txt, which contains base64 encoded data

## Solution

### Commands Used
```bash
ls
base64 -d data.txt 

```

### Explanation
the base64 command is used to encode files in base64, using the command with the -d switch decodes the file instead


### Key Concepts
- base64 command and its switch -d 