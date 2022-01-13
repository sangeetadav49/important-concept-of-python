# important-concept-of-python
For beginners as well as programmers
a.	Gess data type for a.
>>> a=1,2,3
>>> print(a)
(1, 2, 3)
Answer : Tuple
b.	Example of escape sequence character......\n to move to next line
>>> print('today\nis\nThursday')
today
is
Thursday

c. Example of triple quote string	
>>> print('''today
\nis
\nthursday''')
today

is

Thursday


d.	

>>> 3+3.00, 3**3.0
(6.0, 27.0)

e. + operator with string 
>>> int("3"+"4")
      34
f. break keyword to break a loop  
for i in range(1,11):
    if i%5==0:
        break
    print(i)
g. continue keyword to skip an iteration in loop
for i in range(1,11):
    if i%5==0:
        continue
    print(i)
h. pass is a null statement
for i in range(1,11):
    if i%5==0:
        pass
    print(i)
i.  using escape sequence character in doc string
>>> print('\new\new')

ew
ew
j.
converting doc string to raw string
>>> print(r'\new\new')
\new\new
k. using \ to display escape sequence character
>>> print(r'\\new\\new')
\\new\\new
>>> print('\\new\\new')
\new\new

i. different ways to create single element tuple 
>>> a=1,
>>> print(a)
(1,)
>>> a=(1,)
>>> print(a)
(1,)
different ways to create simple integer constant
>>> a=(1)  or a=1
>>> print(a)
1
j. different ways to create single element list
>>> a=[1]
>>> print(a)
[1]
>>> a=[1,]
>>> print(a)
[1]
k. Nested list
>>> l=[1,[2]]
>>> print(l[1][0])
2
>>> print(l[1])
[2]
>>> l=[1,[2]]
>>> print(l[1][0])
2
>>> print(l[1])
[2]
l. String Slicing
>>> s="hello"
>>> print(s[-3:])
llo
>>> 
>>> print(s[:-3])
he
>>> print(s[:-3:-1])
Ol
String functions
>>> "12".isdigit()
True
>>> "12ddd".isdigit()
False
>>> "12.".isdigit()
False
>>> "12.5".isdigit()
False
>>> "1,234".isdigit()
False
>>> True or False
True
>>> True and False
False
>>> False and True
False
>>> False or True
True
>>> 3 and 4
4
>>> 2< 3 and 1
1
>>> 2<3 or 1
True

>>> chr(97)
'a'
>>> ' '.isalnum()
False
>>> '1'.isalnum()
True
>>> 'a'.isalnum()
True
>>> "    ssdd".lstrip()
'ssdd'
>>> "sdff".lstrip("s")
'dff'
>>> "sdfdf     ".rstrip()
'sdfdf'
>>> "sdsdr".rstrip("r")
'sdsd'
>>> "    asdasd   ".strip()
'asdasd'
>>> "aashjjjaa".strip("a")
'shjjj'
>>> "sshhhhshhs".strip("s")
'hhhhshh'
>>> "dafsg".index("af")
1
>>> "dasg".index("zx")
Traceback (most recent call last):
  File "<pyshell#92>", line 1, in <module>
    "dasg".index("zx")
ValueError: substring not found
>>> "asddd".replace("s","@")
'a@ddd'
>>> "asddd".replace("Z","@")
'asddd'
>>>
>>> "today is Friday".partition("is")
('today ', 'is', ' Friday')
>>> "sssdghdkkd".partition("d")
('sss', 'd', 'ghdkkd')
>>>
"sssdghdkkd".split("d")
['sss', 'gh', 'kk', '']
>>> "dfdfd".split("d")
['', 'f', 'f', '']
>>> "ddfdfdd".split("d")
['', '', 'f', 'f', '', '']
>>> l=[23,34,56,76,87]
>>> print(l[-2:-4])
[]
>>> print(l[-2:-4:-1])
[76, 56]
>>>
Copy

>>> s1=l.copy()
>>> print(s1)
[23, 34, 56, 76, 87]

>>> s1=l.copy()  #  Duplicate copy
>>> print(s1)
[23, 34, 56, 76, 87]
>>> s1[0]='a'
>>> print(l)
[23, 34, 56, 76, 87]

>>> s=l
>>> s[0]="we"
>>> print(l)
['we', 34, 56, 76, 87]
>>> p=l[:]
>>> p[0]="rrr"
>>> print(l)
['we', 34, 56, 76, 87]
>>> l=list([1,2,3])
>>> print(l)
[1, 2, 3]

>>> print(sorted(l))
[0, 1, 2]
>>> l=(3,2,4)
>>> print(sorted(l))
[2, 3, 4]
>>> print(l)
(3, 2, 4)
