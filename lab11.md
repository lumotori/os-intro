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
### Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать небольшие командные файлы.

---

## **Ход работы**

---

### **1.**	Написала скрипт (файл с расширением sh), который при запуске будет делать резервную копию самого себя (то есть файла, в котором содержится его исходный код) в другую директорию backup в вашем домашнем каталоге (рис.2-3). При этом файл должен архивироваться одним из архиваторов на выбор zip, bzip2 или tar. Способ использования команд архивации я узнала, изучив справку через команду man (рис.1);

![](https://sun9-1.userapi.com/impg/BIMUi7GF_-uIHI7_n61OUUdAT_i4asz954xZTQ/SGGcB07riBI.jpg?size=1005x553&quality=96&sign=956590df5d16dddc6a8da8274a03cd20&type=album)

*(рис.1 справка команды tar)*

![](https://sun1-25.userapi.com/impg/MuMHtKa0oedp5ww2P7g1HvvagCq3-pim7uwe_A/FqPZC_21r4c.jpg?size=487x99&quality=96&sign=df3fd07704c0d7f1ecc47a68733aa399&type=album)

*(рис.2 создание скрипта, присвоение прав)*

![](https://sun9-21.userapi.com/impg/iLOvPZG6uaxfTi8JmuZ0AurySvjd5-H6xG5knw/OmfJfZFD9aI.jpg?size=669x160&quality=96&sign=d3a29950d2a18c96475e5c60de3029d6&type=album)

*(рис.3 код скрипта)*

---

### **2.**	Написала пример командного файла, обрабатывающего любое произвольное число аргументов командной строки, в том числе превышающее десять. Например, скрипт может последовательно распечатывать значения всех переданных аргументов (рис.4-5);

![](https://sun9-47.userapi.com/impg/G9eo2k7dlRRnjtzU2cMovKBgzxGOY7qnKMVrng/jkIWmS4paxQ.jpg?size=646x261&quality=96&sign=acb63d0ca2e32b8225aa1d574f16958c&type=album)

*(рис.4 код программу)*

![](https://sun9-67.userapi.com/impg/psNpWkV0xXtWDURpb1WWv_DDuPro8I7T8AWQwg/ycubZvQLoyY.jpg?size=412x85&quality=96&sign=48066779bd445c258e1c12dbedd5f424&type=album)

*(рис.5 работа кода)*

---

### **3.**	Написала командный файл — аналог команды ls (без использования самой этой команды и команды dir). Требуется, чтобы он выдавал информацию о нужном каталоге и выводил информацию о возможностях доступа к файлам этого каталога (рис.6-7);

![](https://sun9-60.userapi.com/impg/DkeyNSV8amYxF5CcoXcceHfZihsZFLTq_ym2Vw/oseR2nRLnos.jpg?size=652x223&quality=96&sign=a93807a1ee327e6f1248d8e140667f3b&type=album)

*(рис.6 код)*

![](https://sun9-30.userapi.com/impg/cZn2zGks2QIUPidIR0uD1ASeX5IgmmsJO5i6jQ/LUrCV8Fcom4.jpg?size=376x555&quality=96&sign=ca4ec029a05d6d4fe5d6d7a5a2ed93c8&type=album)

*(рис.7 результат работы)*

---

### **4.**	Написала командный файл, который получает в качестве аргумента командной строки формат файла (.txt, .doc, .jpg, .pdf и т.д.) и вычисляет количество таких файлов в указанной директории. Путь к директории также передаётся в виде аргумента командной строки (рис.8-9);

![](https://sun9-66.userapi.com/impg/cNT1vu6yuV3S9V1w33mBbvXRRy8RwMZFD9teUA/FGVzIF53rUA.jpg?size=675x295&quality=96&sign=256c48907212c314027369b722d4cc0c&type=album)

*(рис.8 командный файл)*

![](https://sun9-63.userapi.com/impg/K7ep59gUSQ-hGrjmmsp8JJwcwku_pEsaBsCXkQ/_aNSpuak06w.jpg?size=994x231&quality=96&sign=b6fa22d28c93cfe4b7f4c9fecca77f4f&type=album)

*(рис.9 работа кода)*

---

## **Вывод:**
### Изучила основы программирования в оболочке ОС UNIX/Linux. Научилась писать небольшие командные файлы.

---

## **Ответы на контрольные вопросы:**

#### **1.**	 Командный процессор (командная оболочка, интерпретатор команд shell) — это программа, позволяющая пользователю взаимодействовать с операционной системой компьютера. В операционных системах типа UNIX/Linux наиболее часто используются следующие реализации командных оболочек:
- оболочка Борна (Bourne shell или sh) — стандартная командная оболочка UNIX/Linux, содержащая базовый, но при этом полный набор функций;
- С-оболочка (или csh) — надстройка над оболочкой Борна, использующая Сподобный синтаксис команд с возможностью сохранения истории выполнения команд;
- оболочка Корна (или ksh) — напоминает оболочку С, но операторы управления программой совместимы с операторами оболочки Борна;
- BASH — сокращение от Bourne Again Shell (опять оболочка Борна), в основе своей совмещает свойства оболочек С и Корна (разработка компании Free Software Foundation). 
#
#### **2.**	POSIX (Portable Operating System Interface for Computer Environments) — набор стандартов описания интерфейсов взаимодействия операционной системы и прикладных программ.
#### Cтандарты POSIX разработаны комитетом IEEE (Institute of Electrical and Electronics Engineers) для обеспечения совместимости различных UNIX/Linuxподобных операционных систем и переносимости прикладных программ на уровне исходного кода. POSIX-совместимые оболочки разработаны на базе оболочки Корна.
#
#### **3.** Командный процессор bash обеспечивает возможность использования переменных типа строка символов. Имена переменных могут быть выбраны пользователем.
#### Пользователь имеет возможность присвоить переменной значение некоторой строки символов. Например, команда mark=/usr/andy/bin присваивает значение строки символов /usr/andy/bin переменной mark типа строка символов.
#### Значение, присвоенное некоторой переменной, может быть впоследствии использовано. Для этого в соответствующем месте командной строки должно быть употреблено имя этой переменной, которому предшествует метасимвол $. Например, команда mv afile ${mark} переместит файл afile из текущего каталога в каталог с абсолютным полным именем /usr/andy/bin.
#### Использование значения, присвоенного некоторой переменной, называется подстановкой. Для того чтобы имя переменной не сливалось с символами, которые могут следовать за ним в командной строке, при подстановке в общем случае используется следующая форма записи: ${имя переменной}
#### Например, использование команд b=/tmp/andyls -l myfile > ${b}lssudo apt-get install texlive-luatex приведёт к переназначению стандартного вывода команды ls с терминала на файл /tmp/andy-ls, а использование команды ls -l>$bls приведёт к подстановке в командную строку значения переменной bls. Если переменной bls не было предварительно присвоено никакого значения, то её значением будет символ пробела.
#### Оболочка bash позволяет работать с массивами. Для создания массива используется команда set с флагом -A. За флагом следует имя переменной, а затем список значений, разделённых пробелами. Например, set -A states Delaware Michigan "New Jersey"
#### Далее можно сделать добавление в массив, например, states[49]=Alaska. Индексация массивов начинается с нулевого элемента.
#
#### **4,5,6.** Команда let также расширяет другие выражения let, если они заключены       в двойные круглые скобки. Таким способом вы можете создавать довольно сложные выражения.
#### Команда let не ограничена простыми арифметическими выражениями.
#### Команда read позволяет читать значения переменных со стандартного ввода:
*echo "Please enter Month and Day of Birth ?"*

*read mon day trash*
#### В переменные mon и day будут считаны соответствующие значения, введённые с клавиатуры, а переменная trash нужна для того, чтобы отобрать всю избыточно введённую информацию и игнорировать её.
#
#### **7.**
- HOME — имя домашнего каталога пользователя. Если команда cd вводится без аргументов, то происходит переход в каталог, указанный в этой переменной.
- IFS — последовательность символов, являющихся разделителями в командной строке, например, пробел, табуляция и перевод строки (new line).
- MAIL — командный процессор каждый раз перед выводом на экран промптера проверяет содержимое файла, имя которого указано в этой переменной, и если содержимое этого файла изменилось с момента последнего ввода из него, то перед тем, как вывести на терминал промптер, командный процессор выводит на терминал сообщение You have mail (у Вас есть почта).
- TERM — тип используемого терминала.
- LOGNAME — содержит регистрационное имя пользователя, которое устанавливается автоматически при входе в систему
#
#### **8, 9.** Такие символы, как ' < > * ? | \ " &, являются метасимволами и имеют для командного процессора специальный смысл. Снятие специального смысла с метасимвола называется экранированием метасимвола. Экранирование может быть осуществлено с помощью предшествующего метасимволу символа \, который, в свою очередь, является метасимволом. Для экранирования группы метасимволов нужно заключить её в одинарные кавычки. Строка, заключённая в двойные кавычки, экранирует все метасимволы, кроме $, ' , \, ".
#
#### **10.** Последовательность команд может быть помещена в текстовый файл. Такой файл называется командным. Далее этот файл можно выполнить по команде: bash командный_файл [аргументы]
#### Чтобы не вводить каждый раз последовательности символов bash, необходимо изменить код защиты этого командного файла, обеспечив доступ к этому файлу по выполнению. Это может быть сделано с помощью команды chmod +x имя_файла
#### Теперь можно вызывать свой командный файл на выполнение, просто вводя его имя с терминала так, как будто он является выполняемой программой. Командный процессор распознает, что в Вашем файле на самом деле хранится не выполняемая программа, а программа, написанная на языке программирования оболочки, и осуществит её интерпретацию.
#
#### **11.** Группу команд можно объединить в функцию. Для этого существует ключевое слово function, после которого следует имя функции и список команд, заключенных в фигурные скобки. Удалить функцию можно с помощью команды unset c флагом-f. Команда typeset имеет четыре опции для работы с функциями: 
- -f — перечисляет определенные на текущий момент функции; 
- -ft— при последующем вызове функции инициирует ее трассировку; 
- -fx— экспортирует все перечисленные функции в любые дочерние программы оболочек; 
- -fu— обозначает указанные функции как автоматически загружаемые. Автоматически загружаемые функции хранятся в командных файлах, а при их вызове оболочка просматривает переменную FPATH, отыскивая файл с одноименными именами функций, загружает его и вызывает эти функции.
#
#### **12.** ls -lrt Если есть d, то является файл каталогом
#
#### **13.** Для создания массива используется команда set с флагом -A. За флагом следует имя переменной, а затем список значений, разделённых пробелами. Удалить функцию можно с помощью команды unset c флагом -f.
#### Команда typeset имеет четыре опции для работы с функциями:
- -f — перечисляет определённые на текущий момент функции;
- -ft — при последующем вызове функции инициирует её трассировку;
- -fx — экспортирует все перечисленные функции в любые дочерние программы
оболочек;
- -fu — обозначает указанные функции как автоматически загружаемые. #### Автоматически загружаемые функции хранятся в командных файлах, а при их вызове оболочка просматривает переменную FPATH, отыскивая файл с одноимёнными именами функций, загружает его и вызывает эти функции. 
#
#### **14.** Символ $ является метасимволом командного процессора. Он используется, в частности, для ссылки на параметры, точнее, для получения их значений в командном файле. В командный файл можно передать до девяти параметров. При использовании где-либо в команд- ном файле комбинации символов $i, где 0 < 𝑖 < 10, вместо нее будет осуществлена подстановка значения параметра с порядковым номером i, т.е. аргумента командного файла с порядковым номером i. Использование комбинации символов $0 приводит к подстановке вместо нее имени данного командного файла. Рассмотрим это на примере. Пусть к командному файлу where имеется доступ по выполнению и этот командный файл содержит следующий конвейер: who | grep $1 Если Вы введете с терминала команду: where andy, то в случае, если пользователь, зарегистрированный в ОС UNIX под именем andy, в данный момент работает в ОС UNIX, на терминал будет выведена строка, содержащая номер терминала, используемого указанным пользователем. Если же в данный момент этот пользователь не работает в ОС UNIX, то на терминал не будет выведено ничего. Команда grep производит контекстный поиск в тексте, поступающем со стандартного ввода, для нахождения в этом тексте строк, содержащих последовательности символов, переданные ей в качестве аргументов, и выводит результаты своей работы на стандартный вывод. В этом примере команда grep используется как фильтр, обеспечивающий ввод со стандартного ввода и вывод всех строк, содержащих последовательность символов andy, на стандартный вывод. В ходе интерпретации этого файла командным процессором вместо комбинации символов $1 осуществляется подстановка значения первого и единственного параметра andy. Если предположить, что пользователь, зарегистрированный в ОС UNIX под именем andy, в данный момент работает в ОС UNIX, то на терминале Вы увидите примерно следующее: $ where andy andy ttyG Jan 14 09:12 $ Определим функцию, которая изменяет каталог и печатает список файлов: $ function clist { > cd $1 > ls > }. Теперь при вызове команды clist каталог будет изменен каталог и выведено его содержимое.
#
#### **15.** 
- $* — отображается вся командная строка или параметры оболочки;
- $? — код завершения последней выполненной команды;
- $$ — уникальный идентификатор процесса, в рамках которого выполняется командный процессор;
- $! — номер процесса, в рамках которого выполняется последняя вызванная на выполнение в командном режиме команда;
- $- — значение флагов командного процессора;
- ${#*} — возвращает целое число — количество слов, которые были результатом $*;
- ${#name} — возвращает целое значение длины строки в переменной name;
- ${name[n]} — обращение к n-му элементу массива;
- ${name[*]} — перечисляет все элементы массива, разделённые пробелом;
- ${name[@]} — то же самое, но позволяет учитывать символы пробелы в самих переменных;
- ${name:-value} — если значение переменной name не определено, то оно будет
заменено на указанное value;
- ${name:value} — проверяется факт существования переменной;
- ${name=value} — если name не определено, то ему присваивается значение value;
- ${name?value} — останавливает выполнение, если имя переменной не определено, и выводит value как сообщение об ошибке;
- ${name+value} — это выражение работает противоположно ${name-value}. Если переменная определена, то подставляется value;
- ${name#pattern} — представляет значение переменной name с удалённым самым коротким левым образцом (pattern);
- ${#name[*]} и ${#name[@]} — эти выражения возвращают количество элементов в массиве name.

### ***Библиография:***

- Лабораторная работа 11 https://esystem.rudn.ru/pluginfile.php/1142232/mod_resource/content/2/008-lab_shell_prog_1.pdf