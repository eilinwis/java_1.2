# Отчёт о тестировании IntelliJ IDEA Community Edition, Credit Card Number Validator

## Краткое описание

04.03.2021 - 04.03.2021 было проведено функциональное тестирование Credit Card Number Validator, тестирование установки приложения IntelliJ IDEA Community Edition.

На тестирование затрачено: 3

В результате тестирования выявлены следующие дефекты:

* [Валидные номера кредитных карт не проходят проверку](https://github.com/eilinwis/java_1.2/issues/1#issue-822146269)




## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* [Инструкция по установке IntelliJ IDEA Community Edition](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

* [Код приложения Credit Card Number Validator](https://github.com/netology-code/javaqa-homeworks/tree/master/intro) 

*Примечание\*: код расположен в блоке "Задание №2"


В качестве тестовых данных использовались данные [Сайта-генератора номеров кредитных карт](https://www.freeformatter.com/credit-card-number-generator-validator.html) 

 
Fake credit card numbers for all major brands

VISA:

* 4485512812717064 OK

* 4449984771849763 OK

* 4916081933289137652 OK

Discover:

* 6011474119146109 OK

* 6011532539525697 OK

* 6011516541198899784 OK 

MasterCard:

* 5585265413791014 OK

* 5522814051696922 OK

* 2720990891834696 OK

American Express (AMEX):

* 378566390562589 OK

* 348073172237610 OK

* 340943822258448 OK

Maestro:

* 0604373079176229 OK

* 6761469421628358 OK

* 6759331468722334 OK


Тестирование производилось в следующем окружении:

* ПК Windows 10 64 bit

* Java 11.0.10" 2021-01-19 LTS

* IntelliJ IDEA Community edition 20.3.2