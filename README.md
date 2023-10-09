#Подключение к GitHub с нового компьютера (Linux)

####0. Генерация колюча SSH ключа 

    ssh-keygen -t ed25519 -C "petrosrv@gmail.comm"

####1. Добавление сгенерированного SSH-ключа в ssh-агент 

    ssh-add ~/.ssh/id_ed25519 

####2. Добавить публичный SSH ключ в github.com 

    https://github.com/settings/keys

####3. Добавить новый репозиторий в github.com 
    https://github.com/new

####2. Установка Git                                         
    sudo apt install git

####3. Инициализация git

    it config --global user.email "petrosrv@gmail.comm"
    git config --global user.name "Roman Petrosyants"
    

####4. Отправить проект в репозиторий GitHub - в рабочей директории выполнить:

    git init 
    git add.
    git commit -m "first commit"
    git branch -M main 
    git remote add origin git@github.com:petros-rv/RRR.git
    git push -u origin main

####5. Enjoy)
