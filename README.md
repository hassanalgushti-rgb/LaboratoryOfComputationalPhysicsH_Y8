#  number1 Part (a)
for i in range(1, 101):          # Loop from 1 to 100 (inclusive)
    if i % 3 == 0 and i % 5 == 0:   # If number divisible by 3 and 5
        print("MickeyMouse")
    elif i % 3 == 0:               # If only divisible by 3
        print("Mickey")
    elif i % 5 == 0:               # If only divisible by 5
        print("Mouse")
    else:
        print(i)                   # Otherwise print the number

