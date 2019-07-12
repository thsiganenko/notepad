# Проверка орфографии

Для того, чтобы включить проверку орфографии достаточно в командном режиме
выполнить команду:

    :setlocal spell spelllang=ru,en

Если словари не были установлены, по будет выдано приглашение для их установки.

Для того, чтобы изменить стиль оформления индикации ошибок в тексте, можно в
конфигурационный файл добавить следующие строки:

    highlight clear SpellBad
    highlight SpellBad ctermfg=Red

    highlight clear SpellCap
    highlight SpellCap ctermfg=Blue

    highlight clear SpellLocal
    highlight SpellLocal ctermfg=Green 

В этом случае орфографические ошибки будут выделяться красным цветом,
отсутствие заглавное буквы - синим, использование "е" вместо "ё" - зеленым.
