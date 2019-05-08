# Python versions

# Overview
Общая информация о ключевых изменениях в новых версиях Python.
Каждая следующая версия включает все предыдущие.
Для поддержания совместимости стоит использовать библиотеку [six](/python/libraries/six) ([cheatsheet](/python/libraries/six/cheatsheet)). 

Полный перечень измений можно посмотреть [тут](https://docs.python.org/release/3.7.3/whatsnew/index.html)

# 3.0
* `print` - теперь функция
* [Views And Iterators Instead Of Lists](https://docs.python.org/release/3.7.3/whatsnew/3.0.html#views-and-iterators-instead-of-lists)
* Операторы сравнения стали более строгими, теперь нельзя `1 < ''`, `0 > None`, `len <= len`, `None < None` ([подробнее](https://docs.python.org/release/3.7.3/whatsnew/3.0.html#ordering-comparisons))
* Убрали `long`, теперь все `int` [PEP237](https://www.python.org/dev/peps/pep-0237) (`repr` больше не добавляет `L`)
* Появился оператор `//` который возвращает `int`, а `/` теперь возвращает `float` [PEP238] (https://www.python.org/dev/peps/pep-0238)
* Больше нет `sys.maxint` (но не стоит забывать про `sys.maxsize`)
* Числа в восьмеричной системе счисления теперь надо писать как `0o720` (раньше было `0720`)
* Unicode строки

# 3.4

# 3.5
# 3.6
# 3.7
