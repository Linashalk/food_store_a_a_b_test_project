# Сборный проект №2
Сборный проект №2 в Яндекс Практикум.

В нашем распоряжении данные стартапа, который продаёт продукты питания. Дизайнеры захотели поменять шрифты в приложении, а менеджеры испугались, что пользователям будет непривычно. Договорились принять решение по результатам A/A/B-теста. Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми.

**Цель исследования** - изучить воронку продаж и исследовать результаты A/A/B-тестирования (выяснить, какой шрифт лучше).

**Стек:**
Pandas, matplotlib, seaborn, numpy

**Итоги исследования:**

Мной был проведен обзор и предобработка данных, изучена воронка событий, выполнен анализ А/А/В-теста, проанализированы результаты эксперимента и сделаны выводы. 

Воронка выглядит следующим образом: 98% пользователей сначала попадают на главный экран (MainScreenAppear), затем 61.91% пользователей попадает в раздел предложений/каталог (OffersScreenAppear), далее 81.3% пользователей переходит в корзину (CartScreenAppear), потом 94.78% пользователей переходит на экран оплаты (PaymentScreenSuccessful). А событие "руководство/консультация/обучение" (Tutorial) может происходить как в конце нашей воронки, так и, например, до покупки товара - все зависит от пользователя.

При изучении результатов эксперимента я выяснила, что статистически значимых отличий между группами нет, значит смена шрифта никак не повлияла на пользователей. 
