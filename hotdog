people = int(input("Enter the number of people attending the cookout: "))
perperson = int(input("Enter the number of hot dogs each person will eat: "))

total = people * perperson
hotdogspack = 10
bunspack = 8

packshotdogs = (total + hotdogspack - 1) // hotdogspack
packsbuns = (total + bunspack - 1) // bunspack

leftoverhotdogs = packshotdogs * hotdogspack - total
leftoverbuns = packsbuns * bunspack - total

print("\n--- Cookout Preparation Summary ---")
print(f"Minimum number of hot dog packages required: {packshotdogs}")
print(f"Minimum number of hot dog bun packages required: {packsbuns}")
print(f"Number of hot dogs that will be left over: {leftoverhotdogs}")
print(f"Number of hot dog buns that will be left over: {leftoverbuns}")