# False is False in [False]
    Почему результат True?

    >>> False is False in [False]
    True

Потому что данное выражение раскрывается в:
    
    False is False and False in [False]

Таким образом исходное выражение является многоместной операцией сравнения
a < b < c.
