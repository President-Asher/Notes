A python class is like a blueprint for creating objects in your code.
---
Example 1.
class Superhero:
    species = "Human"
    # Initializer / Constuctor
    `def __init__(self, name, power, net_worth):
        self.name = name
        self.power = power
        self.net_worth = net_worth`

    # Methods
    def fight_labatt(self):
        return f"{self.name} wants to fight Labatt, but can't find him."
    
    def fight_railroad_baron(self):
        return f"{self.name} wants to fight the railroad baron, but can't find him."
    
    def fight_goddess_hel(self):
        return f"{self.name} wants to fight the goddess Hel, but can't find her."
    
    def angry(self):
        return f"{self.name} is feeling angered."

# The heros (these are all characters in a comic book im making.)
hero1 = Superhero("Archer Kole", "Archer Kole is too cool for superpowers.", 150000)
hero2 = Superhero("Diablo", "Controls the fires of hell and can send people to hell.", 5000)
hero3 = Superhero("Bear Shield", "He wields the ancient bear shield.", 0)

print(hero1.fight_labatt())
print(hero1.angry())
print(hero2.fight_railroad_baron())
print(hero2.angry())
print(hero3.fight_goddess_hel())
print(hero3.angry())

[ninja](https://sekol.ninja)
