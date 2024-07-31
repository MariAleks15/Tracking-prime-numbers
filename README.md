def is_prime(n):
    if n <= 1:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True

# Получаем число от пользователя
number = int(input("Введите число: "))

if is_prime(number):
    print(f"{number} является простым числом.")
else:
    print(f"{number} не является простым числом.")
# Tracking-prime-numbers
This code determines whether the number entered by the user is a prime number.
