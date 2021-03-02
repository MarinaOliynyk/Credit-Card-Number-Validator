# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

02.03.2021-02.03.2021 было проведено тестирование приложения Credit Card Number Validator:
* функциональное тестирование
* тестирование форм ввода с использованием позитивного и негативного тестирования и техники анализа граничных значений

На тестирование затрачено: 4 часа

В результате тестирования выявлены следующие дефекты:
* [issue#1](https://github.com/MarinaOliynyk/Credit-Card-Number-Validator/issues/1)
* [issue#2](https://github.com/MarinaOliynyk/Credit-Card-Number-Validator/issues/2)
* [issue#3](https://github.com/MarinaOliynyk/Credit-Card-Number-Validator/issues/3)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)


В качестве тестовых данных использовались данные из [текущего кода приложения](https://github.com/netology-code/javaqa-homeworks/tree/master/intro) и сгенерированные номера валидных карт [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* Result for MasterCard 5351719427810741 - OK
* Result for Visa 4024007162092351276 - OK
* Result for Maestro 6759159152423160 - OK
* Result for Visa Electron 4508264526738787 - OK
* Result for American Express (AMEX) 349073451801770 -OK
* Result for Diners Club - International 36310139309513 - OK
* Result for InstaPayment 6373107990767625 - OK
* Result for 0000000000000000 - FAIL
* Result for 427230009052540  - FAIL
* Result for 4508264526738781 - FAIL
* Result for 5351719427810749 - FAIL
* Result for _351719427810749 - FAIL

Тестирование производилось в следующем окружении:
* Windows 10 Home 32 bit
* JDK build 11.0.10+9
* IntelliJ IDEA 2020.3.2 Community Edition