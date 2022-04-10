# Инструкция по работе с git и ветками

## Создание репозитория 
Для того чтобы добавить версионность к данной папке, и создать в ней локальный репозиторий, для этого необходимо открыть окно терминала в этой папке и написать команду *git init*. Тогда ваша папка станет репозиторием, и в ней появится скрытая папка .git


## Добавление файлов в репозиторий
Добавить версионность к файлу, ноходящемуся в папке-репозитории, можно с помощью команды *git add*. В терменале она пишется *git add <название файла>*.

## Создание коммитов
Для того чтобы зафиксировать изменения в текущей версии используется команда *git commit*. Используется она следующим образом: *пше commit -m "<Сообщение к коммиту>"*. Сообщение к коммиту писать ОБЯЗАТЕЛЬНО

## Просмотр истории коммитоа
Для просмотра истории всех сделанных коммитов, используется команда *git log*. Чтобы увидеть всю историю коммитов, в папке репозитория необходимо написать *git log*

## Переключение между коммитами
Для того чтобы переключаться между коммитами, необходимо использовать комманду *git checkot*. Используется она следующим образом: *git checkout <номер коммита>*. Номер коммета можно взять, просмотрев список всех коммитов.


## Создание ветки
Для того чтобы создать новую ветку, используется команда *git branch*

## Переключение между ветками
Для того чтобы переключитьтся между ветками, используется команда *checkout*

## Слияние между веток
Слеяние веток можно произвести с помощью команды *git merge*. Используется она следующим образом: В папке с репозиторием нужно написать *git merge <сливаемая ветка>*

## Удаление веток
Удаление слитой ветки можно прооизвести с помощью команды *git branch -d <название удаляемой ветки>*. Удаляемая ветка должна быть обязательно слита с какой-нибуть из существующих веток.