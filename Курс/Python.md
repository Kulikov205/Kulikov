<br/> https://stepik.org/course/58852/syllabus <br/>
<br/>"Поколение Python": курс для начинающих Курс с кучей тренировочных задач, удобный как для самостоятельного изучения, так и для работы в группе в рамках внеурочной деятельности. <br/>
# 2.1 Ввод-вывод данных<br/>
![Opera Снимок_2022-04-27_154312_stepik org](https://user-images.githubusercontent.com/97594290/165520579-e753d70a-c95d-449c-9e9d-9c3515142c5b.png)<br/>
# 2.2 Команды print и input<br/>
![Print](https://user-images.githubusercontent.com/97594290/165521887-c3048e65-55d9-4062-abf2-5c435968180b.png)
<br/>Код№1 - print('Здравствуй, мир!')<br/>
<br/>Код№2 - print('4', '8', '15', '16', '23', '42')<br/>
<br/>Код№3 - print('4') print('8') print('15') print('16') print('23') print('42')<br/>
<br/>Код№4 - print('*') print('**') print('***') print('****') print('*****') print('******') print('*******'))<br/>
<br/>Код№5 - name=input() print('Привет,', name)<br/>
<br/>Код№6 - name=input() print(name,'- чемпион!')<br/>
<br/>Код№7 - name1=input() name2=input() name3=input() print(name1) print(name2) print(name3)<br/>
<br/>Код№8 - name3=input() name2=input() name1=input() print(name1) print(name2) print(name3)<br/>
# 2.3 Параметры sep и end<br/>
![Параметры sep и end](https://user-images.githubusercontent.com/97594290/165526228-7902d9fb-a755-49a3-9b42-00a830a7c53b.png)
<br/>Код№1 - print('I', 'like', 'Python', sep='***')<br/>
<br/>Код№2 - a=input() b=input() c=input() d=input() print(b, c, d, sep=a)<br/>
<br/>Код№3 - name=input() print('Привет,', name, end='!')<br/>
# 2.4 Целочисленная арифметика Параметры sep и end<br/>
![Целочисленная арифметика 1](https://user-images.githubusercontent.com/97594290/165527521-38d581cd-a020-4a0c-b848-7eab69b33c1c.png)
<br/>Код№1 - a = int(input()) print(a) print(a + 1) print(a + 2)<br/>
<br/>Код№2 - a = int(input()) b = int(input()) c = int(input()) print(a + b + c)<br/>
<br/>Код№3 - a = int(input()) print('Объем =', a * a * a) print('Площадь полной поверхности =', 6 * a * a)<br/>
<br/>Код№4 - num1 = int(input()) num2 = int(input()) print(3 * (num1+num2) * (num1+num2) * (num1+num2) + 275 * num2 * num2 - 127 * num1 - 41)<br/>
<br/>Код№5 - a = int(input()) print('Следующее за числом', a, 'число:', a + 1) print('Для числа', a, 'предыдущее число:', a - 1)<br/>
<br/>Код№6 - a = int(input()) b = int(input()) c = int(input()) d = int(input()) print(3 * (a + b + c + d))<br/>
<br/>Код№7 - a = int(input()) b = int(input()) print(f"{a} + {b} = {a+b}") print(f"{a} - {b} = {a-b}") print(f"{a} * {b} = {a*b}")<br/>
<br/>Код№8 - a = int(input()) b = int(input()) c = int(input()) d = a + b * (c - 1) print(d)<br/>
<br/>Код№9 - a = int (input()) print(a, 2 * a, 3 * a, 4 * a, 5 * a, sep='---')<br/>
# 2.5 Целочисленная арифметика<br/>
![2](https://user-images.githubusercontent.com/97594290/165764434-d9e07d82-d356-4e94-9343-9c0df9d030fb.png)
<br/>Код№1 - b1 = int(input()) q = int(input()) n = int(input()) print(b1 * q ** (n-1)<br/>
<br/>Код№2 - ab = int(input()) b = ab // 100 print(b)<br/>
<br/>Код№3 - sch = int(input()) fru = int(input()) print(fru//sch) print(fru%sch)<br/>
<br/>Код№4 - ребята = int(input()) print(ребята//2 + ребята%2)<br/>
<br/>Код№5 - a = int(input()) print((a-1) // 4 + 1)<br/>
<br/>Код№6 - min = int(input()) print(min, f'мин - это {min // 60} час {min % 60} минут.')<br/>
<br/>Код№7 - abcd = int(input()) print('Сумма цифр =', abcd//100 + (abcd % 100) // 10 + abcd%10) print('Произведение цифр =', (abcd// 100) * ((abcd % 100) // 10) * (abcd% 10))<br/>
<br/>Код№8 - num = int(input()) a = num % 10 b = (num % 100) // 10 c = num // 100 print(c, b, a, sep = '') print(c, a, b, sep='') print(b, c, a, sep='') print(b, a, c, sep='') print(a, c, b, sep='') print(a, b, c, sep='') <br/>
<br/>Код№9 - a = int(input()) a1 = a // 1000 a2 = (a // 100) % 10 a3 = (a // 10) % 10 a4 = a % 10 print("Цифра в позиции тысяч равна", a1) print("Цифра в позиции сотен равна", a2) print("Цифра в позиции десятков равна", a3) print("Цифра в позиции единиц равна", a4)<br/>
# 4.1 Выбор из двух</b>
