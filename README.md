# Практическая работа №1
# Автор: [Sergey Salakhov](https://github.com/NetBeholder)
# Мини-шпаргалка по Git
## Создание локального репозитория
```bash
# Создание директории для проекта
mkdir -p ~/Projects/second-project
cd ~/Projects/second-project
# инициализация репозитория
git init
git branch -m main
```
## Добавление файлов в репозиторий
touch 1.txt 2.txt 3.txt
```bash
git add .
git commit -m 'initial commit'
git status
```
## Синхронизация с сервером
[См. документацию](https://docs.github.com/en/get-started/getting-started-with-git/managing-remote-repositories)

# Практическая работа №2
## Статус файлов

```
git status
```

```mermaid
untracked -- "git add" --> staged;
  staged    -- "git commit"     --> tracked/comitted;
    tracked/comitted -- "any change files" --> tracked/modified


%% стрелка без текста для примера: 
  A --> B;
```
