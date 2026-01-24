## Level 8 → Level 9

## Goal 
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once

## Solution

### Commands Used
```bash
ls
sort data.txt | uniq - u 

```

### Explanation
using the sort command as well as uniq -u , i was able to isolate the one line with the password , using uniq without the -u switch returns a massive wall of characters so dont do that haha.


### Key Concepts
- sort command 
- using the uniq command and its -u switch 