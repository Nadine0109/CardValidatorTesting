# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

07.02.2021/22.30 - 07.02.2021/23.04 было проведено тестирование системы валидации номеров кредитных карт с помощью программы ItelliJ IDEA Community Edition

На тестирование затрачено: 34 минуты

В результате тестирования выявлены следующие дефекты:
* https://github.com/Nadine0109/CardValidatorTesting/issues/1
* https://github.com/Nadine0109/CardValidatorTesting/issues/2


## Описание процесса тестирования

Тестирование включало в себя проверку валидации карт девяти распространённых международных платёжный систем: VISA, MasterCard, American Express (AMEX), Discover, JCB, Diners Club - International, Maestro, Visa Electron, InstaPayment. В имеющийся для исполнения валидации код вносились данные карт и была произведена проверка распознования вводимых данных в качестве валидных. 
По результатам тестирования были выявлены дефекты в распознавании карт систем American Express (AMEX) и Diners Club -International.


Программный код для программы валидации был взят в данном источнике: 
https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-2---credit-card-number-validator

В качестве тестовых данных использовались случайно сгенерированные данные с сайта https://www.freeformatter.com/credit-card-number-generator-validator.html:

* VISA:
  
4716320480427961,
4308798537411381

* MasterCard:

5492115159688415,
5299902267429336

* American Express (AMEX):

344026356328310,
376599778791548

* Discover:

6011966245664855,
6011315269818320


* JCB:

3529171810695481,
3540208648971935

* Diners Club - International:

36122563103340,
36142997073109

* Maestro:

6759575046144359,
6763318124261553

* Visa Electron:

4026092355551242,
4844630941369908

* InstaPayment:

6385991710884505,
6370815437396021


Тестирование производилось в следующем окружении:
* Desktop, Windows 10 сборка 19041.630, 64-bit
* openjdk version "11.0.10" 2021-01-19
* ItelliJ IDEA Community Edition