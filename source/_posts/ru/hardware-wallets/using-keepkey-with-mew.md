---
title: "Использование аппаратного кошелька KeepKey с MEW"
date: 2018-06-01 00:02:00
tags:
  - keepkey
  - аппаратный
  - кошелек
categories:
  - 
    - аппаратные-кошельки
primary_category: аппаратные-кошельки
primary_category_display_name: "Аппаратные кошельки"
---

# __Использование аппаратного кошелька KeepKey с MEW__
###### {% read_time title "Использование аппаратного кошелька KeepKey с MEW" %} мин. на прочтение
***

Аппаратные кошельки KeepKey являются ведущими решениями по соответствию стандартам безопасности и удобству использования. Купить их можно [здесь](https://keepkey.myshopify.com/collections/frontpage/products/keepkey-the-simple-bitcoin-hardware-wallet/?source=hasoffers). *Пожалуйста, покупайте аппаратные кошельки у производителя или официального дистрибьютора. На аппаратные кошельки, купленные на Ebay или у других поставщиков, не распространяются гарантии безопасности.*

Аппаратные кошельки часто поддерживают несколько криптовалют, но это руководство было специально разработано для описания работы с токенам Ethereum и ERC-20 с использованием MyEtherWallet (MEW).

**Этот пункт очень важен.** Ваше устройство KeepKey является ОТДЕЛЬНЫМ кошельком. Вы не сможете импортировать свой старый адрес MEW или использовать старый кошелек с устройством. Кошелек обладает собственным закрытым ключом, зашифрованным в самом устройстве. Вам нужно будет выбрать новый адрес ethereum для использования с устройством и пользоваться им как новым основным кошельком.

Ну что ж, давайте начнем!

***

## __Начальная настройка__

**Шаг 1.** Распакуйте ваш KeepKey! Подключите его к компьютеру и загрузите [расширение для браузера KeepKey Client](https://chrome.google.com/webstore/detail/keepkey-client/idgiipeogajjpkgheijapngmlbohdhjg?hl=en-US).
* Это не типичное расширение браузера, которое отображается в его интерфейсе, как MetaMask, например. Возможно, вы захотите закрепить его на панели задач.

**Шаг 2.** В интерфейсе KeepKey Client выберите "Инициализировать устройство".
* Установите название вашего устройства.

**Шаг 3.** Настройте PIN-код для доступа к вашему устройству KeepKey. Выберите такой, который сможете легко запомнить. Запишите его в нескольких местах. Не забудьте его!! Это позволит вам разблокировать свой кошелек каждый раз, когда захотите получить к нему доступ. PIN-код должен содержать от 4 до 8 символов.
* Вводите их в правильном порядке!
* Цифры PIN-кода будут отображаться на самом устройстве.

**Шаг 4.** Это один из самых важных шагов. Не сохраняйте эту фразу на своем компьютере и не делайте ее фотографий. Запишите свои 12 seed-слов в нескольких местах. НЕ ПОТЕРЯЙТЕ ИХ. Если вы потеряете эти слова, вы потеряете также и доступ ко всей своей криптовалюте. Мы предлагаем хранить его на нескольких листках бумаги. И еще раз, не сохраняйте эту фразу на своем компьютере. Используйте ручку и бумагу.
* Фраза также будет отображаться на самом устройстве.

**Шаг 5.** Отлично, теперь ваше устройство готово! Теперь давайте разберемся, как использовать его с MyEtherWallet.

***

## __Использование KeepKey с MEW__

**Шаг 1.** Подключите и выполните вход в ваше устройство KeepKey. Откройте KeepKey Client и скачайте программное обеспечение Ethereum на свое устройство, выбрав 'Добавить учетную запись' в правом нижнем углу.
* После того, как все будет готово, закройте KeepKey Client и отключите, а затем снова подключите свое устройство.

**Шаг 2.** Теперь направляйтесь на сайт MyEtherWallet.com. Выберите "Доступ к кошельку" > "Аппаратный" > "KeepKey".

**Шаг 3.** Введите ваш PIN-код, чтобы подключиться к кошельку.

**Шаг 4.** Здесь вы увидите много адресов. Убедитесь, что вы работаете с сетью Ethereum, используете стандартный путь деривации Ethereum (derivation path), а затем выберите свой адрес.
* Правильного или неправильного выбора адреса не бывает, все зависит от ваших предпочтений. Но выбор первого — это, как правило, лучший вариант для удобства и запоминания.

**Шаг 5.** Теперь вас должны перенаправить в окно, очень похожее на окно доступа к вашему старому кошельку. Отличная работа! Теперь вы официально используете свой новый аппаратный кошелек KeepKey!

***

## __А что насчет моего старого кошелька???__

Если вы использовали старый кошелек и хотите, чтобы ваши ETH и токены были доступны на новом безопасном адресе KeepKey, вам нужно будет перевести средства на новый адрес посредством обычной транзакции. Это можно сделать, войдя в ваш старый кошелек с помощью MEWconnect, MetaMask, хранилища ключей или закрытого ключа (как вы обычно делали это до перехода на KeepKey). Переведите свои ETH и токены на новый адрес KeepKey с более безопасным доступом.

Обращаем ваше внимание, что для перевода токенов со старого кошелька потребуется оплата комиссии газа в ETH. Мы рекомендуем иметь 0.01 ETH, которых хватит для совершения 2—3 транзакций.

## __Как мне восстановить доступ к KeepKey на новом устройстве?__

Вы можете использовать фразу для восстановления, чтобы получить доступ к своему кошельку на неограниченном количестве устройств, принимающих мнемоническую фразу из 12 слов.

## __Решение проблем__

Большинство проблем с KeepKey можно решить, выполнив принудительное обновление страницы (с помощью сочетания клавиш CTRL+F5), использования последней версии прошивки, а также нового кабеля для подключения.

Как обычно, вы можете связаться с нами по адресу support@myetherwallet.com. Мы всегда рады помочь!