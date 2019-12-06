# Digital Concept Tutorial: Making an Array in Python
## Author: Shawn Nguyen
### An array is a variable that gives you the ability to hold more than one variable within a variable at a time. By doing this, it helps save time and with organization.
#### Target Audience: Beginner Level

___

**Scenario:** You work at food market that carries multiple categories of food items. You were assigned to separate the items by categories through a Python code to see what type of items the store carries.

- Items: Snacks, Fruits, Meats, Vegetables, Grains, and Dairy

**Example:** Creating the array

`foodCategories = ["Snacks", "Fruits", "Vegetables", "Grains", "Dairy"]`

- "foodCategories" is the name of the array. It can be named whatever you wish it to be.

- The array index starts at zero (0). Meaning the index of Snacks would be zero (0) since it is the first one in the list of the array.

**Example:** Accessing an element of an array

`x = foodCategories[1]`

- "x" is just the name of the variable. It can be named whatever you wish it to be.

- "foodCategories" calls for the array foodCategories.

- "[1]" calls for the string in the index one (1) of the array Brands.

**Example:** Printing the array

*Printing a specific brand:*

```
foodCategories = ["Snacks", "Fruits", "Vegetables", "Grains", "Dairy"]

x = foodCategories[1]

print("Selected food category:")

print(x)
```

*Output:*

```
Food category selected: Fruits
```

___

*Printing all brands:*

```
foodCategories = ["Snacks", "Fruits", "Vegetables", "Grains", "Dairy"]

print("All food categories:")

for x in foodCategories:
  print(x)
```

*Output:*

```
All food categories:
Snacks
Fruits
Vegetables
Grains
Dairy
```

___

**TRY IT YOURSELF!**

**Scenario:** You work at a computer parts store and just got a new shipment of parts. You are assigned to organization all the parts into different categories within a Python code.

- Computer Parts: CPU, GPU, Motherboard, Memory, Storage, Cases, Display, Keyboard, and Mouse

Then print out the outputs!
>>>>>>> First Commit
