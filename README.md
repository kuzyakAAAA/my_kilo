# kilo_cpp

Текстовый редактор для терминала на C++ с поиском (без учёта регистра, с подсчётом совпадений).

## Основа

Проект основан на редакторе **kilo** (Salvatore Sanfilippo, лицензия BSD-2-Clause):
- исходники: https://github.com/antirez/kilo (коммит `323d93b`, 2025-01-04)
- туториал: https://viewsourcecode.org/snaptoken/kilo/

Оригинальный код лежит в папке `kilo_original/` без изменений, вместе с его лицензией.

## Структура

```
kilo_original/   исходники kilo на C (для справки)
src/             своя версия на C++
```

## Сборка оригинала

```
cd kilo_original && make && ./kilo имя_файла
```
