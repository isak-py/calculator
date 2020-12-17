# calculator

operations = input("Что делаем (+, -, *, /, //, %, **) ? : ")
num1 = int(input("Введите первое число: "))
num2 = int(input("Введите втрое число: "))
if operations == "+":
    ans = num1 + num2
    print("Результат: ", ans)

elif operations == "-":
    ans = num1 - num2
    print("Результат: ", ans)

elif operations == "*":
    ans = num1 * num2
    print("Результат: ", ans)

elif operations == "/":
    ans = num1 / num2
    print("Результат: ", ans)

elif operations == "//":
    ans = num1 // num2
    print("Результат: ", ans)

elif operations == "%":
    ans = num1 % num2
    print("Результат: ", ans)

elif operations == "**":
    ans = num1 ** num2
    print("Результат: ", ans)  

else:
    print("Выбрана неверная операция ")
