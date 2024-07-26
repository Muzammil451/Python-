seconds_in_a_day = 24 * 60 * 60
seconds_in_a_day
seconds_in_a_week = 7 * seconds_in_a_dayseconds_in_a_week

w=3
x=14
y=71
z=89
a=71

print(w+y/x*z)
print(w-y)
print(x+z)
print(y/w)
print(w*z)
print(a==y)

print(10.0.is_integer())
print(10.4.is_integer())
print(10.5.is_integer())

ans=float(4.2)
print(ans+4)
print(ans+5)
print(2<9)
print(5>1)
print(9<4)
print(10>6)
print(6!=8)
print(5==6)

print("welcome")
print("x")
print(x)

clas="7"
section="a"
print(clas + " " + section)
print(clas +  section)

cell_phone = "google pixel"
cell_phone

print(len(cell_phone))
print(len("cell_phone"))

"Happy pythoning!".upper()
"HAPPY PYTHONING!".lower()
cell_phone.upper()
cell_phone.lower()
"cell_phone".upper()
"CELL_PHONE".lower()
"Muzammil!".upper()
"MUZAMMIL".lower()
"data".upper()
"DATA".lower()

print("how are you?","hello", sep="---")
print("hello","how are you?", sep="\n")

# list 
class_sc =["Muzammil",12,10.1,True]
class_sc
class_sc.append("0322......")
class_sc
class_sc.reverse()
class_sc
class_sc.extend("Muzammil")
class_sc
class_sc.pop()
class_sc.count("l")
class_sc.copy()
class_sc.clear()
class_sc
elements=["Hydrogen","Helium","Lithium","Beryllium","boron","carbon","nitrogen","oxygen","flourine","neon","sodium","magnesium","aluminium","silicon","phosphorus"]
elements

# indexing 
student=["room","banana","chair","table","door","mirror","book","glass","pen","pencil"]
student[0:10]
student[-10:-8]

fruits_list=["apple","banana","cherry","mango","kiwi"]
fruits_list
print(len("fruits_lists"))
fruits_list[3]
fruits_list[2:5]

# list[inclusive:exclusive]
fruits_list[:]
fruits_list[1:]
fruits_list[0:4]
fruits_list.append("orange")
fruits_list
fruits_list.sort()
fruits_list
fruits_list.insert(2,"watermelon")
fruits_list
fruits_list.insert(1,"dragon fruit")
fruits_list
print(len(fruits_list))
fruits_list.pop()
fruits_list
fruits_list.sort()
fruits_list
fruits_list.reverse()
fruits_list

# tuple --->()
number1 = (1,2,3,4,5)
number1
print(type(number1))
number1[0:2]
number1[2]
print(len(number1))

# mutable (changable) vs imutable (unchangable)
number1=(1,2,3,4,5)
number2=(6,7,8,9,10)
number3=number1+number2
print(number3)
print(number1)
print(number2)
print(number3)
print(len(number1))
print(len(number2))
print(len(number3))
print(min(number3))
number3[4:10]
number3[4:9]

# (1,3,5,7,9)
number3[::2]
number3[:6:4]

# nested tuples
number4=(1,2,3,4,5)
number5=(6,7,8,9,10)
number6=number4,number5
print(number4)
print(number5)
print(number6)
number6[0]
number6[0][0]
number6[0][2:5]
print(number6[0][2])
print(number6[0][4])
number6[1][3]
number6[1][0:4]

name="Muzammil"
age=12
height=12.5
print(name)
print(age)
height

name='Muzammil'
type(name)
age=12
type(age)
height=13.5

# dictionary
my_dict={"key1":123,"key2":[12,23,33],"key3":["item0","item1","item2"]}
# let's call items from the dictionary
my_dict["key3"]
# finding out the type
type(my_dict)
my_dict={'name':'Muzammil','sub':['Math','chem','phy'],'mark':[90,80,70]}
my_dict['mark']
my_dict={'key1':500}
# Subract 123 from the value
my_dict['key1']=my_dict['key1']-123
# Check
my_dict['key1']
# Create a new dictionary
d={}
# Create a new key through assingment
d['animal'] = ['Dog','Cat']
# Can do this with any object
d['answer']=42
# Show
d
# Dictionary nested inside a dictionary nested inside a dictionary
d={'key1':{'nestkey':{'subnestkey':'value'}}}
# Keep calling the keys
d['key1']['nestkey']['subnestkey']
d={'worldcup':{'worldcup99':{'winner':'aus','runnerup':'pak'}}}
# for getting the inner most value.
d['worldcup']['worldcup99']['runnerup']
# for getting the inner most value.
d['worldcup']['worldcup99']['winner']
d={'montessori':{'6-A':{'first position':'Muzammil','second position':'Ansharah'}}}
# for getting the inner most value.
d['montessori']['6-A']['first position']
# for getting the inner most value.
d['montessori']['6-A']['second position']

# while loops
i = 1
while i < 6:
  print(i)
  i += 1
i = 1
while i < 6:
  print(i)
  if (i == 3):
    break
  i += 1
i = 0
while i < 6:
  i += 1
  if i == 3:
    continue
  print(i)

# Note that number 3 is missing in the result
i = 1
while i < 6:
  print(i)
  i += 1
else:
  print("i is no longer less than 6")

# For loops:
numbers=[1,2,3,4,5,6,7,8,9]
print(numbers)
for numbers in numbers:
  print(numbers)
names=["jamal","ahsan","hassan","waqar"]

for i in names:
    print("hello your name is:  ",i)


































import numpy as np
import IPython.display as display
from matplotlib import pyplot as plt
import io
import base64

ys = 200 + np.random.randn(100)
x = [x for x in range(len(ys))]

fig = plt.figure(figsize=(4, 3), facecolor='w')
plt.plot(x, ys, '-')
plt.fill_between(x, ys, 195, where=(ys > 195), facecolor='g', alpha=0.6)
plt.title("Sample Visualization", fontsize=10)

data = io.BytesIO()
plt.savefig(data)
image = F"data:image/png;base64,{base64.b64encode(data.getvalue()).decode()}"
alt = "Sample Visualization"
display.display(display.Markdown(F"""![{alt}]({image})"""))
plt.close(fig)
