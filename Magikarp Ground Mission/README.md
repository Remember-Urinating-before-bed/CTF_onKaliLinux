# Magikarp Ground Mission

# xavier 15/11/2022


## STEPS
#### Connected to ssh and entered password
'''
ssh ctf-player@venus.picoctf.net -p 52151
'''
password = ee388b88

#### List files inside
'''
ls 
'''

#### Found 2 files, “1of3.flag.txt” & “instructions-to-2of3.txt”
'''
cat “1of3.flag.txt”
'''
A: picoCTF{xxsh_

#### Cat “instructions-to-2of3.txt”
A: Go to root of all things
'''
cd /
'''

#### Found 2of3 & instructions-to-3of3
'''
cat 2of3
'''
A: 0ut_0f_\/\/4t3r_

'''
Cat instrutions-to-3of3
'''
A: Go to home directory
'''
cd ~
'''

#### Found 3of3
'''
cat 3of3
'''
A: 3ca613a1}


## FOUNDINGS
- '''cd /''' -move to root directory 
- '''cd ~''' -move to home directory