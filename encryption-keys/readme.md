# Тестирование криптографической стойкости 

Данные для тестирования находятся в следующих директориях

- `data`- содержит в себе случайно сгенерированный набор данных для применения ключей шифрования
- `keys` - содержит ключи шифрования.



## Зашифрованные данные
Каждый день, в начале дня, в папке `data` будет размещен файл с зашифрованными данными, а в папке `keys` будет размещен публичный ключ.

Задача проверки криптографической стойкости сводится к необходимости провести расшифровку данных за время, равное времени проведения выборов - 12 часов. 



## Расшифрованные данные
Спустя 12 часов, в конце дня, в папке `data` будет размещен файл с исходными данными, а в папке `keys` будет размещен закрытый ключ. 
