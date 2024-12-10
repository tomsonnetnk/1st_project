# 1st_project
correct = 0
incorrect = 0

print('Домашнее задение. Загадка №1.')
print('Какая версия языка сейчас актуальна?')
while True:
    s = input('Введите ответ и нажмите Enter: ')
    if s.lower() == 'python3':
        print('Ответ:', s, 'верен!')
        correct += 1
        break
    else:
        print('Неверный ответ')
        incorrect += 1
print()
print('Домашнее задение. Загадка №2.')
print('Какая кодировка используется в строках?')
while True:
    s = input('Введите ответ и нажмите Enter: ')
    if s.lower() == 'utf8':
        print('Ответ:', s, 'верен!')
        correct += 1
        break
    else:
        print('Неверный ответ')
        incorrect += 1
print()
print('Домашнее задение. Загадка №3.')
print('Сколько значений есть у bool?')
while True:
    s = input('Введите ответ и нажмите Enter: ')
    if s.lower() == '2':
        print('Ответ:', s, 'верен!')
        correct += 1
        break
    else:
        print('Неверный ответ')
        incorrect += 1
print()
