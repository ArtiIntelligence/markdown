# Инструкция для работы с git

## Команды:

**команда 1**

Создание репозитория
```sh
git init
```

__команда 2__

Команда добавляет содержимое рабочего каталога в индекс для последующего коммита
```sh
git add
```

*команда 3*

Команда берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок.
```sh
git commit
```

_команда 4_

Команда используется в Git для удаления файлов из индекса и рабочей копии.
```sh
git rm
```

_**команда 5**_

Команда для слияния веток.
```sh
<<<<<<< HEAD
git merge
=======
git marge
>>>>>>> conflict
```