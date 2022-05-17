<br/> https://stepik.org/course/58852/syllabus <br/>
<br/>"Поколение Python": курс для начинающих Курс с кучей тренировочных задач, удобный как для самостоятельного изучения, так и для работы в группе в рамках внеурочной деятельности. <br/>
# 2  Ввод-вывод данных<br/>
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
![image](https://user-images.githubusercontent.com/97594290/168879672-1d39967a-795d-476b-8852-ad4e3976b860.png)<br/>

# 2.3 Параметры sep и end<br/>
![Параметры sep и end](https://user-images.githubusercontent.com/97594290/165526228-7902d9fb-a755-49a3-9b42-00a830a7c53b.png)
<br/>Код№1 - print('I', 'like', 'Python', sep='***')<br/>
<br/>Код№2 - a=input() b=input() c=input() d=input() print(b, c, d, sep=a)<br/>
<br/>Код№3 - name=input() print('Привет,', name, end='!')<br/>
![image](https://user-images.githubusercontent.com/97594290/168879631-eef951f6-d09c-48f7-9cbc-a7d8ace739e9.png)<br/>

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
![image](https://user-images.githubusercontent.com/97594290/168879571-3bfd8c3b-c6ef-4340-a102-68e2e9fb0c55.png)<br/>

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
![image](https://user-images.githubusercontent.com/97594290/168879527-b63fe18d-5f49-438b-b974-cf338c531ba4.png)<br/>

# 4  Условный оператор<br/>
# 4.1 Выбор из двух</b>
<br/>![image](https://user-images.githubusercontent.com/97594290/168315605-07bf526f-a24b-4633-8c90-fb36dd61d21b.png)<br/>
<br/>Код№1 - a = input() b = input() if a == b: print('Пароль принят') else: print('Пароль не принят')<br/>
<br/>Код№2 - a = int(input()) if a % 2 == 0:print('Четное') else:print('Нечетное')<br/>
<br/>Код№3 - a = int(input()) b = a // 1000 c = a // 100 - (a // 1000 * 10) d = (a % 100 - a % 10) / 10 e = a % 10 if b + e == c - d: print('ДА') else: print('НЕТ')<br/>
<br/>Код№4 - age = int(input()) if age >= 18: print('Доступ разрешен') else: print('Доступ запрещен')<br/>
<br/>Код№5 - a = int(input()) b = int(input()) c = int(input()) if b - a == c - b: print('ДА') else: print('НЕТ ')<br/>
<br/>Код№6 - a = int(input()) b = int(input()) if a > b: print(b) else: print(a)<br/>
<br/>Код№7 - a = int(input()) b = int(input()) c = int(input()) d = int(input()) e = min(a, b, c, d) print( д)<br/>
<br/>Код№8 - a = int(input()) if a <= 13: print('детство') elif a >= 14 и a <= 24: print('молодость') elif a >= 25 и a <= 59: print('зрелость') elif a >= 60: print('старость')<br/>
<br/>Код№9 - a = int(input()) b = int(input()) c = int(input()) d = int() d = 0, если a > 0: d = d + a, если b > 0 : d = d + b, если c > 0 d = d + c print(d)<br/>
![image](https://user-images.githubusercontent.com/97594290/168879477-b5311dfb-7443-4ec4-a1b6-053d6da92f70.png)<br/>

# 4.2 Логические операции</b>
<br/>![image](https://user-images.githubusercontent.com/97594290/168315772-4881dd28-6bef-4c47-a318-ec2267db627a.png)<br/>
<br/>Код№1 -a = int(input()) if a > -1 and a < 17: print('Принадлежит') else: print('Не принадлежит')<br/>
<br/>Код№2 -n = int(input()) if not (-3 < n < 7): print('Принадлежит') else: print('Не принадлежит')<br/>
<br/>Код№3 - a = int(input()) if (a > -30 and a <= -2) or (a > 7 and a <= 25): print('Принадлежит') else: print('Не принадлежит')<br/>
<br/>Код№4 - a = int(input()) if (a % 7 == 0 or a % 17 == 0) and (a >= 1000 and a <= 9999): print('YES') else: print('NO')<br/>
<br/>Код№5 - a = int(input()) b = int(input()) c = int(input()) if (a < (b + c)) and (b < (a + c)) and (c < (a + b)): print("YES") else: print("NO")<br/>
<br/>Код№6 - import calendar print("YES" if calendar.isleap(int(input())) else "NO")<br/>
<br/>Код№7 - a, b, c, d = int(input()), int(input()), int(input()), int(input()) if a == c or b == d: print('YES') else: print('NO')<br/>
<br/>Код№8 - a, b, c, d = int(input()), int(input()), int(input()), int(input()) if (-1 <= a - c <= 1) and (-1 <= b - d <= 1): print('YES') else: print('NO')<br/>
![image](https://user-images.githubusercontent.com/97594290/168879232-1e107af0-64f3-4aa2-9534-229ae25c5a84.png)<br/>

# 4.3 Вложенные и каскадные условия</b>
<br/>![image](https://user-images.githubusercontent.com/97594290/168315831-50e25ed6-7a58-4ec7-bde7-c85b3b141636.png)<br/>
<br/>Код№1 - a = int(input()) b = int(input()) если b > a: print("ДА") если a > b: print("НЕТ") если a == b: print( "Не знаю")<br/>
<br/>Код№2 - a = int(input()) b = int(input()) c = int(input()) if a == b == c: print("Равносторонний") if (a == b или a == c или b == c) и (a != c или a != b или b != c): print("Равнобедренный"), если a != b и a != c и c != b: print("Разносторонний")<br/>
<br/>Код№3 - a, b, c = int(input()), int(input()), int(input()) если a < b < c или a > b > c: print(b) elif b < c < a или b > c > a: print(c) else: print(a)<br/>
<br/>Код№4 - m = int(input()) if m == 2: print('28') elif m <= 7: print(30 + m%2 ) else: print(31 - m%2 )<br/>
<br/>Код№5 - n = int(input()) if n < 60: print('Легкий вес') elif n < 64: print('Первый полусредний вес') elif n < 69: print('Полусредний вес')
<br/>Код№6 - a, b = int(input()), int(input()) s = input() if s == '+': print(a + b) elif s == '-': print( a - b) elif s == '*': print(a * b) elif s == '/': if b == 0: print('На ноль делиться нельзя!') else: print(a / b) else: print('Неверная операция')<br/>
<br/>Код№7 - color1, color2 = input(), input() if color1 == 'красный' и color2 == 'синий' или (color1 == 'синий' и color2 == 'красный'): print('фиолетовый ') elif color1 == 'желтый' and color2 == 'синий' или (color1 == 'синий' and color2 == 'желтый'): print('зеленый') elif color1 == 'красный' and color2 == 'желтый' или (color1 == 'желтый' и color2 == 'красный'): print('оранжевый') elif color1 == 'красный' и color2 == 'красный' или color1 == 'желтый' и color2 = = 'желтый' или color1 == 'синий' и color2 == 'синий': print(color1) else: print('ошибка цвета')<br/>
<br/>Код№8 - n = int(input()) если n < 0 или n > 36: print('ошибка ввода') elif n == 0: print('зеленый') elif 1 <= n <= 10: if n % 2 == 0: print('черный' ) else: print('красный') elif 11 <= n <= 18: if n % 2 == 0: print('красный') else: print('черный') elif 19 <= n <= 28: if n % 2 == 0: print('черный') else: print('красный') elif 29 <= n <= 36: if n % 2 == 0: print('красный') else: print('черный ')<br/>
<br/>Код№9 - a1, b1, a2, b2 = int(input()), int(input()), int(input()), int(input()) if a2 < a1: if b2 < a1: print('пустое множество' elif b2 == a1: print(b2) elif a1 < b2 <= b1: print(a1, b2) elif b2 > b1: print(a1, b1 ) elif a2 == a1: if b2 <= b1: print(a2, b2) else: print(a2, b1) elif a2 < b1: if b2 <= b1: print(a2, b2) else: print(a2, b2) b1) elif a2 == b1: print(a2) else: print('пустое множество')<br/>
![image](https://user-images.githubusercontent.com/97594290/168879185-9e1445ac-453b-468c-889b-a0b1882e6e9f.png)<br/>

# 6 Типы данных<br/>
# 6.1 Числовые типы данных: int, float
<br/>![image](https://user-images.githubusercontent.com/97594290/168317430-77643657-a7ce-4e7b-bc29-fc8e02f662b8.png)<br/>
<br/>Код №1 - print(0.5 * float(input()) * float(input()))<br/>
<br/>Код №2 - a = float(input()) b = float(input()) c = float(input()) print(a/(c+b))<br/>
<br/>Код №3 - n = float(input()) if n == 0: print('Обратного числа не существует') else: print(1 / n)<br/>
<br/>Код №4 - F = float(input()) print(5 / 9 * (F - 32))<br/>
<br/>Код №5 - t = int(input()) print(min(2, t) * 10.5 + max(t - 2, 0) * 4)<br/>
<br/>Код №6 - 6x = float(input()) print(int(x*10)%10)<br/>
<br/>Код №7 - a = float(input()) print(a - int(a))<br/>
<br/>Код №8 - a, b, c, d, e = int(input()), int(input()), int(input()), int(input()), int(input()) print('Наименьшее число =', min(a, b, c, d, e)) print('Наибольшее число =',  max(a, b, c, d, e))<br/>
<br/>Код №9 - a, b, c = int(input()), int(input()), int(input()) print(max(a, b, c)) print(a + b + c - min(a, b, c) - max(a, b, c)) print(min(a, b, c))<br/>
<br/>Код №10 - x = int(input()) a = x % 10b = x // 10 % 10c = x // 100if a + b + c == 2 * max(a, b, c): print("Число интересное") else: print("Число неинтересное")<br/>
<br/>Код №11 - print(sum((abs(float(input())) for i in range(5))))<br/>
<br/>Код №12 - p1, p2, q1, q2 = [int(input()) for _ in range(4)] print(abs(p1 - q1) + abs(p2 - q2))<br/>
![image](https://user-images.githubusercontent.com/97594290/168878953-5f96b3a4-4091-4dfd-9ee2-2b38edc42cf4.png)<br/>

# 6.2  Строковый тип данных
![image](https://user-images.githubusercontent.com/97594290/168319184-27237deb-ff62-47a4-a588-1c2edb3730e7.png)<br/>
<br/>Код №1 - print('''"Python is a great language!", said Fred. "I don't ever remember having this much fun before."''')<br/>
<br/>Код №2 - a = input() b = input() print(f"Hello {a} {b}! You just delved into Python")<br/>
<br/>Код №3 - c = input() print(f"Футбольная команда {c} имеет длину", len(c), "символов")<br/>
<br/>Код №4 - a, b, c = str(input()), str(input()), str(input()) print(min(a, b, c, key=len )) print(max(a, b, c, key=len ))<br/>
<br/>Код №5 - a, b, c = len(input()), len(input()), len(input()) if a + b + c == (min(a, b, c) + max(a, b, c))/2*3: print("YES") else: print("NO")<br/>
<br/>Код №6 - print('YES' if 'синий' in input() else 'NO')<br/>
<br/>Код №8 - s = input() print("YES" if "суббота" in s or "воскресенье" in s else "NO")<br/>
<br/>Код №9 - email = input() print('YES' if all(_ in email for _ in ('@', '.')) else 'NO')<br/>
![image](https://user-images.githubusercontent.com/97594290/168878917-42c42aa8-7524-4e66-a37b-68fa58cc2cb5.png)<br/>

# 6.3  Модуль math!
![image](https://user-images.githubusercontent.com/97594290/168318748-ec99c41f-1a53-4ac7-90c7-961ca9e5a427.png)<br/>
<br/>Код №1 import math x1, x2, y1, y2 = float(input()), float(input()), float(input()), float(input()) print(math.hypot(x1 - y1, x2 - y2))<br/>
<br/>Код №2 R = float(input()) from math import pi print(pi*R**2) print(2*pi*R)<br/>
<br/>Код №3 import math a, b  = float(input()), float(input()) sab, pab = a + b, a * b print(sab / 2) print(math.sqrt(pab)) print(2 * pab / sab) print(math.sqrt((a**2 + b**2) / 2))<br/>
<br/>Код №4 from math import * x = radians(float(input())) print(sin(x) + cos(x) + tan(x)**2)<br/> <br/>import math a = float(input()) print(math.ceil(a)+math.floor(a))<br/>
<br/>Код №5 from math import * a = float(input()) b = float(input()) c = float(input()) d = b**2-4*a*c if d < 0: print('Нет корней') elif d == 0: print(-b / (2*a)) elif d > 0: x1 = (-b - d ** 0.5) / (2*a) x2 = (-b + d ** 0.5) / (2*a) print(min(x1, x2)) print(max(x1, x2))<br/>
<br/>Код №6 from math import *n, a = float(input()), float(input()) ans = (n * pow(a, 2)) / (4 * tan(pi / n)) print(ans)<br/>
![image](https://user-images.githubusercontent.com/97594290/168878870-3741bf94-0a97-4032-ab16-e3bc0bbb7f92.png)<br/>
# 7 Циклы for и while<br/>

# 7.1  Цикл for
![image](https://user-images.githubusercontent.com/97594290/168322525-8ef63ac4-8221-4e99-aae5-49c290f65bf0.png)<br/>
<br/>Код №1 - print('Python is awesome!\n' * 10) <br/>
<br/>Код №2 - a = input() b = int(input()) for i in range(b): print(a)<br/>
<br/>Код №3 - for i in range(6): print('A' * 3) for i in range(5): print('B' * 4) print('E') for i in range(9): print('T' * 5) print('G')<br/>
<br/>Код №4 - n = int(input()) for i in range(n): print('*' * 19)<br/>
<br/>Код №5 - a = input() for b in range(10): print(b, a)<br/>
<br/>Код №6 - n=int(input()) for i in range(n+1): print('Квадрат числа', i, 'равен', i**2)<br/> 
<br/>Код №7 - g = int(input()) for f in range(g, 0, -1): print("*" * f)<br/>
<br/>Код №8 - m, p, n = float(input()), float(input()), int(input()) [print(i + 1, m * (1 + p / 100) ** (i)) for i in range(n)]<br/>
![image](https://user-images.githubusercontent.com/97594290/168878590-ceb72176-96c8-482f-9a68-185797925099.png)<br/>

# 7.2   Цикл for: функция range
![image](https://user-images.githubusercontent.com/97594290/168877712-8363a31b-a2cd-469c-8270-601dbde1c2e7.png)<br/>
<br/>Код №1 - c = int(input()) v = int(input()) for i in range (c, v+1): print(i) <br/>
<br/>Код №2 - n, m = int(input()), int(input()) if n < m: for i in range(n, m + 1): print(i) else: for i in range(n, m - 1, -1): print(i)<br/>
<br/>Код №3 - m, n = int(input()), int(input()) start = ((m - 1) // 2) * 2 + 1 for i in range (start, n - 1, -2): print(i)<br/>
<br/>Код №4 - m, n = int(input()), int(input()) for i in range(m, n + 1): if i % 17 == 0 or i % 10 == 9 or i % 15 == 0: print(i)<br/>
<br/>Код №5 - a = int(input()) for i in range(1, 11): print(f"{a} x {i} = {i*a}")<br/>
![image](https://user-images.githubusercontent.com/97594290/168878531-d1bd488f-76d6-454f-b5e6-9709ab0d01a9.png)<br/>

