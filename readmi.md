Hellow world.

#GIT
1)	Створи директорію (наприклад папку module), яку ти залиєш згодом на GIT, і в якій будеш працювати., і створи там перший файл(наприклад readme.txt)
2)	Створи репозиторій на GIT, куди будеш заливати директорію з компа
3)	Відкрий термінал, виведи директорію яку створив, або відкрий термінал з папки(директорії ) яку створив
4)	В терміналі проініціалізуй репозиторій, в терміналі введи команду git init  (в директорії на компі створиться невидима папка .git)
5)	В терміналі введи команду ls – виведе всі видимі файли що є і цій директорії
6)	Введи команду ls -a   - виведе всі видимі і невидимі файли що є в цій директорії (один з файлів(директорій) обов’язково має бути .git)
7)	help - виводить на екран перелік основних консольних команд та їх призначення.
8)	pwd - (скорочення від анг. print working directory "вивести робочу директорію".)
9)	cd - За допомогою цієї команди можна змінити поточну робочу директорію
(після самої команди потрібно вказати шлях до бажаного джерела переходу.
Наприклад, перейдемо в каталог з назвою test.  cd / home / maria / test    )
Часто використовувані аргументи:

     ..    - для повернення в попередню директорію;
     
     - - для повернення в попередню директорію;
     
     . - для переходу в піддеректорію в поточній робочій папці;
     
     ~   - для переходу в домашню директорію.

8)	-l   -  опція для виведення додаткової інформації про файли (наприклад, права доступу, власник, дата створення і т.д.
9)	touch foo.txt  - команда яка створить файл foo.txt  в директорії  в якій зараз знаходишся.
10)	mkdir bar  - команда яка створить директорію bar (папку bar), в директорії в якій зараз знаходишся. (mkdir – Make Directory)
11)	cp foo2.txt bar.txt  – команда яка скопіює файл foo2.txt (з поточної директорію) і збереже його під назвою bar.txt (в поточній директорії)
12)	cp ../foo.txt ./foocopy.txt  -  команда яка скопіює файл foo.txt (з вищої директорії ) і збереже його під назвою foocopy.txt (в поточній директорії) 
13)	mv foo.txt ../foopast.txt  -  команда яка виріже файл foo.txt з поточної директорії і вставить його під  назвою foopast.txt  в директорію вище
14)	mv ./bar/foo2.txt ./foopast.txt  - команда яка виріже файл foo2.txt з директорії  bar  і вставить його під назвою foopast.txt  в директорію поточну
15)	cat first-file.rtf  - команда яка відкриє(відобразить)  вміст файлу first-file.rtf  (в нашому випадку текст “Слава Україні”) якщо він знаходиться в поточній директорії.
16)	cat ./module-git/first-file.rtf   - команда яка відкриє(відобразить)  вміст файлу first-file.rtf  (в нашому  випадку текст “Слава Україні”) якщо ми знаходимось в директорії вище.
17)	
18)	Зайди в директорійю  .git ,  для цього в терміналі , знаходячись в директорії яку створив(module ),  введи команду cd .git
19)	Перевір статус репозиторію, ввівши команду  git status
20)	Вказуємо за яким файлом має слідкувати git ввівши команду git add readme.txt   (або ввівши команду git add .  – ми вказали щоб git слідкував за всіма файлами які знаходяться в директорії в якій ми зараз працюємо)
21)	 Перевіряємо тепер чи git відслідковує те що нам потрібно: вводимо команду git status врезультаті якщо висвітлився потрібний нам файл зеленим кольором, це означає що за ним git слідкує і все ок, все за чим git не слідкує, висвітлиться червоним кольором.
22)	Тепер піля кожного редагування робимо комбінацію для комітів, для цього робимо команди
git add readme.txt 
git coomit -m “next commit”  
12)	 Для перевірки комітів використовуй команду git log
13)	 Додаємо конфігурації до нашого GIT git config --global user.email “you@gmail.com”  та  git config –global user.name “your name”  - щоб встановити ідентифікатор за замовчуванням для ваших облікових записів  omit --global  - щоб встановити ідентифікатор лише в цьому сховищі
14)	 git restore --staged readmi.txt  - команда яка вказує git, щоб він перестав відслідковувати зміни в файлі readmi.txt  

Основи роботи в командній стрічці:

cd
ls
mv
rm
cp
cat
Налаштування Git

git config --list
git config user.name
git config user.email
Загальні положення

що таке hash коміту
що таке HEAD
Віддалені репозиторії

Github
Gitlab
Bitbucket
Отримання даних з віддаленого репозиторія

git clone
git remote -v
git pull
git fetch
Відправка даних у віддалений репозиторій

генерація токену для доступу до репозиторію
git push
помилки під час отримання та відправлення даних на сервер
Робота з гілками. Створення гілок

git checkout -b <branch-name>
Вирішення конфліктів в Git

git merge
мітки "<<<<<<<, ======= та >>>>>>>"
git rebase
Cтворення пулл-реквесту

Додаткові ресурси:
https://git-scm.com/book/uk/v2
https://git-school.github.io/visualizing-git
ДЗ
 


