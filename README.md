# Домашнее задание "Git" Штанько Богдан

---

## 📌 Задание 1

### Что было сделано:
- Создан публичный репозиторий на GitHub
- Выполнено клонирование репозитория
- Настроены имя и email в Git
- Отредактирован файл README.md
- Выполнен коммит и отправка на GitHub

### Используемые команды:

git clone https://github.com/Fuyumiki/netology_hw_git.git

git config --global user.name "Fuyumiki"
git config --global user.email "dreft507@gmail.com"
"
git status
git diff
git add README.md
git commit -m "First commit"
git push origin main


### Ссылка на коммит:
https://github.com/Fuyumiki/netology_hw_git/commit/4ed91ef8891e6c199e428cd99f7380a4318d2fe8#diff-b335630551682c19a781afebcf4d07bf978fb1f8ac04c6bf87428ed5106870f5

---

## 📌 Задание 2

### Что было сделано:
- Создан файл `.gitignore`
- Добавлены правила игнорирования файлов

### Содержимое .gitignore:

*.pyc
cache/


### Команды:

git add .gitignore
git commit -m "Add gitignore"
git push


### Ссылка на коммит:
https://github.com/Fuyumiki/netology_hw_git/commit/ТВОЙ_ХЕШ

---

## 📌 Задание 3

### Что было сделано:
- Создана ветка `dev`
- Создан файл `test.sh`
- Сделано несколько коммитов в ветке dev
- В основной ветке создан файл `main.sh`
- Выполнен merge ветки dev в main

### Команды:

git checkout -b dev
touch test.sh
git add test.sh
git commit -m "add test.sh"
git commit -am "update test.sh"
git push origin dev

git checkout main
touch main.sh
git add main.sh
git commit -m "add main.sh"
git push

git merge dev
git push


### Ссылка на граф коммитов:
https://github.com/Fuyumiki/netology_hw_git/network

---

## 📎 Скриншоты

![Скриншот 1](ссылка_на_скрин)
![Скриншот 2](ссылка_на_скрин)