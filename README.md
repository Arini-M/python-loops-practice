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
