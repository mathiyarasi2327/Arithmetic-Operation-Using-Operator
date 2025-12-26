a = int(input("Enter 1st number: "))
b = int(input("Enter 2nd number: "))
c = input("Enter the operator (+, -, *, /): ")

print("The result is:", end=" ")

if c == '+':
    print(a + b)
elif c == '-':
    print(a - b)
elif c == '/':
    print(a / b)
elif c == '*':
    print(a * b)
else:
    print("Error: Wrong operator entered")

OUTPUT:

Enter 1st number: 10
Enter 2nd number: 11
Enter the operator (+, -, *, /): /
The result is: 0.9090909090909091
