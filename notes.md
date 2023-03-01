Notes by Soumyajeet Bal
### 1 - What is Data Science?
- Introduction to datascience
- Some examples related to application of data science (store data analysis for decision maybe marketing, etc)

### 2 - Data Science for beginners and where to learn it
- defination : Datascience is a process of drawing insights from data.
- https://drive.google.com/file/d/14yb8XPOOuRwOMoYltCPKaoEAGVuqpjNr/view?google_abuse=GOOGLE_ABUSE_EXEMPTION%3DID%3Deaef5bca232cab19:TM%3D1677678939:C%3Dr:IP%3D2405:201:a000:68b9:15c1:85ea:7e9b:8b3-:S%3DXKXk2avqtdHtQ_u4WsZ6HqM%3B+path%3D/%3B+domain%3Dgoogle.com%3B+expires%3DWed,+01-Mar-2023+16:55:39+GMT 
-  Check description - https://www.youtube.com/watch?v=Vn_mmOuQkSA&list=PLeo1K3hjS3us_ELKYSj_Fth2tIEkdKXvV&index=3&ab_channel=codebasics

### 3 - Install python on windows [Python 3 Programming Tutorials]  
- Python installation 
- IDLE inbuilt 
- python shell - allows to write program
- cmd python converts cmd to python shell
- environment variable incase python is not mapped in system.

### 4 - Variables in python [Python 3 Programming Tutorials]
- simple variable defination and naming convention
- print multiple item i.e ``` print("Expense items: ",item1,item2,item3) ``` It will auto insert space
- True is a keyword so cant be used as variable

### 5 - Numbers [Python 3 Programming Tutorials]
- Variables used to store values
- / - division 
- // - Integer division or Floor division
- ** - power
- % - modulo for remainder
- integer and floating numbers (there is another called complex)
- round(x.12323.. ,2) 
- precedence in opearators 
- 6-5.7 = 0.2999998 (floating number always loose accurancy)

### 6 Strings [Python 3 Programming Tutorials]
- how python stores string (array of characters)
- ith positon of a string is string[i]
- Strings are immutable i.e you cannot change them once created
- String slicing using index subrange string[0:3] 0 to 3-1.
- double quotes and single quotes and triple quotes (internally uses \n)
- + for concatenation
- str function converts a number to string

### 7 - Lists [Python 3 Programming Tutorials]
- collection of item
- list= ["one","two","three","four"]
- list can be manipulated and altered
- list[0:2] print the list elements from 0 to 1
- list[-1] prints the last element
- there are several function to operate with the list i.e list.append("butter")
- list.insert(1, "butter") all other elements gets shifted
- + sign can be used to join two list
- len(list) prints length of the list
- "bread" in list (searches for bread in list; return true if found )

### 8 -Install PyCharm on Windows [Python 3 Programming Tutorials]
- pycharm download 
- basic installation setup

### 9 - Debug Python code using PyCharm [Python 3 Programming Tutorials]
- breakpoint in pycharm

### 10 - If Statement [Python 3 Programming Tutorials]
- input() for taking input
- int(var_name) can be used to convert the string to integer
- if num%2==0 : 
- and or not operators 
- elif (it is basically else if)

### 11 - For loop [Python 3 Programming Tutorials]

```
exp=[1,10,11,22,15]
sum=0
for i in exp:
    sum=sum+i
print (sum)
```
- range(1,11,2)  -  here 1 is the starting point; 11-1 is the end point; and 2 is the incrementation value
- len(list) can be used in range 
- while and do while

### 12 - Functions [Python 3 Programming Tutorials]
- to avoid code repetation
- def a_Fun() - def is used to define a funtion
- function argument, function parameter, return value, function body
- Position arguments and named arguments - named arguments (b=10,a=5)
- Global vs local varible (scope is limited to the particular code block)
- missing argument ( you can initialize default varible in function parameter incase there is argument missing) i.e def lol(a,b=0) ; here b is default varible
- documentation """ """

https://www.geeksforgeeks.org/differences-and-applications-of-list-tuple-set-and-dictionary-in-python/

### 13 - Dictionaries and Tuples [Python 3 Programming Tutorials]
- something called key and value
```
d={"tom":5651,"sam":6525,"lol":5621,"rob":4584}
print(d["lol"])
```
- del d["lol"] will delete the value of key "lol" in dictionary d
```
for key in d: 
  print(d[key])
```
- tuples 
```
for k,v in d.items():
  print(v)
print("sam" in d)
d.clear()
```
### Tuples 
```
point=(5,9)
```
- Tuple is immuttable unnlike list which mutable
- 
