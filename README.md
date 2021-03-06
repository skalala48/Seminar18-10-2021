# Инструкция по работе с Git

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий. Git позволяет управлять нашими изменениями, создавать фиксации, ветки, а так же сливать их.

## Подготовка репозитория
Репозиторий - это хранилище файлов, поддерживающее версионность. Создать репозиторий можно с помощью применеия в папке команды *git init*.

## Создание сохранений
Сохранения в репозитории происходят через команду *git commit commit_name*

## Перемещение между сохранениями
Чтобы переместиться от одного сохранения к другому следует взять хэш нужного коммита и вставить его в команду *git checkout _____*

## Журнал изменений
Для вызова журнала изменений можно воспользоваться одной из команд:
*git log*;
*git log --graph*;

## Ветки в Git
Для создания веток в Git нужна команда *git branch branch_name*
Чтобы перемещаться между ветками используем команду *git checkout branch_name*

## Слияние веток и решение конфликтов
Для слияния веток используется команда *git merge branch_name*
При возникновении конфликта слияния веток Visual Studio Code предложит варианты решения конфликта.

## Удаление веток
Чтобы удалить ветки нужно ввести команду *git branch -d branch_name*.