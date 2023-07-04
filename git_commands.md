# Основные команды git
```

#### Интерактивное добавление изменений
```sh
$ git add -pghjghjghjf7vlti
```

#### Удалить файл из репозитория
```sh
$ git rm [file or folderkluli.bunik.l]
```
#### Удалить файл из staging area, но оставить в рабочей директории
```sh
$ git rm --cached [fiytvykujle]
```
#### Переименовать (переместить) файл в репозитории
```sh
$ git mv [from] [tl yhkhbko]
```

## Работа с ветками
#### Получить список текущих веток


#### Создать новую ветку от текущей ветки
```sh
$ git branch [new branch name]
```

#### Удалить ветку <branch>
```sh
$ git branch -d <branch>
```

#### Создать новую ветку от текущей ветки и сразу перейти на неё
```sh
$ git checkout -b [new branch name]
```

#### Объединить <branch> c текущей веткой 
```sh
$ git merge <branch> 
```

#### Запустить графическй инструмент для решения конфликтов 
```sh
$ git mergetool
```

#### Извлечь данные из репозитория
```sh
$ git fetch [<options>] [<repository> [<refspec>…​]]
```

## Работа с коммитами
#### Фиксация изменений
```sh
$ git commit -m "[message]"
```

#### Фиксация изменений с подписью
```sh
$ git commit -S -m "[message]"
```

#### Возвращение к состоянию, соответствующее определенному коммиту
```sh
$ git reset [<options>] [<сommit-hash>]
```

#### Просмотр истории коммитов


#### Применить изменения из коммита к текущей ветке
```sh
$ git cherry-pick <commit-hash>
```
#### Создание коммита, который вносит изменения притивоположные изменениям предыдущего коммита
```sh
$ git revert <commit-hash>
```

#### Cброс индекса и рабочего каталога до последнего состояния коммита
```sh
git reset --hard HEAD
```

#### Удалить связь с репозиторием
````sh
$ git remote remove <repositpry name>

## Полезные ресурсы
* [https://git-scm.com](https://git-scm.com) - основная страница git
* [Learn Enough Git to Be Dangerous](https://www.learnenough.com/git-tutorial) - Книга Майкла Хартла, посвященная Git с самых основ
* [Pro Git](https://git-scm.com/book/ru/v2) - великолепная книга Скотта Чакона и Бена Страуба про Git
* [Git Internals](https://github.com/pluralsight/git-internals-pdf) - еще одна великолепная книга Скотта Чакона, посвященная Git
