# Отчёт о тестировании Precision

## Краткое описание

09.08.2021 - 09.08.2021 было проведено функциональное тестирование приложения Precision.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [При проверке суммы бонуса длинное значение после запятой](https://github.com/kokanoka/Precision/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Код для оптимизации бонусной системы

В качестве тестовых данных использовались данные:
* double regularBonus = 0.3, double specialBonus = 0.6, totalBonus = 09.


Тестирование производилось в следующем окружении:
* Windows 10, 64 bit
* 11.0.12