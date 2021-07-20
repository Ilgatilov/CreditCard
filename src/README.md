# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

19.07.2021 - 20.07.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 5 часов

В результате тестирования выявлены следующие дефекты:
* [Карта не валидна при вводе номера меньше 16-значного](https://github.com/Ilgatilov/CreditCard/issues/1#issue-947957521)
* [Карта не валидна при вводе номера больше 16-значного](https://github.com/Ilgatilov/CreditCard/issues/2#issue-948821876)

## Описание процесса тестирования

В качестве тестовых данных использовались данные [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* Diners Club - карт-бланш № карты 30596895062744 - Result is OK;
* American Express (AMEX) № карты 374274826903592 - Result is OK;
* ВИЗА № карты 4916357950406830552 - Result is OK.

Тестирование производилось в следующем окружении:
* Windows 10
* Java 11.0.5