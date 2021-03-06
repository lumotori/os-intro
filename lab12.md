# **РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ**


### **Факультет физико-математических и естественных наук**
### **Кафедра прикладной информатики и теории вероятностей**

---

# **ОТЧЕТ** 
# **ПО ЛАБОРАТОРНОЙ РАБОТЕ № 	10**
### дисциплина:	Операционные системы


### Студент: Казакова Виктория Алексеевна 
### Группа: НФИбд-01-20

###  **Москва**
### 2021

---
## **Цель работы:** 
### Изучить основы программирования в оболочке ОС UNIX. Научится писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

---

## **Ход работы**

---

### **1.**	Используя команды getopts grep (предварительно создала текстовый файл file.txt и скрипт lab12.sh), написала командный файл (рис.1-2), который анализирует командную строку с ключами: 
- -iinputfile — прочитать данные из указанного файла; 
- -ooutputfile — вывести данные в указанный файл; 
- -pшаблон — указать шаблон для поиска; 
- -C — различать большие и малые буквы; 
- -n — выдавать номера строк.

![](https://sun9-73.userapi.com/impg/LsEdjultXMKryLRPBkzUWLnFzEl9yFdBh2RkWQ/bosk24gYLGw.jpg?size=661x174&quality=96&sign=1db8197ff78d0c784a1fee0c89c31380&type=album)

*(рис.1 текстовый файл)*

![](https://sun9-61.userapi.com/impg/x4ZWwuiO6u3J5jVBqQ956gr6ffT5_a_K51XrSQ/N6P4Y9EgFtc.jpg?size=666x700&quality=96&sign=17f0c1b74d0b47a263ab768923963bef&type=album)

*(рис.2 код программы)*

---

### **2.**	Написала на языке Си программу, которая вводит число и определяет, является ли оно больше нуля, меньше нуля или равно нулю. Затем программа завершается с помощью функции exit(n), передавая информацию в коде завершения в оболочку (рис.3-5);

![](https://sun9-3.userapi.com/impg/0hnDxFKrB6tKNsXH6JMIj9TODPX7CGK-v0Qn4w/jXsJ8JHUaxo.jpg?size=657x313&quality=96&sign=29a7aa38559822820314415472e84dbc&type=album)

*(рис.3 программа на Си)*

![](https://sun9-13.userapi.com/impg/VW9zHPku0NznilbPSas2GxxSUJCQ5wuDl3M-Mw/qNaaT3GrqtA.jpg?size=684x282&quality=96&sign=acbea0d58f7ce38355ea27b9d5ca48fc&type=album)

*(рис.4 вывод данных)*

![](https://sun9-34.userapi.com/impg/FZ7YgKNbAaY1s3DaeV1QrhQIOqfcfeXsj0181Q/jm0QKYIvNOY.jpg?size=453x199&quality=96&sign=cfede2bd24f676e0be80062bd79eaff6&type=album)

*(рис.5 работа программы)*

---

### **3.**	Написала командный файл, создающий указанное число файлов, пронумерованных последовательно от 1 до N (например 1.tmp, 2.tmp, 3.tmp, 4.tmp и т.д.). Число файлов, которые необходимо создать, передаётся в аргументы командной строки. Этот же командный файл должен уметь удалять все созданные им файлы (если они существуют) (рис.6-8);

![](https://sun9-14.userapi.com/impg/_ymnT1g5wDuEFIjyaFDUqgqL5VPfLUNpV5rWvQ/CTbWIxotL8k.jpg?size=573x370&quality=96&sign=5100b3a3ab569fb44bbf4780d2f22cdb&type=album)

*(рис.6 командный файл)*

![](https://sun9-47.userapi.com/impg/E2TJ6sAbHnJKL0NBh4MN395-QjwIg60NXzyEjg/zpuTI4ysjbU.jpg?size=649x169&quality=96&sign=e40a5fbbedad78759cfc2eb36fefa0d3&type=album)

*(рис.7 работа программы)*

![](https://sun1-94.userapi.com/impg/TQSIPI1Y3C_COle5suBuHjoHqHwBqo4JRiVLgQ/z5RtRhxXD7o.jpg?size=634x153&quality=96&sign=5259593f2403d22075728abd71061d66&type=album)

*(рис.8 работы программы)*

---

### **4.**	Написала командный файл, который с помощью команды tar запаковывает в архив все файлы в указанной директории. Модифицировать его так, чтобы запаковывались только те файлы, которые были изменены менее недели тому назад (использовать команду find) (рис.9-10);

![](https://sun9-21.userapi.com/impg/wn0wrpT92BeMNumKkoqJ50kRjt2_Ft0eHanBHw/3Z2VLi6HZy4.jpg?size=660x172&quality=96&sign=93033fa4230d5adfc7576efecc3fc9a8&type=album)

*(рис.9 командный файл)*

![](https://sun9-58.userapi.com/impg/X7lMUvzvhzm4yJ978xgCRcQbmf0hwxUInRqDZg/TDpAqjoeTEY.jpg?size=823x322&quality=96&sign=282292eefa8d948a26a90f15e56ca680&type=album)

*(рис.10 работа программы)*

---

## **Вывод:**
### Изучила основы программирования в оболочке ОС UNIX. Научилась писать более сложные командные файлы с использованием логических управляющих конструкций и циклов.

---

## **Ответы на контрольные вопросы:**

#### **1.** Команда getopts является встроенной командой командной оболочки bash, предназначенной для разбора параметров сценариев. Она обрабатывает исключительно однобуквенные параметры как с аргументами, так и без них и этого вполне достаточно для передачи сценариям любых входных данных.
#
#### **2.** При генерации имен используют метасимволы:
- * произвольная (возможно пустая) последовательность символов;
- ? один произвольный символ;
- [...] любой из символов, указанных в скобках перечислением и/или с указанием диапазона;
- cat f* выдаст все файлы каталога, начинающиеся с "f";
- cat *f* выдаст все файлы, содержащие "f";
- cat program.? выдаст файлы данного каталога с однобуквенными расширениями, скажем "program.c" и "program.o", но не выдаст "program.com";
- cat [a-d]* выдаст файлы, которые начинаются с "a", "b", "c", "d". Аналогичный -эффект дадут и команды "cat [abcd]*" и "cat [bdac]*".
#
#### **3.** Операторы && и || являются управляющими операторами. Если в командной строке стоит command1 && command2, то command2 выполняется в том, и только в том случае, если статус выхода из команды command1 равен нулю, что говорит об успешном ее завершении. Аналогично, если командная строка имеет вид command1 || command2, то команда command2 выполняется тогда, и только тогда, когда статус выхода из команды command1 отличен от нуля.
#
#### **4.** Оператор break завершает выполнение ближайшего включающего цикла или условного оператора, в котором он отображается.
#
#### **5.** Команда true всегда возвращает ноль в качестве выходного статуса для индикации успеха. Команда false всегда возвращает не-ноль в качестве выходного статуса для индикации неудачи. Во всех управляющих конструкциях в качестве логического значения используется код возврата из программы, указанной в качестве условия. Код возврата 0 – истина, любое другое значение – ложь. Программа true – всегда завершается с кодом 0, false – всегда завершается с кодом 1.
#
#### **6.** Введенная строка означает условие существования файла man$s/$i.$s
#
#### **7.** Цикл While выполняется до тех пор, пока указанное в нем условие истинно. Когда указанное условие становится ложным - цикл завершается. Цикл Until выполняется до тех пор, пока указанное в нем условие ложно.

---

### ***Библиография:***

- Лабораторная работа 11 https://esystem.rudn.ru/pluginfile.php/1142232/mod_resource/content/2/008-lab_shell_prog_1.pdf
- Лабораторная работа 12 https://esystem.rudn.ru/pluginfile.php/1142235/mod_resource/content/3/009-lab_shell_prog_2.pdf