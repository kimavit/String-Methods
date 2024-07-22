Text Sequence Type — str
========================
String Methods
--------------
````ruby
n = int(input())
cnt = 0
for i in range(n):
    s = input()
    if s.count("11") >= 3:
        cnt += 1
print(cnt)
````
````ruby
s = str(input())
max = 0
m = 0
for i in range(len(s)):
    if s.count(s[i]) >= max:
        max = s.count(s[i])
        m = s[i]
print(m)
````
````ruby
s = input()
a = s.find ("h")
b = s.rfind ("h")
print(s.replace ((s[a:b+1]), ''))
````
````ruby
num = input()
flag = 'NO'
let = 'АВЕКМНОРСТУХ'
if 9 <= len(num) <=10:
    le = num[0] + num [4:6]
    dig = num [1:4] + num[7:]
    un = num[6]
    if dig.isdigit() and un == "_":
        flag = 'YES'
    for i in le:
        if i not in let:
            flag = 'NO'
print (flag)
````
````ruby
n = int(input())
s = input()
script = 26
for i in range (len(s)):
    w = ord(s[i]) - n
    if w < 97:
        w += script
    print(chr(w), end = " ")
````
