# python-multiples-of-3

# Python program to display all multiples of 3 within the range 10 to 50

print("Multiples of 3 from 10 to 50 are:")

for i in range(10, 51):  # Include 50
    if i % 3 == 0:
        print(i, end=" ")


OUTPUT:

Multiples of 3 from 10 to 50 are:
12 15 18 21 24 27 30 33 36 39 42 45 48
