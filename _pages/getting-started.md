---
layout: page
title: Торговля криптовалютами с Reverie
permalink: /getting-started/
---

### Вступление

Крайне важно изучить инструкцию и понять все детали.

Торговля фьючерсами только по правилам: `5-20%` от депозита (зависит от суммы) с плечами до `х5`. Нарушение правил приведет к потери денег. 

Если у вас есть трудности с терминологией или техническими вопросами - вы найдете все ответы в нашем блоге. Там вы найдете обьяснения непонятных вещей для новичков, обучение и инструкции.

### Что это?

Это целая серия алгоритмов разработанная нами для того, что бы торговать криптовалютами легко. Скрипты написаны на языке PineScript на платформе TradingView и запускаются на ней же. Исполнение скрипта происходит на серверной стороне TradingView, а рендеринг (отрисовка графических элементов) - у вас в браузере. Это значит, что все самое сложное берет на себя платформа, и для использования скрипта вам не нужно мощное железо.

### Почему лучше пользоваться алгоритмом?

Самая большая проблема всех трейдеров - эмоции. Мы уже прошли тот этап, когда торгуя руками мы не заходили в сделку там, где надо было, а выходили где не надо было. Трейдер, находящийся в сделке и трейдер без сделки в данный момент - два разных, с точки зрения психики, человека. Новичкам особенно трудно справиться с эмоциями и принимать верные решения, чаще всего это заканчивается потерей средств. На помощь приходит алгоритм, полностью избавляющий нас от этих проблем. Именно поэтому профи торгуют только с софтом.

## Инструкции

Это пример работы индикатора.

"Buy" - становитесь в позицию Long, покупаете.
"Sell" - продаете. Если до этого вы стояли в Long'е, то нужно закрыть покупку и открыть продажу.
"ТP" - закройте часть позиции, так вы уже частично будете в профите.
"Exit Buy/Sell" - полностью закрываете позицию. Это может быть 30% или 50% от позиции.

[<img src="{{ site.baseurl }}/images/testChart.png" alt="алгоритмический трейдинг"/>]({{ site.baseurl }}/)

У индикатора нет настроек, мы зашили правильные параметры заранее и подготовили его для работы с монетами:

- KSM/USDT
- ICX/USDT
- NEAR/USDT
- 1INCH/USDT
- ADA/USDT
- AXS/USDT
- BNB/USDT
- ETH/USDT

Только на 45 минутном таймфрейме!
На других монетах и таймфреймах индикатор, на данный момент, не работает!

### Бектест

Бектест - проверка работы алгоритма на истории, что бы узнать была ли стратегия прибыльной. Мы подготовили бектесты для списка монет выше. Синяя зона на графике - прибыль, а красная просадки. 
Небольшие убытки всегда были и будут у всех. Никто не видит будущего, однако на таких бектестах мы можем видеть что стратегия работала месяцами успешно и на диастанции оказалась профитной.

###### Данные ниже приведены с начальными переменными: 
- 1000$ стартового депозита.
- Вход в каждую сделку на 30% от депозита

#### 1INCHUSDT
1114% прибыли при 1.8% максимальных убытков. Профит фактор: 26.98
[<img src="{{ site.baseurl }}/images/backtest/1INCHUSDT.png" alt="Бектест 1INCHUSDT алгоритмический трейдинг"/>]({{ site.baseurl }}/)

#### ADAUSDT
1253% прибыли при 1.2% максимальных убытков. Профит фактор: 41.13
[<img src="{{ site.baseurl }}/images/backtest/ADAUSDT.png" alt="Бектест ADAUSDT алгоритмический трейдинг"/>]({{ site.baseurl }}/)

#### AXSUSDT
1774% прибыли при 1.3% максимальных убытков. Профит фактор: 49.6
[<img src="{{ site.baseurl }}/images/backtest/AXSUSDT.png" alt="Бектест AXSUSDT алгоритмический трейдинг"/>]({{ site.baseurl }}/)

#### BNBUSDT
263% прибыли при 0.75% максимальных убытков. Профит фактор: 41.9
[<img src="{{ site.baseurl }}/images/backtest/BNBUSDT.png" alt="Бектест BNBUSDT алгоритмический трейдинг"/>]({{ site.baseurl }}/)

#### ETHUSDT
611% прибыли при 1.3% максимальных убытков. Профит фактор: 43.2
[<img src="{{ site.baseurl }}/images/backtest/ETHUSDT.png" alt="Бектест ETHUSDT алгоритмический трейдинг"/>]({{ site.baseurl }}/)

#### ICXUSDT
2500% прибыли при 2.8% максимальных убытков. Профит фактор: 33.9
[<img src="{{ site.baseurl }}/images/backtest/ICXUSDT.png" alt="Бектест ICXUSDT алгоритмический трейдинг"/>]({{ site.baseurl }}/)

#### KSMUSDT
1468% прибыли при 1.6% максимальных убытков. Профит фактор: 46.9
[<img src="{{ site.baseurl }}/images/backtest/KSMUSDT.png" alt="Бектест KSMUSDT алгоритмический трейдинг"/>]({{ site.baseurl }}/)

#### NEARUSDT
2800% прибыли при 2.4% максимальных убытков. Профит фактор: 52.5
[<img src="{{ site.baseurl }}/images/backtest/NEARUSDT.png" alt="Бектест NEARUSDT алгоритмический трейдинг"/>]({{ site.baseurl }}/)

### Что дальше?

Что бы получить доступ к индикатору, вам нужно написать [Сюда](https://t.me/engineerios). Мы дадим вам адрес криптокошелька. Стоимость 50$ в месяц. После оплаты вы получите доступ к индикатору.

Для торговли вам нужно:
- Аккаунт на сайте [TradingView](tradingview.com). Там будет работать индикатор.
- Сам индикатор "Reverie".
- Аккаунт на бирже [Binance](http://binance.com).
- Верифицировать акканут на бирже.
- Перевести средства на фьючерсны для торговли.

После того как вы поулчите доступ к индикатору вы можете применить его на графике. Выберите любой из списка выше график. Далее нажмите на кнопку индикаторов на панеле вверху. Выберите вкладку индикаторов с ограниченным доступом и выберите "Reverie A" что бы применить его на графике.

[<img src="{{ site.baseurl }}/images/howtoadd.png" alt="алгоритмический трейдинг"/>]({{ site.baseurl }}/)

Торговать можно и на других биржах, таких как [KuCoin](https://www.kucoin.com). Нам же больше нравится именно Binance. Делать сделки на фьючерсах можно как на ПК, так и в мобильном приложении. У TradingView так же есть мобильное приложение, что позволяет вообще не сидеть за монитором.

Вы будете использовать фьючерсы для торговли. Это нужно для того, чтобы зарабатывать как на росте, так и на падении цены. Индикатор будет подсказывать когда вставать в позицию на повышение (Long/Buy), а когда на понижение (Short/Sell) и когда закрывать сделку. Находиться в сделке можно неограниченное количество времени, однако лучше доверять индикатору и обязательно придерживаться риск-менеджменту.

[ENG]({{ site.baseurl }}/getting-started-ENG)