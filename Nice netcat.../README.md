
# Nice netcat ..

# xavier 13/11/2022
 
## STEPS
#### Connect to site from given port
```
nc mercury.picoctf.net 7449
```

#### Tried connect netcat but random num came out
112 
105 
99 
111 
67 
84 
70 
123 
103 
48 
48 
100 
95 
107 
49 
116 
116 
121 
33 
95 
110 
49 
99 
51 
95 
107 
49 
116 
116 
121 
33 
95 
102 
50 
100 
55 
99 
97 
102 
97 
125 
10 

#### Check first few num to see if is ASCII of picoCTF
Ans: Yes, 112 is ASCII of p

#### Googled for ASCII to char
Ans: a = "ASCII" -just a var
     a.decode('unicode_escape') -to real convert ASCII to char
-> But no use at all

-> Copied output "112  105  99  111  67  84  70  123  103  48  48  100  95  107  49  116  116  121  33  95  110  49  99  51  95  107  49  116  116  121  33  95  102  50  100  55  99  97  102  97  125  10" to web so that no enter key for input

#### Simple python to loop throgh list and print char
```
a = output string
a = a.split() -split by whitespace
for i in a:
	print(chr(int(i)), end='')
	ENTER 2 TIMES to stop loops
```


## FOUNDINGS
- nc (netcat) can be used to connect port on internet via ```nc siteName portNum```