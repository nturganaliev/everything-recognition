# everything-recognition

Распознавание образов

### config.py
`config.py` содержит настройку со цветами, которые используются скриптом `run.py` для окрашивания в разные цвета распознанные части тела.

### run.py
`run.py` импортирует библиотеку `cv2` для распознования части тела и настройку со цветами с файла `config.py`. 
При запуске открывает встроенную или подключенную веб камеру и начинает распозновать части тела человека напротив камеры.
Каждый распознанный часть тела выделяется в квадрат и квадраты в свою очередь окрашиваются в разные цвета.
Например: Глаза в зеленый цвет, голова в синий цвет и.т.д.

![image](https://dvmn.org/media/lessons/xfiles4.png)


### Как установить?

Python3 должен быть уже установлен.</br>
Затем используйте `pip` (или `pip3`, м.б. конфликт с Python2)
для установки зависимостей наберите команду в терминале:
```bash
pip install -r requirements.txt
```

### Использование

Из терминала (командной строки) набираете следующую команду:

```bash

python3 run.py

```


### Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).
