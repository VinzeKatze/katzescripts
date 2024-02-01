# ktz-autokali

Библиотека [bashmator](https://github.com/vinzekatze/bashmator) для __kali linux__.

Потихоньку коплю тут всякие сомнительные скрипты.

## Установка

Добавить оболочки, если не добавлены:
```
bshm shell add /usr/bin/bash
bshm shell add /usr/bin/python3
```

Скачать и добавить библиотеку:

```
git clone https://github.com/vinzekatze/ktz-autokali
bshm library add ktz-autokali
bshm library use ktz-autokali
```

Установить все необходимое:

```
bshm use install --item 1-6
```
После установки рекомендуется перелогиниться