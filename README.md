# Репозиторий для pull request

**## Инструкция для чайников ##**
 1. ! Открыть Visual Studio Code 
 2. ! Открыть/Создать Новую папку для работы (название прописать на англ.)
 3.   Открыть терминал 
      Прописать команду git status
      Убедится в том что работа ведется в чистом репозитории

* В своём аккаунте на *GitHub* создать копию репозитория **maxim-stoma/gitHomeWork** с помощью кнопки "Fork".

На сайте GitHab создаем "вилку" копируем файл для своего аккаунта: *Смотри фото №1,№2"
(Фото FORK)[]

* Клонировать копию репозитория на локальный компьютер.

 4. Ввести в терминале команду 
 
 git clone ...
 
 (ввести ссылку на репозитарий/длинны строка появится автоматически *https://...* )

 5. Перейти в файл который скопировали с сайта 
 с помощью команды:
     
      cd ...(*имя новаго файла "форкнутого"*)

* **Создать новую ветку.**

6. Создать новую ветку с помощью команды 

     git branch ...(*любое название"имя ветки"*)

 7. переходим в новую "свою" ветку 

    git checkout ...(*имя новой ветки*)


8. Проверяем где находится

     git status
     
* Добавить файл с инструкцией в новую ветку.

  
 9. Добавляем файл из "форкнутого" 

     git add ...(*имя файла из сторенней папки/внимательно все буквы и расширение файла*)

     Смотри фото:

     (Фото файла)[Foto_faila.png]


  10. git status

  11. Вносим изменения и незабывает Коммитить-сохранятся и коментировать

 git commit -am *"Коментарий что изменили для понимания линия работы"*

    *После ввода этой команды выходит сообщение копия что мы сохранили и прокоментировали*      
  
* Дополнить инструкцию разделами по работе с удалёнными репозиториями, pull request.

Когда работа будет закончена, по вашему мнению, снова проверяем где находимся 
## git status


* Зафиксировать изменения (коммиты).

## Проверяем все сохранения и после проводим отправку нашей работы,нашу измененную версию файла,на сайт GitHab

* Отправить изменения на GitHub.

## git push 

12. Отправляем нашу версию на внешний репозитарий с  помощью команды:

  Вводим в терминале git push 

   После ввода команды git подскажет какую команду надо ввести
   Копируем эту подсказку и вводим в новой строке иии...
   Случается магия :)-- Наша версия загружается на сайт GitHub

* На сайте GitHub выполнить Pull request.
  
13. Переходим  на сайт GitHub , обнавляем страницу, если все сделано правильно напротив имени копии форкнутого файла почвится кнопка *Pull Request*

  смотри фото:

  (Фото кнопки Pull Request)[]

  После нажатия на её появится окно в котором можно обратится к хозяину файла и написать коментарий.

Поздравляю Вы справились !!!

*P.S. Вам на почту прейдет ответное письмо когда владелец файла его просмотрит и внесет какие либо лействия правки или замечания.*