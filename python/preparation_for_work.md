Подготовка Python к работе
================================================================================
Устанавка пакетного менеджера pip
    
    $ sudo apt install python3-pip

Обновляем до последней версии

    $ sudo pip3 install --upgrade pip

Установка пакетов для удобной работы с виртуальными окружениями

    $ sudo pip3 install virtualenv virtualenvwrapper

Настраиваем virturalenvwrapper
--------------------------------------------------------------------------------
Находим место нахождения скрипта virtualenvwrapper.sh

    $ find / -name virtualenvwrapper.sh 2>/dev/null

или 

    $ locate virtualenvwrapper.sh

Добавляем в файл .bashrc:
 
    # Каталог с файлами виртуального окружения
    export WORKON_HOME=$HOME/.virtualenvs

    # Указание версии интерпретатора Python
    export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3

    # Место нахождения скрипта для работы с виртуальными окружениями
    source /usr/local/bin/virtualenvwrapper.sh

