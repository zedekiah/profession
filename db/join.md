# JOIN

N, M - размеры таблиц в количестве строк

## Сложность
**Nested Loops Join** 
O(N^M) - квадратичная асимптотика

**Hash Join**
Если можно запихнуть хотя бы одну таблицу в память (обычно правую, но многие базы умеют определять какую лучше).
O(N+M) - линейная 

**Merge Join**
Если данные отсортированы, то O(M+N)
Если нет, то O(M log M + N log N)



## Сложность индексов
log(N)

## Ссылки
https://habr.com/ru/post/278087/
