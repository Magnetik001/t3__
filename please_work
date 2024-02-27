dct = {'Сила': 0,'Интеллект': 0,'Ловкость': 0}
print(dct)
n = 10
while n > 0:
    print(n)
    ans1 = input('Введите хар-ку: ').title()
    ans2  = int(input('Введите количество очков: '))

    if ans1 in dct:
        if n - ans2 >= 0:
            dct[ans1] += ans2
            n -= ans2
        else:
            print('Неверно')
    else:
        print('Неверно')

    print(dct)

for i,j in dct.items():
    print(f'{i}: {j}')
