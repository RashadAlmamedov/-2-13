# git-config

git-config --global user.name "Рашад Алмамедов"
git-config --global user.email "rashaman777@gmail.com"

git config --list # посмотреть настройки

git-config --global core.autocrlf true
git-config --global core.quotepath off
git-config --global core.safecrlf warn
git-config --global init.defaultBranch main

git init # инициализация репозитория
git add . # добавить все файлы в tarack
git commit -m # описание, сделать коммит
git status # показывает текущий статус
git diff # показывает текущие изменения
git diff --color words # более развернуто изменения
git checkout # вернуться к последнему коммиту
