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
numbers=range(0,200)
print(numbers)
for integer in range(0,200):
    print(integer)
for integer in range(0,200):
    print(integer//5)
for integer in range(0,200):
    print(integer/5)
for integer in range(0,200,2):
    print(integer)
for integer in range(1,50,2):
    print(integer)
total = 0
for number  in range(1,21):
    total += number
    print(total)
print("Your total from1 to 20 is: ",total)
for i,j in zip(range(0,20), range(120,140)):
    print(i,j)
number = int(input("Enter the number for multiplication table"))
print("Multiplication table:    ")
print("--------------------")
for i in range(1,13):
    print(i, " x " ,number," = ", i*number)
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
  if x == "banana":
    break

num=[7757,5454,654]
for i in range(len(num)):
    num[i]+=1

print(i)

for i in "banana":
    print(i)

57%2

age=13

if age> 14 and grade ==2:
  print("u can take addmisiion")
elif age<14:
  print("come after one year")
else:
  print("you'r not eligible")


# Define a condition
condition = True

# Use the condition in an if-elif-else statement
if condition:
    print("Your condition is True")
elif not condition:
    print("Your condition is False")
else:
    print("This should not happen")

if condition:
    print("your condition")
elif condition:
    print("whatever you want")
else:
    print("again what you want")

age=int(input("enter your age"))

if age <13:
  print("child")
elif 13 <= age <20:
  print("teen")
else:
  print("adult")

# USER DEFINE FUNCTION

def greet(name):
    print(f"hello {name} welcome to NED university")

greet("Muzammil")

4*4

def square(number):
    x=number*number
    return(x)

# Multiply the length of rectangle by width of the rectangle
def area_of_rec(length, width):
  x=length+width-height
  return(x)

square(2)

square(6)

square(100)

def area_of_rec(length,width):
  x=length+width
  return(x)

area_of_rec(3,6)

def area_of_rec(length,width,height):
  x=length+width-height
  return(x)

area_of_rec(10,6,5)

a=7
b=8
c=2
y=a+b
s=y-c

s

def volume(l,w,h):
    x=l+w-h
    return(x)

volume(3,4,5)

# Define the Dog class
class Dog:
    # This method initializes the object when it is created
    def __init__(self, name, age):
        self.name = name  # Attribute to store the dog's name
        self.age = age    # Attribute to store the dog's age

    # Method for the dog to bark
    def bark(self):
        print(f"{self.name} says: Woof!")

    def play(self,toy):
        return f"{self.name} plays with {toy} "

    # Method to get the dog's age in dog years (1 human year = 7 dog years)
    def get_dog_years(self):
        return self.age * 7

#Create instances (objects) of the Dog class
my_dog = Dog("Buddy", 3)
your_dog = Dog("Bella", 5)

#Use the methods of the Dog class
my_dog.bark()  # Output: Buddy says: Woof!
your_dog.bark()  # Output: Bella says: Woof!

#Get the dog's age in dog years
print(f"{my_dog.name} is {my_dog.get_dog_years()} dog years old.")  # Output: Buddy is 21 dog years old.
print(f"{your_dog.name} is {your_dog.get_dog_years()} dog years old.")  # Output: Bella is 35 dog years old.


#reate instances (objects) of the dog claas
my_dog=Dog("Buddy",3)


#use the method of the dog class
my_dog.bark()   # Output: buddy says: Woof!

class CoffeeMaker:
    def _init_(self, water_level, coffee_beans):
        self.water_level = water_level  # in milliliters
        self.coffee_beans = coffee_beans  # in grams

    def make_coffee(self, cup_size):
        if self.water_level >= cup_size and self.coffee_beans >= 10:
            self.water_level -= cup_size
            self.coffee_beans -= 10
            print("Your coffee is ready!")
        else:
            print("Not enough water or coffee beans!")

    def refill_water(self, amount):
        self.water_level += amount
        print(f"Refilled water by {amount}ml. Current water level: {self.water_level}ml.")

    def add_coffee_beans(self, amount):
        self.coffee_beans += amount
        print(f"Added {amount}g of coffee beans. Current coffee beans: {self.coffee_beans}g.")

#Create a coffeeMaker object
my_coffee_maker=(500,100)

# Bar graphs
import seaborn as sns
#Load the built-in 'mpg' dataset
mpg_df = sns.load_dataset('mpg')

#Display the first few rows of the dataset
mpg_df.head()

import matplotlib.pyplot as plt
import seaborn as sns

#Bar Chart: Average MPG by Origin
plt.figure(figsize=(6, 4))
sns.barplot(x='origin', y='mpg', data=mpg_df)
plt.title('Average MPG by Origin')
plt.xlabel('origin')
plt.ylabel('Miles per gallon')
plt.show()
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
import seaborn as sns

mpg_df = sns.load_dataset('mpg')

mpg_df

data=["cylinders"]

students=["Mahad","Azfi","Hussain","Zainab"]
marks=[80,85,70,90]
plt.figure(figsize=(10, 6))

#guess the number

numcheck=int(input("enter your number between 1 to 10:"))

if numcheck%2==0:
  print("even")
else:
  print("odd")


def calculate_price(coffee_type, size, sugar, temperature):
    # Prices for different sizes
    prices = {
        'large': 4.50,
        'medium': 3.50,
        'small': 2.50
    }

    # Base price for each coffee type
    base_prices = {
        'americano': 1.50,
        'espresso': 2.00,
        'cappuccino': 2.50,
        'black coffee': 3.00,
        'milk coffer': 3.50,
    }

    # Calculate total price
    base_price = base_prices.get(coffee_type, 0)
    size_price = prices.get(size, 0)
    total_price = base_price + size_price

    # Print order details
    print("\nOrder Details:")
    print(f"Coffee: {coffee_type}")
    print(f"Size: {size}")
    print(f"Sugar: {'Yes' if sugar else 'No'}")
    print(f"Temperature: {temperature}")
    print(f"Price: ${total_price:.2f}")

#Main function to handle user input
def main():
    print("Welcome to the coffee shop!")

    # Ask user for coffee choice
    print("\nWhat type of coffee would you like?")
    print("1. Americano")
    print("2. Espresso")
    print("3. Cappuccino")
    print("4. black coffee")
    print("5. milk coffee")
    choice = input("Enter your choice (1/2/3/4/5): ")

    coffee_type = ''
    if choice == '1':
        coffee_type = 'americano'
    elif choice == '2':
        coffee_type = 'espresso'
    elif choice == '3':
        coffee_type = 'cappuccino'
    elif choice == '4':
        coffee_type = 'black coffee'
    elif choice == '5':
        coffee_type = 'milk coffe'
    else:
        print("Invalid choice. Please try again.")
        return

    # Ask user for sugar preference
    sugar_input = input("Do you want to add sugar (yes/no)? ").lower()
    if sugar_input == 'yes':
        sugar = True
    else:
        sugar = False

    # Ask user for temperature preference
    temperature = input("Do you want it hot or cold? ").lower()

    # Ask user for cup size
    size = input("What size would you like (large/medium/small)? ").lower()
    while size not in ['large', 'medium', 'small']:
        print("Invalid size. Please choose again.")
        size = input("What size would you like (large/medium/small)? ").lower()

    # Calculate and print the price
    calculate_price(coffee_type, size, sugar, temperature)
    print("\nHere is your coffee. Enjoy!")

#Run the main function
if __name__ == "__main__":
    main()


class IceCreamOrder:
    def __init__(self):
        self.prices = {
            'large': 5.00,
            'medium': 4.00,
            'small': 3.00
        }
        self.base_prices = {
            'vanilla': 1.00,
            'chocolate': 1.50,
            'strawberry': 2.00,
            'caramel': 2.50,
            'blue berry': 3.00
        }

    def calculate_price(self, flavor, size, toppings):
        base_price = self.base_prices.get(flavor, 0)
        size_price = self.prices.get(size, 0)
        total_price = base_price + size_price

        # Add extra cost for toppings
        if 'sprinkles' in toppings:
            total_price += 0.50
        if 'chocolate chips' in toppings:
            total_price += 0.75

        return total_price

    def take_order(self):
        print("Welcome to the ice cream parlor!")

        # Ask user for flavor choice
        print("\nWhat flavor would you like?")
        print("1. Vanilla")
        print("2. Chocolate")
        print("3. Strawberry")
        print("4. caramal")
        print("5. blue berry")
        choice = input("Enter your choice (1/2/3/4/5): ")

        flavor = ''
        if choice == '1':
            flavor = 'vanilla'
        elif choice == '2':
            flavor = 'chocolate'
        elif choice == '3':
            flavor = 'strawberry'
        elif choice == '4':
            flavor = 'caramel'
        elif choice == '5':
            flavor = 'blue berry'
        else:
            print("Invalid choice. Please try again.")
            return

        # Ask user for size
        size = input("What size would you like (large/medium/small)? ").lower()
        while size not in ['large', 'medium', 'small']:
            print("Invalid size. Please choose again.")
            size = input("What size would you like (large/medium/small)? ").lower()

        # Ask user for toppings
        toppings = []
        while True:
            topping = input("Enter a topping you would like (sprinkles/chocolate chips/cookie/granola/syrup, or type 'done' to finish: ").lower()
            if topping == 'done':
                break
            elif topping in ['sprinkles', 'chocolate chips', 'cookie', 'granola', 'syrup']:
                toppings.append(topping)
            else:
                print("Invalid topping. Please choose again.")

        # Calculate total price
        total_price = self.calculate_price(flavor, size, toppings)

        # Print order details
        print("\nOrder Details:")
        print(f"Ice Cream Flavor: {flavor}")
        print(f"Size: {size}")
        print("Toppings:", ', '.join(toppings) if toppings else "None")
        print(f"Price: ${total_price:.2f}")

#Main function to run the ice cream ordering process
def main():
    ice_cream_order = IceCreamOrder()
    ice_cream_order.take_order()
    print("\nHere is your ice cream. Enjoy!")

#Run the main function
if __name__ == "__main__":
    main()

import random

class Game:
    def __init__(self, lower_bound, upper_bound):
        self.lower_bound = lower_bound
        self.upper_bound = upper_bound
        self.target_number = random.randint(lower_bound, upper_bound)
        self.guesses = 0
        self.game_over = False

    def make_guess(self, guess):
        self.guesses += 1
        if guess < self.target_number:
            return "Too low!"
        elif guess > self.target_number:
            return "Too high!"
        else:
            self.game_over = True
            return f"Correct! You've guessed the number in {self.guesses} tries."

    def is_game_over(self):
        return self.game_over


class Player:
    def __init__(self, name):
        self.name = name

    def get_guess(self):
        guess = input(f"{self.name}, enter your guess: ")
        return int(guess)


def main():
    print("Welcome to 'Guess the Number'!")
    player_name = input("Enter your name: ")
    player = Player(player_name)

    game = Game(1, 100)

    while not game.is_game_over():
        guess = player.get_guess()
        result = game.make_guess(guess)
        print(result)

    print("Thank you for playing!")


if __name__ == "__main__":
    main()

import random

class Item:
    def __init__(self, name, description):
        self.name = name
        self.description = description

class Enemy:
    def __init__(self, name, health):
        self.name = name
        self.health = health

    def is_alive(self):
        return self.health > 0

    def take_damage(self, damage):
        self.health -= damage

class Room:
    def __init__(self, name, description):
        self.name = name
        self.description = description
        self.items = []
        self.enemy = None

    def add_item(self, item):
        self.items.append(item)

    def set_enemy(self, enemy):
        self.enemy = enemy

class Player:
    def __init__(self, name):
        self.name = name
        self.health = 100
        self.inventory = []

    def take_damage(self, damage):
        self.health -= damage

    def collect_item(self, item):
        self.inventory.append(item)

    def is_alive(self):
        return self.health > 0

class Game:
    def __init__(self):
        self.player = None
        self.rooms = {}
        self.current_room = None

    def setup(self):
        self.player = Player(input("Enter your name: "))

        # Create rooms
        room1 = Room("Hall", "A dimly lit hall.")
        room2 = Room("Kitchen", "A smelly kitchen.")
        room3 = Room("Cave", "A dark, damp cave.")

        # Add items to rooms
        room1.add_item(Item("Flashlight", "A useful tool to see in the dark."))
        room2.add_item(Item("Knife", "A sharp kitchen knife."))
        room3.set_enemy(Enemy("Goblin", 30))

        # Connect rooms
        self.rooms = {
            "Hall": room1,
            "Kitchen": room2,
            "Cave": room3,
        }

        self.current_room = room1

    def play(self):
        while self.player.is_alive():
            print(f"\nYou are in the {self.current_room.name}.")
            print(self.current_room.description)

            if self.current_room.items:
                print("You see: " + ", ".join(item.name for item in self.current_room.items))
            if self.current_room.enemy:
                print(f"A wild {self.current_room.enemy.name} appears!")

            command = input("What do you want to do? (explore/take/fight/exit) ").lower()

            if command == "explore":
                self.explore()
            elif command == "take":
                self.take_item()
            elif command == "fight":
                self.fight()
            elif command == "exit":
                print("Thanks for playing!")
                break
            else:
                print("Invalid command.")

    def explore(self):
        next_room = input("Which room do you want to go to? (Kitchen/Cave) ")
        if next_room in self.rooms:
            self.current_room = self.rooms[next_room]
        else:
            print("Room not found!")

    def take_item(self):
        if self.current_room.items:
            item = self.current_room.items.pop()
            self.player.collect_item(item)
            print(f"You took the {item.name}.")
        else:
            print("There are no items here.")

    def fight(self):
        if self.current_room.enemy:
            enemy = self.current_room.enemy
            print(f"You are fighting {enemy.name}!")

            while enemy.is_alive() and self.player.is_alive():
                action = input("Do you want to (attack/run)? ").lower()
                if action == "attack":
                    damage = random.randint(5, 20)
                    enemy.take_damage(damage)
                    print(f"You dealt {damage} damage to {enemy.name}.")
                    if enemy.is_alive():
                        enemy_damage = random.randint(5, 15)
                        self.player.take_damage(enemy_damage)
                        print(f"{enemy.name} dealt {enemy_damage} damage to you.")
                elif action == "run":
                    print("You ran away!")
                    break
                else:
                    print("Invalid action.")

            if not enemy.is_alive():
                print(f"You defeated {enemy.name}!")
                self.current_room.enemy = None
        else:
            print("There is no enemy here to fight.")

def main():
    game = Game()
    game.setup()
    game.play()

if __name__ == "__main__":
    main()


import pygame

pygame.init()
screen = pygame.display.set_mode((400, 500))
done = False

while not done:
    for event in pygame.event.get():
        if event.type == pygame.QUIT:
            done = True

    pygame.display.flip()

pygame.quit()


class Sphere:
    def __init__(self, radius):
        self.radius = radius

    def calculate_volume(self):
        return (4/3) * math.pi * (self.radius ** 3)

#Create an instance of the Sphere class
radius = float(input("Enter the radius of the sphere: "))
my_sphere = Sphere(radius)

#Calculate and print the volume of the sphere
volume = my_sphere.calculate_volume()
print(f"Volume of the sphere with radius {my_sphere.radius} is: {volume:.2f} cubic units.")

import math

#Define the Sphere class
class Sphere:
    def __init__(self, radius):
        self.radius = radius

    def calculate_volume(self):
        return (4/3) * math.pi * (self.radius ** 3)

#Create an instance of the Sphere class
my_sphere = Sphere(5)

#Calculate and print the volume of the sphere
volume = my_sphere.calculate_volume()
print(f"Volume of the sphere with radius {my_sphere.radius} is: {volume:.2f} cubic units.")

























