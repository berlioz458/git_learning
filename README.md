# Lesson 11. QA-GURU

Первая половина задания:
1. создать branch
2. сделать три изменения тремя коммитами, 
3. сделать скрин git log, 
4. после чего обьединить три коммита в один общий (rebase -i ).
5. Сделать пулл реквест на бранче.


Список команд в помощь:
1. Узнать версию гита

```bash
git --version
```

1. Узнать конфигурационные данные

```bash
git config --global user.email
```

1. Инициализируем репозитории в папке

```bash
git init
```

1. Проверка статуса репозитория

```bash
git status
```

1. Добавить файл для отслеживания гитом

```bash
git add filename
```

1. Добавить всё что есть в папке в гит для отслеживания версий

```bash
git add .
```

1. Удаляем файлы из отслеживания гитов

```bash
git rm --cached filename
git rm --cached -r directory
```

1. Создать бранч

```bash
git branch add_tests
```

1. Список бранчей

```bash
git branch -a
```

1. Соедить локальный и удаленный репозиторий, пример

```bash
git remote add origin git@github.com:berlioz458/qa_guru_10_11.git
```

1. Удалить соединение

```bash
git remote remove origin
```

1. Добавить коммит

```bash
git commit -m "init commit"
```

1. Запушить изменения на удаленный репозиторий

```bash
git push -u origin master // для первого раза
git push origin master
```

1. Переключиться на другой бранч

```bash
git checkout nameBranch
```

1. Обновление репозитория локального

```bash
git pull
```
