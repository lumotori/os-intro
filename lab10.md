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
### Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

---

## **Ход работы**

### **1.** Ознакомилась с теоретическим материалом; 

### **2.**	Ознакомилась с редактором emacs;

### **3.**	Выполнила следующие упражнения:

---

### **1.**	Открыла emacs (предварительно узнала информацию о версиях – рис.1 установила – sudo apt install emacs) (рис.2);

![](https://sun9-22.userapi.com/impg/L0HgiZZ8X1WxvWCxzy7RXf2UYXJV9dYyoJSfuQ/HLQgVMzUuOU.jpg?size=732x280&quality=96&sign=f5ce7c2b0eff2c7ba2ccddc2dff88252&type=album)

*(рис.1 информация о версиях emacs)*

![](https://sun9-55.userapi.com/impg/R2WcC2LGQdBTypb0zK8VfXURhWTHKTGNNI9wDg/F4pPmy5sM3k.jpg?size=387x57&quality=96&sign=a869f8840e270b3724f67e245c72bfb6&type=album)

*(рис.2 открыла emacs)*

### **2.**	Создала файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f (C-x C-f) (рис.3);

![](https://sun9-17.userapi.com/impg/D_nog9l-qH5DTv_IumsZGFoJ8_8MA1kl2dCvEg/-Ybf_X0asFc.jpg?size=712x133&quality=96&sign=a9e6935e09dac632d1fd7839d6a3f0fd&type=album)

*(рис.3)*

### **3.**	Набрала текст (рис.4): 
### #!/bin/bash 
### HELL=Hello 
### function hello { 
### LOCAL HELLO=World 
### echo $HELLO 
###  } 
### echo $HELLO 
### hello 

![](https://sun9-39.userapi.com/impg/5CqIoscuAL-czEy2cTeOQjhjiHDrTHqLpQkvLg/hb1iNOt7VzI.jpg?size=621x204&quality=96&sign=b32fe65052a36e0d0a0eb256bd38c6ed&type=album)

*(рис.4 текст из задания)*

### **4.**	Сохранила файл с помощью комбинации Ctrl-x Ctrl-s (C-x C-s) (рис.5);

![](https://sun9-7.userapi.com/impg/sEAPi0PHMnNAU0NWyLbfNzW-2vykXzKnQ4TkpA/YoQ9EHPb_0U.jpg?size=690x268&quality=96&sign=275f5bf1a1995c79211deeae29959110&type=album)

*(рис.5 сохранение файла)*

### **5.**	Проделала с текстом стандартные процедуры редактирования:

---

### ***5.1.***	Вырезала одной командой целую строку (С-k) (рис.6);

![](https://sun1-21.userapi.com/impg/AFv7dENsAG-Voo45gqAgSIT0BuL9Cw9fVY7N5A/klkv_8_Sb2I.jpg?size=660x337&quality=96&sign=7129218c008117ce7c3b5249b335de60&type=album)

*(рис.6)*

### ***5.2.***	Вставила эту строку в конец файла (C-y)В (рис.7);

![](https://sun9-59.userapi.com/impg/7UGp7RArap6cf937058CzaaKBsjUYv9hllMTuA/M2_9dOIV8ZU.jpg?size=652x343&quality=96&sign=c0b6a98bc7e25a21743b888082783a8b&type=album)

*(рис.7)*

### ***5.3.***	Выделила область текста (C-space) (рис.8);

![](https://sun9-33.userapi.com/impg/mE0RVNVNgigcnTKyJ-sy10Jp9Fi2UdgPCnljcw/k1ARduds-ZE.jpg?size=666x331&quality=96&sign=d4cd5de5a25b56bb2497665641e4c3e0&type=album)

*(рис.8)*

### ***5.4.***	Скопировала область в буфер обмена (M-w) (т.к. у меня нет клавиши Meta, я использовала клавишу Alt) (рис.9);

![](https://sun9-9.userapi.com/impg/6rdyxdQQhx8mQghgOKopM91oVAaAyIzqx43cew/5vnaJuNQxf0.jpg?size=655x205&quality=96&sign=dbc75fd366f87c3632e4f3de32cdf4e2&type=album)

*(рис.9)*

### ***5.5.***	Вставила область в конец файла (С-у) (рис.10);

![](https://sun9-68.userapi.com/impg/DKU71CH83JUbHiX20MvTHFWwWUz7084Zcf9oTA/i_yuwINQzv8.jpg?size=658x246&quality=96&sign=529a682aa307550c22e0ec8dc479fa13&type=album)

*(рис.10)*

### ***5.6.***	Вновь выделила эту область и на этот раз вырезала её (C-w) (рис.11);

![](https://sun9-4.userapi.com/impg/e_YBofN9ROnP8LAMESrkZOvfO6UOR6l-Xhg3BA/YfFkIVvj4SE.jpg?size=658x211&quality=96&sign=fbc854825cc7ccee6e6962650449c122&type=album)

*(рис.11)*

### ***5.7.***	Отменила последнее действие (C-/) (рис.12);

![](https://sun9-5.userapi.com/impg/cn2keyybOyrV6MjgKjiKlFsyJBIeNt0CB-ICvA/5yqnE2TVlp4.jpg?size=652x211&quality=96&sign=65b5295d7ec35de90ec61cb95f62cf3b&type=album)

*(рис.12)*

---

### **6.** Научилась использовать команды по перемещению курсора

---

### ***6.1.***	Переместила курсор в начало строки (C-a);
### ***6.2.***	Переместила курсор в конец строки (C-e) (рис.13);

![](https://sun9-14.userapi.com/impg/KpM0mh3CVZL8Rt3neSVUKTs_nr-B8Nu-a4i5wg/VOQQLJNrEB4.jpg?size=637x115&quality=96&sign=cad4d34bfddddf3d2731ee1197b97434&type=album)

*(рис.13)*

### ***6.3.***	Переместила курсор в начало буфера (M-<) (рис.14);

![](https://sun9-76.userapi.com/impg/-854u5NdAfE2wVEqWKrbcJomDbK6Mjscx-ITKg/aXiDNSvUREI.jpg?size=657x340&quality=96&sign=6d68fb6a9022b82c73432d4f48c156ef&type=album)

*(рис.14)*

### ***6.4.***	Переместила курсор в конец буфера (M->) (рис.15);

![](https://sun9-50.userapi.com/impg/ZYgMLx_UnnPT5z6HBKg8iPGFkN2Q12IlEyZ1-A/Dy1AJC8N7VU.jpg?size=660x357&quality=96&sign=64481bf0705f44e6d31eb4abe4c97a88&type=album)

*(рис.15)*

---

### **7.**	Управление буферами: 

### ***7.1.***	Вывела список активных буферов на экран (C-x C-b) (рис.16);

![](https://sun9-5.userapi.com/impg/BaOGYJx9eMI6fASMKF2UzhiwF0d-l14mOHN4DA/3sv9lKo2CCs.jpg?size=655x313&quality=96&sign=f7debe50779c41bc83dfb9e9c857fa8a&type=album)

*(рис.16)*

### ***7.2.***	Переместила во вновь открытое окно (C-x) o со списком открытых буферов и переключилась на другой буфер (рис.17);

![](https://sun9-35.userapi.com/impg/kwZX9L6WlcTnw1WWCavoPLnMV9hJHD_GkbqG0g/-v7yWO5_Tbw.jpg?size=676x340&quality=96&sign=7a6f2bfa39385f0fdad7c3f9de981a1c&type=album)

*(рис.17)*

### ***7.3.***	Закрыла это окно (C-x 0) (рис.18);

![](https://sun9-62.userapi.com/impg/QMobH3l105ir-FR3tsiaqZTBVF0TySuZsTuVvw/VvljKkuO5Mg.jpg?size=661x250&quality=96&sign=2149ba0015ce857e9aa213c50b8e2fed&type=album)

*(рис.18)*

### ***7.4.***	Теперь вновь переключилась между буферами, но уже без вывода их списка на экран (C-x b) (рис.19);

![](https://sun9-42.userapi.com/impg/6LBBGIUbuSzWeA2_vSzoJM-P3IZaPtzGCcJhBQ/f8JZ0gqa5yM.jpg?size=658x253&quality=96&sign=8ceef26b88f50e58000f76630316eec2&type=album)

*(рис.19)*

---

### **8.**	Управление окнами. 

### ***8.1.***	Поделила фрейм на 4 части: разделила фрейм на два окна по вертикали (C-x 3) (рис.20), а затем каждое из этих окон на две части по горизонтали (C-x 2) (рис.21);

![](https://sun9-26.userapi.com/impg/yGUyHqvfPEs47w97CmTNbCSabX1TuzD40S5iLw/MRRM3L_M4qs.jpg?size=672x289&quality=96&sign=30738a0e28291e5f2a76e944f09b443c&type=album)

*(рис.20)*

![](https://sun9-40.userapi.com/impg/C4a6rOp3yPib8VSEAKhpUOJTgk-jQYNg5bJuOw/RPugIdi0pFM.jpg?size=670x577&quality=96&sign=7660fb998d19742f6fc64694e3fd0e5d&type=album)

*(рис.21)*

### ***8.2.***	В каждом из четырёх созданных окон открыла новый буфер (файл) (назвала его lab.sh) и ввела несколько строк текста (рис.22);

![](https://sun9-58.userapi.com/impg/gbi0xNAynYmF2jvZ2agiCEv-grYxhgJlkzTR1g/59dgPdgQ450.jpg?size=847x435&quality=96&sign=08a4f912bf6ea6457d241ba2e39997b8&type=album)

*(рис.22)*

---

### **9.**	Режим поиска:

### ***9.1.***	Переключилась в режим поиска (C-s) и нашла несколько слов, присутствующих в тексте (рис.23);

![](https://sun9-2.userapi.com/impg/o6WXr3GK2l_Tg7803-jtwqkw4XWxrRI-ZZx0sQ/SaMxiKwiQ9E.jpg?size=850x535&quality=96&sign=1d5df035bffb302f54c8a3f4b239f57e&type=album)

*(рис.23)*

### ***9.2.***	Переключалась между результатами поиска, нажимая C-s (рис.24);

![](https://sun9-73.userapi.com/impg/SRGLB0EkQibNk7kJL37K2UZSLyNlU3lRqi5mHw/rwKoLpk2BGo.jpg?size=862x532&quality=96&sign=e221ec1f7b404d4f8237a4a3e4e3aad2&type=album)

*(рис.24)*

### ***9.3.***	Вышла из режима поиска, нажав C-g (рис.25);

![](https://sun9-70.userapi.com/impg/SV5-49A2iqgM8MKqYaJyYhdZYb4UEIyd5kO0sA/Q9AKOhgIu00.jpg?size=856x522&quality=96&sign=f56829473ae9af47eec4a400c64d05c6&type=album)

*(рис.25)*

### ***9.4.***	Перейдите в режим поиска и замены (M-%), введите текст, который следует найти и заменить, нажмите Enter , затем введите текст для замены. После того как будут подсвечены результаты поиска, нажмите «!» для подтверждения замены. 

### ***9.5.***	Испробуйте другой режим поиска, нажав M-s o. 

### *(пункты 9.4 и 9.5 на моем устройстве с моей версией emacs не работают)*

---

## **Вывод:**
### Познакомилась с операционной системой Linux, получила практические навыки работы с редактором Emacs.

---

## **Ответы на контрольные вопросы:**
#### **1.** Emacs представляет собой мощный экранный редактор текста, написанный на языке высокого уровня Elisp.

#### **2.** Развитие Emacs в сторону его многогранности послужило причиной того, что и без того интуитивно непонятная программа стала чрезвычайно сложной в применении. В частности, управление осуществляется при помощи различных клавиатурных комбинаций, запомнить которые будет непросто.

#### **3.** Буфер – что-то, состоящее из текста.
#### Окно – область с одним из буферов.

#### **4.** В одном окне можно открыть больше 10 буферов.

#### **5.** После запуска emacs без каких-либо параметров в основном окне отображается буфер *scratch*, который используется для оценки выражений Emacs Lisp, а также для заметок, которые вы не хотите сохранять. Этот буфер не сохраняется автоматически.

#### **6.** Чтобы ввести следующую комбинацию C-c | я нажму клавиши: Control+c и Shift+\, и для C-c C-|: Control+c и Control+Shift+\.

#### **7.** Поделить текущее окно на две части можно двумя комбинациями клавиш: C-x 3 или C-x 2.

#### **8.** Настроить или расширить Emacs можно написав или изменив файл ~/.emacs.

#### **9.** Клавиша ß выполняет функцию перемещения курсора в открытом окне также, как и многие другие клавиши её можно переназначить.

#### **10.** Редактор emacs показался мне удобнее из-за возможности открытия нескольких окон с буферами и работать комбинациями клавиш в этот редакторе мне было проще

---

### ***Библиография:***
- Лабораторная работа 10 https://esystem.rudn.ru/pluginfile.php/1142229/mod_resource/content/3/007-lab_emacs.pdf 