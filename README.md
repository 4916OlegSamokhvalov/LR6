# Отчет о лабораторной работе №6
## Самохвалов Олег гр.4916

### Ход работы:

Была сделана копия репозитория https://github.com/Kurtyanik/LR6/

![Rep](screenshots/1.png)

При помощи команды cd Desktop\lab6 выполняется переход в созданную папку на компьютере. Затем при помощи команды git init инициализируется git в данной папке. После записывается команда git remote add origin для связывания папки с удаленным репзоиторием на GitHub и git clone для клонирования репозитория в данную папку. 

![git init](screenshots/2.png)

Выполняется вход git с помощью команд git config --global user.name, git config --global user.email

![git conf](screenshots/0.png)

Через сайт GitHub создается текстовый файл text.txt. Выполняется переход в папку, клонированного репозитория cd LR6, затем при помощи команды git pull origin master загружаются изменения из удаленного в локальный репозитории.

![txt](screenshots/3.png)

Выполняется команда git log, которая показывает список действий в репозитории

![git log](screenshots/4.png)

При помощи команды git show показывается последние изменение в репозитории.

![git show](screenshots/5.png)

Затем выполняется переход на ветку branch git checkout -t origin/branch1. После возвращаемся в master при помощи git checkout master.

![git checkout](screenshots/6.png)

Выполняется попытка слияния веток branch1 и master командой git merge branch1, однако выдается ошибка.

![merge error](screenshots/7.png)

Исправляется ошибка в mergefile.txt путем удаления выделенных строк.

![merge fixed](screenshots/8.png)

После редактирования добавляется mergefile.txt используя команду git add, затем выполняется git merge branch1, после слияния удаляется ветка branch1. В конце выполняется git push origin master на удаленный репозиторий.

![git merge](screenshots/9.png)

![git merge](screenshots/10.png)

Создаются 3 файла в удаленном репозитории.

![file](screenshots/11.png)

Новые файлы добавляются в локальный репозиторий git pull origin master, просматривается лог действий.

![new file](screenshots/12.png)

Выполняется откат последнего коммита git reset --hard HEAD~1. Пушим изменения на удаленный репозиторий.

![git hard reset](screenshots/13.png) 

Данный текстовый файл удален на удаленном репозитории

![reset file](screenshots/14.png)

Создается новая ветка report, используя команду git checkout -b report. Выводится графический лог git log --graph

![git graph](screenshots/18.png)

После этого скриншоты добавляются в новую ветку git add screenshots. Отправляем коммит с сообщением git commit -m "adding screenshots to report". 

![git add](screenshots/15.png)

Пушатся файлы скриншотов в обновленны репозиторий.

![screen](screenshots/16.png)

Повторно просматриваются логи в графическом виде.

![git graph2](screenshots/17.png)

Составляется отчет в файле README.md. Данный файл добавляется в новую ветку и пушится в репозиторий.

![git read1](screenshots/20.png)

![git read2](screenshots/21.png)

Финальный результат.

![git final log](screenshots/19.png)

Все скриншоты данной работы лежат в папке screenshots.
