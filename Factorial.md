# factorial
while True:
    a=int(input("Number: "))
    if a == -1:
        break
    fat=1
    while a > 1:
        fat=fat*a
        a=a-1
    print (fat)
