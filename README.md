<!----- Conversion time: 1.115 seconds.


Using this Markdown file:

1. Cut and paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β17
* Wed Sep 18 2019 01:01:48 GMT-0700 (PDT)
* Source doc: https://docs.google.com/open?id=1sIorEva0JHPGjUlZBihoiGIootksj8HqQUjW8Vota0c
----->




## 3. Работа с удаленными репозиториями и GitHub


### Цель работы

Освоить основные навыки работы с облачными и распределенными системами контроля версий, получить навыки работы с инструментальными средствами, обеспечивающими командную работу над разработкой ПО.


### Задания для выполнения



1. Зарегистрироваться на сайте github.com
2. Установить на компьютере программу Git
3. Форкнуть данный репозиторий в свой аккаунт
4. Склонировать созданный удаленный репозиторий в директорию ~/git/test
![image](https://user-images.githubusercontent.com/70998859/138615122-750b11f6-8fc1-4713-9f9f-0e195f02b9f4.png)
6. На локальной машине пишем скрипт ~/git/test/backup.sh, с произвольным содержанием
![image](https://user-images.githubusercontent.com/70998859/138615703-a618371c-ae76-480c-ada5-b2634d527165.png)
8. Фиксируем скрипт в репозитории (делаем коммит)
![image](https://user-images.githubusercontent.com/70998859/138615711-89fb8aa1-6077-4397-8dee-3b182b2bd057.png)
10. Обновляем удаленный репозиторий репозиторий (делаем пуш)
![image](https://user-images.githubusercontent.com/70998859/138615843-3b04ccc3-f4c4-4a3e-bd06-4ef3594f4cd3.png)
12. Через текстовый редактор добавить любую новую строку с комментарием
![image](https://user-images.githubusercontent.com/70998859/138615878-da6aafb8-881a-4b1b-9380-733ac07ef61a.png)
14. Сделать коммит
![image](https://user-images.githubusercontent.com/70998859/138615910-9f675343-8de7-4c86-89f2-77308b8200ab.png)
16. Вности синтаксическую ошибку в скрипт
![image](https://user-images.githubusercontent.com/70998859/138615974-4e4c7f5e-9aae-40eb-90a5-745892cee846.png)
18. Сделать коммит ошибочного скрипта
![image](https://user-images.githubusercontent.com/70998859/138616003-4342f55e-7d56-4b16-9d2c-0e9222583bc2.png)
20. Откатываем до последней рабочей версии
![image](https://user-images.githubusercontent.com/70998859/138616123-f241a26b-d1a8-44a4-bb32-55deac840fc3.png)
![image](https://user-images.githubusercontent.com/70998859/138616220-b6554f4a-829c-4f7a-a902-83899e01e4f1.png)
22. Просмотреть историю коммитов
![image](https://user-images.githubusercontent.com/70998859/138616743-8e8889a8-e871-43e8-9149-2023c20f000a.png)
24. Добавить несколько коммитов произвольного содержимого
![image](https://user-images.githubusercontent.com/70998859/138616822-161d513a-22be-480d-9f9e-2d467b4122f4.png)
26. Создать пулл реквест в данный репозиторий


### Контрольные вопросы



1. Зачем нужен облачный хостинг репозиториев?
Облачный хостинг репозиториев нужен, чтобы одновременно над одним репозиторием могли работать несколько человек.
2. Какими основными функциями обладает сайт github.com?
Github позволяет копировать, загружать делиться репозиториями, а также организовывать, помечать и связывать вопросы с определенными этапами разработки.
3. Как организовать командную работу над открытым проектом?
Участники проекта могут делать ветвления, чтобы работать над своей частью кода, а когда закончат, просто сделать pull request в основную версию.

### Дополнительные задания

Настройте работу с git вашей интегрированной среды разработки по выбору. Для работы с python рекомендуется использовать PyCharm. Выполните задания лабораторной работы в IDE используя встроенные средства работы с системами контроля версий.  
![image](https://user-images.githubusercontent.com/70998859/140273007-b678c647-970c-4f6b-ba28-1b81196411f3.png)  


<!-- Docs to Markdown version 1.0β17 -->
