# NAVI
print('Как расшифровывается ВОЗ?')
print('1-Всемирная организация здравоохранения')
print('2-Всероссийская организация защиты')
print('3-Всероссийская особая здравница')
print('4-Владение особого значения')

while True:
    try:
        var = int(input())
        break
    except:
        print('Ошибка! Введите номер правильного ответа')
        

if var == 1:
    print('Абсолютно верно!')
else:
    print('Нет. ВОЗ - это Всемирная организация здравоохранения')

