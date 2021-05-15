# **РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ**


### **Факультет физико-математических и естественных наук**
### **Кафедра прикладной информатики и теории вероятностей**

---

# **ОТЧЕТ** 
# **ПО ЛАБОРАТОРНОЙ РАБОТЕ № 	6**
### дисциплина:	Операционные системы


### Студент: Казакова Виктория Алексеевна 
### Группа: НФИбд-01-20

###  **Москва**
### 2021

---
## **Цель работы:** 
### Ознакомление с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.

---

## **Ход работы**

### **1.**	Выполнила все примеры, приведённые в первой части описания лабораторной работы:

### ***Пример 1.*** 
Скопировала файл ~/abc1 в файл april и в файл may. Скопировала файлы april и may в каталог monthly. Скопировала файл monthly/may в файл с именем june. Скопировала каталог monthly в каталог monthly.00 (рис.1). Скопировала каталог monthly.00 в каталог /tmp (рис.2);

![](https://sun9-48.userapi.com/impg/03sAPcHE6MAn47UWzn-9JckVes9H_NNCe2-bcw/6G870ChUA2Q.jpg?size=819x246&quality=96&sign=2dd691a1835163c79406822ae1e57ebf&type=album)

*(рис.1)*

![](https://sun9-6.userapi.com/impg/0M7ajbEmWMTTvwWlpRcKy8kGhsjhDCVX_Z8jwQ/-kF-_7sozXs.jpg?size=682x97&quality=96&sign=64913f4ba3c41e464880907acb0ae4ed&type=album)

*(рис.2)*

### ***Пример 2.***
Изменила название файла april на july в домашнем каталоге. Переместила файл july в каталог monthly.00. Переименовала каталог monthly.00 в monthly.01. Переместила каталог monthly.01в каталог reports. Переименовала каталог reports/monthly.01 в reports/monthly (рис.3);

![](https://sun9-51.userapi.com/impg/z-mz6OWhppkz7_MIiiwpBYXxeC33S_OQZUf1Gg/VKS_vyYxPQ0.jpg?size=839x270&quality=96&sign=9c04726c75e1893542757479adac6e64&type=album)

*(рис.3)*

### ***Пример 3.***
Создала файл ~/may с правом выполнения для владельца. Лишила владельца файла ~/may права на выполнение (рис.4). Создала каталог monthly с запретом на чтение для членов группы и всех остальных пользователей (рис.5). Создала файл ~/abc1 с правом записи для членов группы (рис.6);

![](https://sun9-22.userapi.com/impg/__Mpb2Wljx2DZu69zLFQnCZFG3VF7HqTlxrzyQ/lvDuzM-4hGQ.jpg?size=643x214&quality=96&sign=18e1fe025bb207ed93b17b8b5855cdc9&type=album)

*(рис.4)*

![](https://sun9-9.userapi.com/impg/JJW-uRYyruHHIbUAfv9RGZyX1MXecMtzoV8xjw/ZBPLD_ipXr0.jpg?size=693x84&quality=96&sign=ea38dba7742e5bd40ed85a35c46ea23b&type=album)

*(рис.5)*

![](https://sun9-10.userapi.com/impg/CCztL-_JWHlslDvALha8Fm0l4a1cCuRdUm0t1A/yUgiVvKz4Kw.jpg?size=643x79&quality=96&sign=bdf90f3d97936b193c9a501ee007d0dc&type=album)

*(рис.6)*

### ***Пример 4.***
Воспользовалась командой df, которая выведет на экран список всех файловых систем в соответствии с именами устройств, с указанием размера и точки монтирования, для определения объёма свободного пространства на файловой системе (рис.7);

![](https://sun9-17.userapi.com/impg/tkots7-0gW2gbJIDqzAtb35MJXNjbB-WiXNq-Q/sQYfnbETjKg.jpg?size=817x430&quality=96&sign=6421ac524455c8d28250ad8bcfe0c24a&type=album)

*(рис.7)*

С помощью команды fsck проверила целостность файловой системы (рис.8);

![](https://sun9-13.userapi.com/impg/vLfnSh4ym0Dd_hjMit2C0MkfePyZHoaMpaKMnQ/V2t5ijIyTUo.jpg?size=700x109&quality=96&sign=e0b202ee40c7237043d0ead5ee51ad9e&type=album)

*(рис.8)*

---

### **2.**	Выполнила следующие действия, зафиксировав в отчёте по лабораторной работе используемые при этом команды и результаты их выполнения:

### ***2.1.***	Скопировала файл /usr/include/sys/io.h в домашний каталог и назвала его equipment (рис.9). (на моем устройстве данного файла не было, поэтому я заменила его на /usr/include/xorg/isdv4.h (рис.10));

![](https://sun9-45.userapi.com/impg/vOedurz5ktVjvXFXBzaIjtYMJcIDvt_VbyhB2A/MeKjHqg34C0.jpg?size=691x82&quality=96&sign=275bd6be5ec203b7fabcb1e0abf80f4f&type=album)

*(рис.9)*

![](https://sun9-59.userapi.com/impg/B8mSqPfjRSZI4FPEB8n5ne7Gf5WLgAxDPSPW1Q/mkGjArutmFw.jpg?size=732x231&quality=96&sign=bb9eb3c62b3f9d74ed4eba29cd9a4311&type=album)

*(рис.10)*

### ***2.2.***	В домашнем каталоге создала директорию ~/ski.plases (рис.9);

### ***2.3.***	Переместила файл equipment в каталог ~/ski.plases (рис.11);

![](https://sun9-11.userapi.com/impg/GgAsFV4rhIcutBerEaZF-wYhUalPYM_QwgSrkQ/hS6NwhRAEiM.jpg?size=496x55&quality=96&sign=83aa3d05c4be51797949633e4fe48e15&type=album)

*(рис.11)*

### ***2.4.***	Переименовала файл ~/ski.plases/equipment в ~/ski.plases/equiplist (рис.12);

![](https://sun9-61.userapi.com/impg/MvmP9px4OgIv2gWYzkpctlaG6fWCgiV0gNqaFg/7k5wrp1i-2g.jpg?size=727x58&quality=96&sign=506eaf57932d89ed1640c2824ac44f8f&type=album)

*(рис.12)*

### ***2.5.***	Создала в домашнем каталоге файл abc1 и скопировала его в каталог ~/ski.plases, назвала equiplist2 (рис.13);

![](https://sun9-43.userapi.com/impg/bB-SJFz2PBLvrQ_LbL56wQi0BFGfMTrY5OQ4_A/ygBotGbrc8U.jpg?size=742x82&quality=96&sign=08de5de22b4371c760feab51299efa9e&type=album)

*(рис.13)*

### ***2.6.***	Создала каталог с именем equipment в каталоге ~/ski.plases (рис.14);

![](https://sun9-7.userapi.com/impg/X59RBPHNVA8Z573zTS3x_bGgNoZXINLxNl2GFg/QWf4r8nCjJk.jpg?size=519x93&quality=96&sign=47d6b907e604cfed183a1e0e5e23bf21&type=album)

*(рис.14)*

### ***2.7.***	Переместила файлы ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment (рис.15);

![](https://sun9-40.userapi.com/impg/jujwFeqnT-ndWTH--zDs03W6cobp9PemjK7asg/XM-dvwqDa5c.jpg?size=952x52&quality=96&sign=fbc1d97be384646ab1a2bb5947261cf7&type=album)

*(рис.15)*

### ***2.8.***	Создала и переместила каталог ~/newdir в каталог ~/ski.plases (рис.16) и назовите его plans (рис.17);

![](https://sun9-62.userapi.com/impg/2bCxO1a8TlKMwm56oj5eD3QYZpLq9qunfqc_Uw/vNm01bxmJjg.jpg?size=489x45&quality=96&sign=9ee72c985b5d554f1c05aaea3d6c808d&type=album)

*(рис.16)*

![](https://sun9-38.userapi.com/impg/y03xGC4RqHw9lKcXfPBPRJWIzyWMSkm1fpI9ow/uZ9wjnvTxQk.jpg?size=654x58&quality=96&sign=2b8d9024d7a29ee05577ff8281a31f92&type=album)

*(рис.17)*

---

### **3.**	Определила опции команды chmod, необходимые для того, чтобы присвоить перечисленным ниже файлам выделенные права доступа, считая, что в начале таких прав нет:

### ***3.1.***	drwxr--r-- ... australia (рис.18-19);

![](https://sun9-8.userapi.com/impg/D2IaJMIdreAe_PdqxhvmJco94UaYgJsPICA-dg/5DDiJ56b5TQ.jpg?size=649x370&quality=96&sign=d28cc0e51fb044695b7ea73d88764f02&type=album)

*(рис.18 создание файла)*

![](https://sun9-33.userapi.com/impg/-9cX2D8hqHNRsSzRp7rt-LkhCnjYRPwq3KY30Q/sjjcffwiK0g.jpg?size=613x391&quality=96&sign=44472e0e1e0d367d84ed6e033e9b250c&type=album)

*(рис.19 опции chmod)*

### ***3.2.***	drwx--x--x ... play (рис.20-21);

![](https://sun9-1.userapi.com/impg/tTgB2VHthp1IHkM2RyE7F9EUiflia2io0eVj5w/ZosSUxFWTsw.jpg?size=607x405&quality=96&sign=16424606f5dd23c912aabdb7c8e0d42f&type=album)

*(рис.20 создание файла)*

![](https://sun9-61.userapi.com/impg/B-aAU4vO1HW33EiFcU9enGi9vS9O_vqXF7wZOg/uJPlcr7ndy4.jpg?size=619x403&quality=96&sign=31efa48bca4c8bb3814acd839eeb4481&type=album)

*(рис.21 опции chmod)*

### ***3.3.***	-r-xr--r-- ... my_os (рис.22-23)

![](https://sun9-31.userapi.com/impg/sC-IHe_uGPH_NVvPlbOa-jO3s2WtipUhSpmq8g/gSqxiOMr0dQ.jpg?size=595x237&quality=96&sign=de262771d51f64f555a64d13c88fc492&type=album)

*(рис.22 создание файла)*

![](https://sun9-15.userapi.com/impg/9NGyHbkDmxZom9epLBpF9arDkc4qHpw9SMwbgA/5nV9aedlcvE.jpg?size=592x231&quality=96&sign=67f2ecaa098464335a1b3c711af64a56&type=album)

*(рис.23 опции chmod)*

### ***3.4.***	-rw-rw-r-- ... feathers (рис.24);

![](https://sun9-36.userapi.com/impg/ZtVmvNcKlVoeH2MEPgzOKqjFrQEkMDjL1rBUGA/yT3fsHrTuy8.jpg?size=595x177&quality=96&sign=d93c2583c0c56ca341e9d1997e5c9dc4&type=album)

*(рис.24)*

---

### **4.**	Проделала приведённые ниже упражнения, записывая в отчёт по лабораторной работе используемые при этом команды:

### ***4.1.***	Просмотрела содержимое файла /etc/password (на моем устройстве такого файла нет) (рис.25);

![](https://sun9-19.userapi.com/impg/XG_fzkvvsbX5o2w5dtCZo6civrGUPQS5pOCSKA/8uWSMlh1cFw.jpg?size=658x49&quality=96&sign=827b63d301068d5d88817f4d4cd7ffe7&type=album)

*(рис.25)*

### ***4.2.***	Скопировала файл ~/feathers в файл ~/file.old (рис.26);

![](https://sun9-50.userapi.com/impg/rr4w3HNcF81X6Qqtye3AgouReC0arijfH6SWDA/SjwD0CIVUTA.jpg?size=544x55&quality=96&sign=addd116e336c054ffe0d3045d74bdb2c&type=album)

*(рис.26)*

### ***4.3.***	Переместила файл ~/file.old в каталог ~/play (рис.27);

![](https://sun9-69.userapi.com/impg/DECEdMvIsOktTCJKo6YTrlYqlXqbo2Fe_NT_5w/EsJflfFqyao.jpg?size=478x46&quality=96&sign=21307b0521b960a94ccb1a2db3d63cd2&type=album)

*(рис.27)*

### ***4.4.***	Скопировала каталог ~/play в каталог ~/fun (рис.28);

![](https://sun9-13.userapi.com/impg/blPnwN77TaN4wO5Z6pb6DFWJyqcrEljpD06QRg/uCDxhnXNlUo.jpg?size=453x46&quality=96&sign=eb2345442f571160dbd9685f3e0ac5cd&type=album)

*(рис.28)*

### ***4.5.***	Переместила каталог ~/fun в каталог ~/play и назвала его games (рис.29-30); 

![](https://sun9-72.userapi.com/impg/ImLnWNdCwu7YGWgXG6eKSdkyuUu7b0N0QEMB8A/DwXBGtppHXM.jpg?size=414x61&quality=96&sign=5e8196f417593db22d5a42b0b2db01dd&type=album)

*(рис.29 переместила каталог)*

![](https://sun9-72.userapi.com/impg/4H3FLGEORgKZSARvo1U-l8OyPSmG4IRIMpuabA/zJj3aafQVQs.jpg?size=426x96&quality=96&sign=7a91c4e5907ee47c2994b689f1dd4512&type=album)

*(рис.30 поменяла название)*

### ***4.6.***	Лишила владельца файла ~/feathers права на чтение (рис.30);

![](https://sun9-42.userapi.com/impg/1weF1JB5Y5-Kpi1TegQUvxaYivCSqwHYaipsuw/r4qsapYlABY.jpg?size=430x76&quality=96&sign=2ecbaa9ad53b78ed2a2cd2e9a679eb60&type=album)

*(рис.30)*

### ***4.7.***	Что произойдёт, если вы попытаетесь просмотреть файл ~/feathers командой cat? – Если попытаться просмотреть файл ~/feathers командой cat, то выведется: (рис.31);

![](https://sun9-35.userapi.com/impg/eQTAGwnwd1YL9FhT1OrvZTdz4INRcCxHWJUG3w/_SUM1X3Iw14.jpg?size=400x70&quality=96&sign=bedee8fdce317483ae446a306e963873&type=album)

*(рис.31)*

### ***4.8.***	Что произойдёт, если вы попытаетесь скопировать файл ~/feathers? – Если попытаться скопировать файл ~/feathers командой cp, то выведется: (рис.32);

![](https://sun9-25.userapi.com/impg/OFp6idQulRocXx3b_TIUVqRL1iPN09SDTUnAyA/i9px98zo9mY.jpg?size=649x91&quality=96&sign=aa48315462652c6aad2afc5c83da56d5&type=album)

*(рис.32)*

### ***4.9.***	Дала владельцу файла ~/feathers право на чтение (рис.33);

![](https://sun9-11.userapi.com/impg/XE9lHg38mnuUh-ygoGaoFLpcirYK0VQucB1ZnA/pRKwvezOG2U.jpg?size=421x67&quality=96&sign=006bcbe65856ea4c15ddaf89d36dc488&type=album)

*(рис.33)*

### ***4.10.***	Лишила владельца каталога ~/play права на выполнение (рис.34); 

![](https://sun9-21.userapi.com/impg/U7HXPGgkujClXmg_wGHnlKkL5NqvLema3reXyg/9ICB98OTPUE.jpg?size=448x72&quality=96&sign=5bf281f81a987f4becf42ed240ba0b27&type=album)

*(рис.34)*

### ***4.11.***	Перешла в каталог ~/play. Что произошло? – Если попытаться прейти в каталог ~/play командой cd, то выведется: (рис.35);

![](https://sun2.ufanet.userapi.com/impg/jDfHY4qod0vPJIP18MoTA6Mu9RCaOwdvCDWqjg/-sJeeoy-EqY.jpg?size=511x85&quality=96&sign=c9f903d81a592bd3e8dd3df760840f75&type=album)

*(рис.35)*

### ***4.12.***	Дала владельцу каталога ~/play право на выполнение (рис.36);

![](https://sun9-52.userapi.com/impg/qxOChalKKcmPdrBsisimGTdhu30uv8NFABkEoQ/8MzgzLA22rQ.jpg?size=462x67&quality=96&sign=e07a3fa4052000f997331f6fa0b2e9f5&type=album)

*(рис.36)*

### **5.**	Прочитала man по командам mount, fsck, mkfs, kill и кратко их охарактеризовала, приведя примеры (рис.37-41);

![](https://sun9-69.userapi.com/impg/phNuBPdXlcW1gBCmELn7kGBMNqdGHFI2GiowVw/EB_wKpMSCmU.jpg?size=336x114&quality=96&sign=7353a0b82f96e9f8494c4c7906297fdc&type=album)

*(рис.37 использование man)*

![](https://sun9-64.userapi.com/impg/QWR-0VL-IH-GGz8zatOa1Ja3wC40Hx_TbDlVSQ/2PmENwIfmNA.jpg?size=1168x667&quality=96&sign=208b171c18faa1c6a1d7a981d4c3adf9&type=album)

*(рис.38 команда mount)*

![](https://sun9-46.userapi.com/impg/p03-HSgEGbtMzvJ3VNWsyZQSnRRzlajXvt2Bug/vJZXzICZYHw.jpg?size=1156x667&quality=96&sign=e998ad8c8cdd45319e0ed1e5491fc21f&type=album)

*(рис.39 команда fsck)*

![](https://sun9-5.userapi.com/impg/h7YiFMQyrvmqWuXuGCqp6aFWsHtEKim9m43_gg/rPt5nt_Eql0.jpg?size=1185x651&quality=96&sign=b748f6e51ea84c12c59b0d7090d18a7f&type=album)

*(рис.40 команда mkfs)*

![](https://sun9-60.userapi.com/impg/4aBIqRLgwJBy4UGw_pWLr24vivDcW8Tc6-dUBg/dDXMuMh3--U.jpg?size=1167x643&quality=96&sign=450c3da33646068534a0a32105f65052&type=album)

*(рис.41 команда kill)*

### ***Краткая характеристика:***
#### •	mount применяется для монтирования файловых систем;
#### •	fsck восстанавливает повреждённую файловую систему или проверяет на целостность;
#### •	mkfs создаёт новую файловую систему;
#### •	kill используется для принудительного завершения работы приложений.

---

## **Вывод:**
### Ознакомилась с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобрела практические навыки по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.

---

## **Ответы на контрольные вопросы:**
#### **1.**	Характеристика файловой системы, которая использовалась в данной лабораторной работе:
#### *Файлы:* abc1, april, may, june, july, isdv4.h, equipment, equiplist, equiplist2, my_os, feathers, file.old. 
#### *Каталоги:* monthly, monthly.00, tmp, monthly.01, reports, usr, include, xorg, ski.plases, equipment, newdir, plans, australia, play, etc, fun, games.

#### **2.**	Пример общей структуры файловой системы: /home/pdarzhankina/monthly/april, где /home/pdarzhankina – домашний каталог, /monthly – каталог, находящийся в домашнем и содержащий файл, /аpril – файл, находящийся в каталоге.

#### **3.**	Чтобы содержимое некоторой файловой системы было доступно операционной системе должно быть выполнено монтирование тома.

#### **4.**	Основные причины нарушения целостности файловой системы:
- Один блок адресуется несколькими mode (принадлежит нескольким файлам).
- Блок помечен как свободный, но в то же время занят (на него ссылается onode).
- Блок помечен как занятый, но в то же время свободен (ни один inode на него не ссылается).
- Неправильное число ссылок в inode (недостаток или избыток ссылающихся записей в каталогах).
- Несовпадение между размером файла и суммарным размером адресуемых inode блоков.
- Недопустимые адресуемые блоки (например, расположенные за пределами файловой системы).
- "Потерянные" файлы (правильные inode, на которые не ссылаются записи каталогов).
- Недопустимые или неразмещенные номера inode в записях каталогов.
Чтобы устранить повреждения файловой системы используется команда fsck.

#### **5.** Команда mkfs создаёт новую файловую систему.

#### **6.** Характеристика команд, которые позволяют просмотреть текстовые файлы:
- для просмотра небольших файлов удобно пользоваться командой cat.
- для просмотра больших файлов используйте команду less — она позволяет осуществлять постраничный просмотр файлов.
- для просмотра начала файла можно воспользоваться командой head, по умолчанию она выводит первые 10 строк файла.
- команда tail выводит несколько (по умолчанию 10) последних строк файла.

#### **7.**	Основные возможности команды cp:
- копирование файла в текущем каталоге.
- копирование нескольких файлов в каталог.
- копирование файлов в произвольном каталоге.
#### Опция i в команде cp выведет на экран запрос подтверждения о перезаписи файла, если на место целевого файла вы поставите имя уже существующего файла.
#### Команда cp с опцией r (recursive) позволяет копировать каталоги вместе с входящими в них файлами и каталогами.

#### **8.**	Характеристика команд перемещения и переименования файлов и каталогов:
- переименование файлов в текущем каталоге.
#### mv <старое_название_файла> <новое_название_файла>
- перемещение файлов в другой каталог.
#### mv <название_файла> <название_каталога>
#### Если необходим запрос подтверждения о перезаписи файла, то нужно использовать опцию i.
- переименование каталогов в текущем каталоге.
#### mv <старое_название_каталога> <новое_название_каталога>
- перемещение каталога в другой каталог.
#### mv <старый_каталога> <новый_каталог>
- переименование каталога, не являющегося текущим.
#### mv <каталог/старое_название_каталога> < каталог/новое_название_каталога>

#### **9.**	Каждый файл или каталог имеет права доступа: чтение (разрешены просмотр и копирование файла, разрешён просмотр списка входящих в каталог файлов), запись (разрешены изменение и переименование файла, разрешены создание и удаление файлов каталога), выполнение (разрешено выполнение файла, разрешён доступ в каталог и есть возможность сделать его текущим). Они могу быть изменены командой chmod.

