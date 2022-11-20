# Bases

# xavier 20/11/2022

## STEPS
#### Given "bDNhcm5fdGgzX3IwcDM1" change base to get flag
2 ways:
A: throw it in cyberchef and let it solve 

B: Think it in a systematic way
1. when taking about base, check the sets{...} contructing the string first
1-A: sets in string is {lower case(26), upper case(26), number(10)}, which gives 26+26+10 = 62. which gives similar to base64
2. After finding which base, we can convert it to binary, and conver it to ascii
2-A: string -> binary -> ascii

## FOUNDINGS
strings with lower case, upper case and number is usually base 64(26+26+10 ~= 64)