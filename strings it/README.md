# strings it

# xavier 20/11/2022

## STEPS
#### cat contents of file
A: long strings, seems executable

#### check if contains flag in contents of file
A: Used grep but unfound

#### check type of file by ```file fileName```
A: Executable file

#### checked hints and found using ```strings``` command to find printable strings in any files(including machine codes)
```strings fileName``` -to find & print printable stirngs in file

#### grep picoCTF from output of ```strings``` function
```strings fileName | grep "picoCTF"```

## FOUNDINGS
```strings fileName``` -to find & print printable strings from the file (can be any file including machine codes file)