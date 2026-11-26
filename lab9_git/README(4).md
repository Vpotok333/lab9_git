1-2 ![alt text](image(na_4)/image.png)
3-4 ![alt text](image(na_4)/image1.png)
5-7 ![alt text](image(na_4)/image-1.png)
8-10 ![alt text](image(na_4)/image-2.png) - разные результаты
11 git add - это не "сохранить". Это "положить в конверт". Конверт еще не запечатан, файл можно править дальше, и он будет жить в двух версиях сразу: в индексе - то, что вы добавили, в Changes - то, что дописали после. git diff в этот момент показывает разницу между этими двумя версиями.
12 ![alt text](image(na_4)/image-3.png)
13-14 ![alt text](image(na_4)/image-4.png)
15 ![alt text](image(na_4)/image-5.png)
16 ![alt text](image(na_4)/image-6.png)
17-18 ![alt text](image(na_4)/image-7.png)
19-20 ![alt text](image(na_4)/image-8.png)
21-22 ![alt text](image(na_4)/image-9.png) - строчка printf исчезла

Ветки и ff-merge
1-2 ![alt text](image(na_4)/image-10.png)
3-5 ![alt text](image(na_4)/image-11.png) - ветка идентична mybranch
6-8 ![alt text](image(na_4)/image-13.png) - верхний регистр
9 ![alt text](image(na_4)/image-14.png) - дерево коммитов
10-14 ![alt text](image(na_4)/image-16.png) - git diff показывает, в файле greeting.txt были изменения
15-16 ![alt text](image(na_4)/image-17.png) - удалили ветку и соединили главную и mybranch.
17 ![alt text](image(na_4)/image-18.png) коммит сделанный в новой(удаленной уже) ветке перешел на ветку mybranch
