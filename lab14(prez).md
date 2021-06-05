---
marp: true
---
# **РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ**

### **Факультет физико-математических и естественных наук**
### **Кафедра прикладной информатики и теории вероятностей**

---

# **ПРЕЗЕНТАЦИЯ** 
# **ЛАБОРАТОРНОЙ РАБОТЫ № 	14**
### дисциплина:	Операционные системы

### Студент: Казакова Виктория Алексеевна 
### Группа: НФИбд-01-20

###  **Москва**
### 2021

---
## ***Цель работы:*** 
## ***Приобрести простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования C калькулятора с простейшими функциями.***

---

![](https://sun9-64.userapi.com/impg/y47o4xfb7W7BwL-XBLZi4NUXG0Dgux9fLjoCJg/SK106aOzgfA.jpg?size=586x196&quality=96&sign=3d15f15caf0cf53d81fbcda60e74b563&type=album)

![](https://sun9-76.userapi.com/impg/PNYgIKhZ4amCu3m0Tgdn7cwrDgTS5HG_jjpF5A/06notJN9f0M.jpg?size=631x121&quality=96&sign=f8b42eaed44d66757e118efa806e1510&type=album)

---

### ***Реализация функций калькулятора в файле calculate.h:***

![](https://sun9-13.userapi.com/impg/-V9DonS5kmdGVsFJBsJDGwOlhVtyrPUcSEhgrQ/ax6uISH9Pc4.jpg?size=652x207&quality=96&sign=82764e2957bd45e58bb3ef77d3ab8224&type=album)

---

### ***Интерфейсный файл calculate.h, описывающий формат вызова функции калькулятора:***

![](https://sun9-55.userapi.com/impg/ueXwind3fFL7IUqDoGypA_Wo0GwBsa1AA4xu4Q/IDHwAXhuyjQ.jpg?size=918x498&quality=96&sign=26fde8f581a2e7f8a1569dbd2447f403&type=album)

---

![](https://sun9-12.userapi.com/impg/MSUyAlzhzqnyNYC56KfpbsF2HgJRDrVS2OJwFg/lu44EzIoEC0.jpg?size=849x447&quality=96&sign=15b3439224d916935c219ac84a1076ac&type=album)

---

### ***Основной файл main.c, реализующий интерфейс пользователя к калькулятору:***

![](https://sun9-55.userapi.com/impg/6LaTJ4qTeCPiZhs3_uapqUpcLqPsZuVfZ12Ejg/kt5F0mpDs-A.jpg?size=835x364&quality=96&sign=3941de09530c94eb48ee9219b4e78e95&type=album)

---
### ***Выполнила компиляцию программы посредством gcc***

![](https://sun9-72.userapi.com/impg/jmszvhMuE2_y3iweeuTocSyzCWwS-f2AyrHrWg/55uV1EM3xJA.jpg?size=697x66&quality=96&sign=e90d8c10f10eb75ce99c2a50569386ec&type=album)

---

### ***Создала Makefile со следующим содержанием:***

![](https://sun9-51.userapi.com/impg/Chn50BGE-dMfEdagiaPx-rROxhv8Gbbk3dQQ5w/eOwxj93UxW8.jpg?size=670x286&quality=96&sign=b8f4dd2c570a71804b8be5d139cfba28&type=album)

---

### ***С помощью утилиты splint попробовала проанализировать коды файлов calculate.c и main.c***

![](https://sun9-40.userapi.com/impg/n01OkmegAlmU5kDF1Gtfxh2S8uGsi04tZHGZdg/2eMNnzkfnPk.jpg?size=847x562&quality=96&sign=c90b72eb49dfac29732050d3647e9e9c&type=album)