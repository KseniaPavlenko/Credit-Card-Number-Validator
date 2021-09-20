# Отчёт о тестировании "Credit Card Number Validator"

## Краткое описание

19.09.2021 г. - 19.09.2021 г. было проведено модульное функциональное тестирование (позитивные сценарии) приложения "Credit Card Number Validator".

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:

* https://github.com/KseniaPavlenko/Credit-Card-Number-Validator/issues/1
* https://github.com/KseniaPavlenko/Credit-Card-Number-Validator/issues/2
* https://github.com/KseniaPavlenko/Credit-Card-Number-Validator/issues/3

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* Тест кейсы для Credit Card Number Validator https://docs.google.com/spreadsheets/d/1qyX8oaZ-5h_G6KjjlVFI_jVbZoffv_F9ky6hJ_ABJ3M/edit?usp=sharing

В качестве тестовых данных использовались данные сайта https://www.freeformatter.com/credit-card-number-generator-validator.html:

* VISA 16-значные номера кредитных карт, ожидаемый результат: Result is OK
* VISA 19-значные номера кредитных карт, ожидаемый результат: Result is OK
* Discover 16-значные номера кредитных карт, ожидаемый результат: Result is OK
* Discover 19-значные номера кредитных карт, ожидаемый результат: Result is OK
* Diners Club - Carte Blanche 14-значные номера кредитных карт, ожидаемый результат: Result is OK
* Visa Electron 16-значные номера кредитных карт, ожидаемый результат: Result is OK
* MasterCard 16-значные номера кредитных карт, ожидаемый результат: Result is OK
* JCB 16-значные номера кредитных карт, ожидаемый результат: Result is OK
* JCB 19-значные номера кредитных карт, ожидаемый результат: Result is OK
* Diners Club - International 14-значные номера кредитных карт, ожидаемый результат: Result is OK
* InstaPayment 16-значные номера кредитных карт, ожидаемый результат: Result is OK
* American Express (AMEX) 15-значные номера кредитных карт, ожидаемый результат: Result is OK
* Diners Club - North America 16-значные номера кредитных карт, ожидаемый результат: Result is OK
* Maestro 16-значные номера кредитных карт, ожидаемый результат: Result is OK

Тестирование производилось в следующем окружении:

* ОС Windows 10 (Версия 20H2 (сборка ОС 19042.1165); 64-разрядная ОС, процессор x64)
* Версия Java JDK11U-jdk_x64_windows_hotspot_11.0.11.9
* IntelliJ IDEA Community Edition 2021.2.1
