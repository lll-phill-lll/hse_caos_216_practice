# АКОС (архитектура компьютеров и операционные системы)

# Страничка семинаров 216 группы

## Навигация по семинарам
1.  [[Видео](https://disk.yandex.ru/d/hVWLMgTBxXHBUQ/%D0%90%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0%20%D0%BA%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%B0%20%D0%B8%20%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D1%8B%D0%B5%20%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D1%8B/%D0%A1%D0%B5%D0%BC%D0%B8%D0%BD%D0%B0%D1%80/%D0%91%D0%9F%D0%9C%D0%98216%20%D0%A4%D0%B8%D0%BB%D0%B8%D1%82%D0%BE%D0%B2%202022-11-08T11-28-00Z.mp4)][[конспект](01sem-asm)][asm] - введение в ассемблер
2.  [[Видео](https://disk.yandex.ru/d/hVWLMgTBxXHBUQ/%D0%90%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0%20%D0%BA%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%B0%20%D0%B8%20%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D1%8B%D0%B5%20%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D1%8B/%D0%A1%D0%B5%D0%BC%D0%B8%D0%BD%D0%B0%D1%80/%D0%91%D0%9F%D0%9C%D0%98216%20%D0%A4%D0%B8%D0%BB%D0%B8%D1%82%D0%BE%D0%B2%202022-11-15T11-28-37Z.mp4)][[конспект](02sem-asm)][asm] - продолжение ассемблера - сдвиги, loop, simpleio

## Навигация по темам

Пока пусто

## Правила игры

### Форматирование ASM

1. В одном блоке кода (участок кода отделенный новой строкой сверху и снизу) между командами и аргументами должен быть отступ одного размера. Отступ должен быть сделан табом, а не пробелом. То есть все аргументы должны быть выравнены.

```
        pushl   %ebp
        movl    %esp, %ebp

        subl    $4, %esp
        and     $-16, %esp
        leal    -4(%ebp), %eax
```

### Форматирование С

[Link](style.html)

### Реджекты

Сданный код проходит тестирование в тестирующей системе, а затем проверяется глазами семинариста и ассистентов.

Прошедший тесты код может быть отправлен на исправление (получен статус reject), если решение является неоптимальным, если нарушает условия, установленные в задаче или если нарушает форматирование.

### Списывание

Проверка на списывание запускается в случайное время. При обнаружении списывания обнуляется ВЕСЬ контест и составляется записка в УО.

В проверке на списывание участвуют все доступные онлайн материалы, в том числе известные репозитории с решениями и решения прошлых годов.

Если вы берете код из общедоступного источника, то нужно прикладывать ссылку на этот источник и пояснять комментариями код, чтобы было видно, что вы этот код понимаете.

## Полезные ссылки

### Материалы

* [Материалы курса 2020 года](https://github.com/blackav/hse-caos-2020)
* [Материалы физтеха](https://github.com/victor-yacovlev/fpmi-caos)
* [Вики учебник по asm](https://ru.wikibooks.org/wiki/%D0%90%D1%81%D1%81%D0%B5%D0%BC%D0%B1%D0%BB%D0%B5%D1%80_%D0%B2_Linux_%D0%B4%D0%BB%D1%8F_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%81%D1%82%D0%BE%D0%B2_C)

### Тулзы

* [Godbolt - compiler explorer](https://gcc.godbolt.org/)

## Файлы

* [C11 стандарт](C11_standard.pdf)
* [Simpleio](simpleio_i686.S)

## Обратная связь

* [Анонимно похвалить или поругать](https://forms.gle/oPw34wmeiaq72T3C8)

## Контакты

 * [сем]    Филитов Миша     - [tg] @iiixphillxiii
 * [ассист] Осташов Денис    - [tg] @igreetyou
 * [фссист] Петренко Ксения  - [tg] @KseniaPetrenko
