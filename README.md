


import random

print("Welcome to the Fortune Teller!")
name = input(" ")
birthdate = input("(MM/DD/YYYY) ")


fortunes = [
  "You'll have a great day!",
  "Good things are coming your way!",
  "Be careful, something unexpected might happen.",
  "You'll meet someone special soon!",
  "You'll have a wonderful year ahead!"
]

fortune = random.choice(fortunes)


print(f"\nHello {name}, your fortune for being born on {birthdate} is:")
print(fortune)



