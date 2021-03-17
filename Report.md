#           **Отчет Lab01**
##                *Report*

- Команда `export LAB_NUMBER=01`

```
Cоздаем переменную с номером лабораторной работы
```

```
Результат:
export LAB_NUMBER=01
```
- Команда `git clone https://github.com/tp-labs/lab${LAB_NUMBER} tasks/lab${LAB_NUMBER}`

```
Клонирование реперезитории
```

```
Результат:
Cloning into 'tasks/lab01'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 74 (delta 0), reused 0 (delta 0), pack-reused 71
Unpacking objects: 100% (74/74), 945.05 KiB | 1.65 MiB/s, done.
```
- Команда `mkdir reports/lab${LAB_NUMBER} `

```
Cоздание дериктории
```

```
Результат:
nikita@DESKTOP-VB3RC3D .../workspace $ mkdir reports/lab${LAB_NUMBER}
```
- Команда `cp tasks/lab${LAB_NUMBER}/README.md reports/lab${LAB_NUMBER}/REPORT.md`

```
Копирование Report.md
```
```
Результат:
cp tasks/lab${LAB_NUMBER}/README.md reports/lab${LAB_NUMBER}/REPORT.md
```
- Команда `cd reports/lab${LAB_NUMBER}`

```
Смена рабочего католога
```
```
Результа:
nikita@DESKTOP-VB3RC3D .../lab01 $ pwd
/mnt/c/Users/79207/Desktop/Nikita7181/workspace/reports/lab01
```

- Команда `edit REPORT.md`

```
Открытие файла Report.md
```

```
Результат:
## Laboratory work I
```

### *Homework*
1. Установка `boost`
![](https://raw.githubusercontent.com/Nikita7181/Lab01/main/screenshots/install.png)
   
2. Разархивирование файла с помощью `tar`
![](https://raw.githubusercontent.com/Nikita7181/Lab01/main/screenshots/tar.PNG)
   
3.Подсчет количества файлов в директории `~/boost_1_69_0` не включая вложенные директории.
![](https://raw.githubusercontent.com/Nikita7181/Lab01/main/screenshots/t.PNG)

4.Подсчет количества файлов в директории `~/boost_1_69_0` включая вложенные директории.
![](https://raw.githubusercontent.com/Nikita7181/Lab01/main/screenshots/kol2.PNG)

5.Подсчет количества заголовочных файлов, файлов с расширением .cpp, .h

`.сpp`
![](https://raw.githubusercontent.com/Nikita7181/Lab01/main/screenshots/1.PNG )

`.h`
![](https://raw.githubusercontent.com/Nikita7181/Lab01/main/screenshots/2.PNG)

6.Полный путь до `any.hpp`

![](https://raw.githubusercontent.com/Nikita7181/Lab01/main/screenshots/any.PNG)

7.Вывод в консоль все файлы, где упоминается последовательность `boost::asio`

![](https://raw.githubusercontent.com/Nikita7181/Lab01/main/screenshots/3.PNG)

>Все не влезло

8.Компиляция `boost`

![](https://raw.githubusercontent.com/Nikita7181/Lab01/main/screenshots/komp.PNG)

9.Перенос файлов в `~/boost-libs`
![](https://raw.githubusercontent.com/Nikita7181/Lab01/main/screenshots/7.PNG)
![](https://raw.githubusercontent.com/Nikita7181/Lab01/main/screenshots/8.PNG)
10.Подсчет сколько занимает дискового пространства каждый файл в этой директории.
 ![](https://raw.githubusercontent.com/Nikita7181/Lab01/main/screenshots/10.PNG)
11.Топ 10 `Самых тяжелых`
 ![](https://raw.githubusercontent.com/Nikita7181/Lab01/main/screenshots/9.PNG) 
