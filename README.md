# Оптимизация маркетинговых затрат в Яндекс.Афише

Для этого проекта были использованы:
- Python;
- Pandas;
- Matplotlib;
- когортный анализ; 
- продуктовые метрики;
- юнит-экономика.

На основании подготовленных данных от Яндекс.Афиши  рассчитала и проанализировала объемы продаж сайта по дням, неделям и месяцам с разных устройств (desctop, touch), а также средний чек.

Затем были построены профили пользователей, в дальнейшем разбитые на когорты, и рассчитала сколько денег приносят пользователи (LTV), сколько стоило привлечение одного покупателя (CAC) и насколько окупились расходы (ROMI).

Проведен анализ посещений, прибыли и маркетинговых расходов сервиса Яндекс.Афиша за период с июня 2017 года по май 2018 года.

Пользователи июня 2017 года в большем количестве случаев, чем все остальные возвращаются на сайт. Даже через 11 месяцев 4,5% пользователей этой когорты посещают сайт. Самые жизнеспособные источники привлечения пользователей - 1,2 и 9. Их Retention Rate в первый месяц составляет от 13% до 16%. И затем на протяжении года пользователи из этих источников продолжают пользоваться сервисом. Пользователи desktop-версии сайта возвращаются чаще, чем пользователи touch-версии.

Самым активным месяцем как для посещений, так и для покупок является декабрь.

Пользователи desktop-версии сервиса совершают более дорогие покупки нежели пользователи touch-версии. Средний чек первых варьируется от 5.02 у.е. до 5.8 у.е., вторых - от 3,21 у.е. до 4,84 у.е.
 
Самые высокие расходы на привлечение одного пользователя приходятся на третий источник привлечения пользователей (13.49 у.е.). При этом ежемесячный прирост доходов по этому источнику привлечения недостаточно большой и за исследуемый период затраты на привлечение пользователей по этому источнику не окупились. При аналогичных расходах во втором источнике привлечения клиентов (12.21 у.е.), они окупаются уже на шестой месяц. Расходы на привлечение одного пользователя на первый источник составляют 7.19 у.е., и окупаются они уже на третий месяц. Также, несмотря на сравнительно небольшие сас в 9 и 10 источниках привлечения (5.01 у.е. и 4.38 у.е. соответственно), эти источники практически не окупаются. 
