# CDP Parser

CDP Parser - это утилита для парсинга выводов CDP (Cisco Discovery Protocol) и визуализации топологии сети.

## Установка

Тестировалось на Python 3.11. Установка зависимостей:

1. Установите зависимости (при необходимости создайте виртуальное окружение):
   ```shell
   pip install -r requirements.txt
   ```
2. Установите [среду](https://graphviz.org/download/) для рендеринга изображений graphviz

## Запуск
Выполните следующую команду, чтобы запустить программу:
```shell
python main.py -s путь_к_каталогу
```

По умолчанию программа ищет файлы в каталоге `./cdp`, но вы можете указать другой каталог с помощью опции `-s` или `--source-directory`.