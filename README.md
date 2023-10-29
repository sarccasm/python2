n = int(input("Введіть значення n: "))

perestanovka = list(range(1, n+1))

for i in range(n):
    if perestanovka[i] == i + 1:
        print("Число", i + 1, "є натуральним, що j = i")



