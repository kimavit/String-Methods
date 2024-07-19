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
