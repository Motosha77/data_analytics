## Анализ пользовательского поведения в мобильном приложении ##

**Описание проекта**

**Дано:** мобильное приложение по продаже продуктов питания.

**Найти:** как ведут себя пользователи приложения.
- Построить событийную воронку; 
- Выяснить, как пользователи доходят до покупки. 
- Сколько пользователей доходит до покупки, а сколько — «застревает» на предыдущих шагах? 
- Исследовать результаты A/A/B теста


**Выводы:**

1. В воронке 5 событий: Tutorial, MainScreenAppear, OffersScreenAppear, CartScreenAppear, PaymentScreenSuccessful.  
Раздел Tutorial посещают лишь 11% пользователей, что говорит о неэффективности обучения.
2. Больше всего клиентов теряется на шаге OffersScreenAppear - минус 38,38% от пользователей, перешедших с главного экрана.  
Зато следующие этапы воронки отличаются хорошим удержанием пользователей.
3. Доля юзеров, прошедших все этапы воронки составляет 48%.
4. Результаты A/A/B теста:
    - Контрольные группы статистических различий не имеют, что хорошо.
    - Контрольные и тестовая группа не имеют статистических различий, тем самым можно предположить,  
    что изменение шрифтов не повлияло на пользовательскую воронку.
