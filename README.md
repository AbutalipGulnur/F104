# F104
Room for students
n = int(input())


def factorial(n):
    san = 1
    for i in range(1, n + 1):
        san = san * i

    return san


print(factorial(n))
