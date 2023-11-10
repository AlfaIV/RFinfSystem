# Задание дополнительное по курсу РСПИ

![РСПИ](png/антенны.png)
------

1. Изобразите в draw.іо схему DPCM кодера, формирующего на выходе сигнал ошибки $e(n) = s(n) - \widehat{s}_q(n)$, где $$\widehat{s}_q(n) = \sum_{i=1} ^{p} a(i)s_q(n - i)$$ поступающего на АЦП и затем передаваемого по каналу связи.

1. Изобразите в draw.іо схему DPCM декодера, формирующего на выходе востановленный сигнал из сигнала ошибки, принятого по каналу связи.
    
    * коэффициенты в кодере и декодере сигнала предполагаются заранее вычисленными и постоянными в течение некоторого интервала времени

1. Напишите следующие функции, реализующие операции кодирования/декодирования первичного сигнала источника информации:

    * функция расчета коэффициентов предсказания $a(i)$, предсказывающего значение сигнала по входящему сигналу ошибки.

    * функция DPCM-кодера, по схеме из п.1‚ принимающая на вход нормированный сигнал с нулевым математическим ожиданием и формирующим b—битный целочисленный сигнал ошибки на выходе (разрядность квантования необходимо получить у преподавателя индивидуально);

    * функция DPCM-декодера, по схеме из п.2, восстанавливающего исходный сигнал из сигнала ошибки.

1. Определите оптимальное значение порядка предсказывающего фильтра для сигнала из первой части домашнего задания по критерию максимума значения SQNR. Сравните результаты работы схемы компандирования и дифференциального кодирования.

##Решение
Можно посмотреть решение онлайн и оставить комментарии на Google Collab по следующей ссылке:

[Ссылка на Google Collab](https://colab.research.google.com/drive/1iqZ7XkYdhZiXfOxD7mM09mJUs2Te0vpB?usp=sharing)

Решение также лежит в файле в расширением *.ipynd. Можно его открыть и GitHub должен его отобразить прямо в браузере.