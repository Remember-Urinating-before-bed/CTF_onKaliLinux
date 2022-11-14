# Static ain't always noise

# xavier 14/11/2022

-> wget for static and BASH script

-> cat static
A: random bin char, might be encrypted / program

-> subl BASH script
A: Seems can disassembly files from comments and codes

-> tried run but access denied, so add permission
# chmod +x ltdis.h

-> ran with empty arguement
A: got ... Usage: ltdis.sh <program-file> Bye! ...

-> ran with file together
# ./ltdis.sh static 
A: got written result to "static.ltdis.strings.txt with file offset"

-> cat static.ltdis.x86_64.txt 
A: Got machine code, shd be wrong file we are looking for

-> cat static.ltdis.strings.txt
A: Got flag in middle of file


FINDINGS
- remember .sh file run like a.out by "./fileName"
- Flags can be in the middle of contents of files