## Описание

Мобильная игра зарабатывает на показе рекламы.

Есть несколько форматов:

+ `int` – полноэкранная реклама;
+ `banner` – горизонтальный баннер, висит внизу экрана пока юзер играет;
+ `rv` – видео, которое юзер смотрит по желанию и за просмотр получает монетки или др. ресурсы.

Информация о каждом показе отправляется в аналитику и содержит доход от показа, формат показанной рекламы, рекламную сеть от которой был показ и др.

*Задача*

Провести исследование показов рекламы с целью понять на сколько отличается eCPM в зависимости от географии (города) юзера, версии ОС и других параметров.

`pip list`
+ plotly 5.8.2
+ kaleido 0.2.1
+ pandas 1.4.2
+ все их зависимости

Что бы скачать - git clone https://github.com/Korfour/eda_ad_revenue.git

Что бы при запуске ноутбука графики стали интерактивными нужно удалить строку `pio.renderers.default='svg'` в ноутбуке она находится в ячейке с импортами библиотек.
