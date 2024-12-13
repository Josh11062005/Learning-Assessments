```python
class MLHero():
    def __init__(self, name, role):
        self.name = name
        self.role = role

    def describe(self):
        return f"{self.name} is a/an {self.role} hero."

    def __str__(self):
        return f"{self.name} is a/an {self.role} hero."

mage = MLHero("Kagura", "Mage")
marksman = MLHero("Lesley", "Marksman")

print(mage.name)
print(mage.role)
print(mage)
print(marksman.name)
print(marksman.role)
print(marksman)
```python