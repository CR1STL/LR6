# LR6
Лабораторная работа №6
### Настройка клиента Git
![](im/1.png)
### Был выполнен процесс клонирования личного удалённого репозитория на локальный компьютер
![](im/4.jpg)
### В интерфейсе GitHub был добавлен новый файл в репозиторий
![](im/5.jpg)
### Была получена история операций для каждой из веток в репозитории
![](im/6.jpg)
### Скриншот разрешения конфликта при помощи Github Desktop
![](im/7.png)
### Результат успешного решения конфликта
![](im/8.jpg)
### Удаление побочной ветки
![](im/9.jpg)
### Скриншот с историей операций
![](im/3.png)
## Лог команд:
```
git clone https://github.com/CR1STL/LR6
cd "C:\Users\vadim\OneDrive\Рабочий стол\LR6"git pull
git log
git log origin/branch1
git status
git merge branch1
git branch -D branch1
git push origin -d branch1
git add .
git commit -m "first change"
git add .
git commit -m "second change"
git reset --hard HEAD~
git branch report
git checkout report
git log --pretty="%h %ad %ch %s"
```
