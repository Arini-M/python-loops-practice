# python-loops-practice
# Armstrong Number

num = int(input("Enter a number: "))

temp = num
sum_of_digits = 0

while temp > 0:
    digit = temp % 10
    sum_of_digits += digit ** 3
    temp //= 10

if sum_of_digits == num:
    print(num, "is an Armstrong Number")
else:
    print(num, "is not an Armstrong Number")



# Number Guessing Game

secret_number = 7

while True:
    guess = int(input("Guess the number (1-10): "))

    if guess == secret_number:
        print("Congratulations! You guessed correctly.")
        break
    else:
        print("Wrong guess. Try again.")



# Multiplication Tables Generator

num = int(input("Enter a number: "))

print("Multiplication Table of", num)

for i in range(1, 11):
    print(num, "x", i, "=", num * i)
