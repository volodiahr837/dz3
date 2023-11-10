def pora_roku(temperatura):
    if temperatura >= 25:
        return 'Літо:Футболка та шорти'
    elif 15 <= temperatura < 25:
        return 'Осінь:Світшот та джинси'
    elif 5 <= temperatura < 15:
        return 'Весна:Легка куртка та джинси'
    else:
        return 'Зима:Тепла куртка, шапка та рукавички'
temperatura = float(input('Введіть температуру:'))
odyag = pora_roku(temperatura)
print(f'odyag:{odyag}')
