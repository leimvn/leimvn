| Описание                                                                                                                                          | ОР                                  | Статус |
|---------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------|--------|
| КУРЬЕРСКАЯ ДОСТАВКА                                                                                                                               |                                     |        |
| Доставка: ""Привезём быстро""  POST /fast-delivery/v3.1.1/calculate-delivery.xml                                                                  |                                     |        |
| hostDeliveryCost - 23 руб.                                                                                                                        |                                     |        |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 0<br>productsWeight - 1.5<br>deliveryTime - 08                 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 23 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
|                                                                                                                                                   | Логика                              | FAILED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 4<br>productsWeight - 0<br>deliveryTime - 14                   | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 23 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
|                                                                                                                                                   | Логика                              | FAILED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 4<br>productsWeight - 0.1<br>deliveryTime - 07                 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 23 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 1<br>productsWeight - 1.5<br>deliveryTime - 14                 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 23 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 7<br>productsWeight - 2.4<br>deliveryTime - 20                 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 23 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 6<br>productsWeight - 2.5<br>deliveryTime - 20                 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 23 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 6<br>productsWeight - 2.4<br>deliveryTime - 21                 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 23 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
| hostDeliveryCost - 43 руб.                                                                                                                        |                                     |        |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 8<br>productsWeight - 2.4<br>deliveryTime - 20                 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 43 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 9<br>productsWeight - 2.6<br>deliveryTime - 20                 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 43 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 11<br>productsWeight - 2.7<br>deliveryTime - 20                | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 43 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 13<br>productsWeight - 4.5<br>deliveryTime - 20                | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 43 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 14<br>productsWeight - 5.9<br>deliveryTime - 20                | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 43 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 0.1<br>productsWeight - 6<br>deliveryTime - 20                 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 43 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 0.1<br>productsWeight - 5.9<br>deliveryTime - 21               | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 43 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 0 руб.         | PASSED |
| clientDeliveryCost - 99 руб | hostDeliveryCost - 43 руб                                                                                           |                                     |        |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 15<br>productsWeight - 4<br>deliveryTime - 20                  | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 43 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 99 руб.        | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 16<br>productsWeight - 4<br>deliveryTime - 20                  | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 43 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 99 руб.        | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 13<br>productsWeight - 6.1<br>deliveryTime - 20                | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 43 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 99 руб.        | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 13<br>productsWeight - 6.2<br>deliveryTime - 20                | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 43 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 99 руб.        | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 50<br>productsWeight - 4<br>deliveryTime - 20                  | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 43 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 99 руб.        | PASSED |
| Узнать стоимость доставки ""Привезем быстро"" и ее наличие при:<br>productsCount - 13<br>productsWeight - 25<br>deliveryTime - 20                 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | PASSED |
|                                                                                                                                                   | Наличие доставки TRUE               | PASSED |
|                                                                                                                                                   | hostDeliveryCost - 43 руб.          | PASSED |
|                                                                                                                                                   | clientDeliveryCost - 99 руб.        | PASSED |
| НЕГАТИВНЫЕ ПРОВЕРКИ / ДОСТАВКА                                                                                                                    |                                     |        |
| Проверить, что доставка ""Привезем быстро""  недоступна в нерабочее время 22-06<br>productsCount - 4<br>productsWeight - 1.5<br>deliveryTime - 22 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
|                                                                                                                                                   | Наличие доставки FALSE              | FAILED |
| Проверить, что доставка ""Привезем быстро""  недоступна в нерабочее время 22-06<br>productsCount - 4<br>productsWeight - 1.5<br>deliveryTime - 23 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
|                                                                                                                                                   | Наличие доставки FALSE              | FAILED |
| Проверить, что доставка ""Привезем быстро""  недоступна в нерабочее время 22-06<br>productsCount - 4<br>productsWeight - 1.5<br>deliveryTime - 02 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
|                                                                                                                                                   | Наличие доставки FALSE              | FAILED |
| Проверить, что доставка ""Привезем быстро""  недоступна в нерабочее время 22-06<br>productsCount - 4<br>productsWeight - 1.5<br>deliveryTime - 05 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
|                                                                                                                                                   | Наличие доставки FALSE              | FAILED |
| Проверить, что доставка ""Привезем быстро""  недоступна в нерабочее время 22-06<br>productsCount - 4<br>productsWeight - 1.5<br>deliveryTime - 06 | Код и статус ответа 200 ОК          | PASSED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
|                                                                                                                                                   | Наличие доставки FALSE              | FAILED |
| Проверить появление ошибки при некорректном значении: отриц. число<br>productsCount - ""-1"                                                       |                                     |        |
| Код и статус ответа 400 Bad Request                                                                                                               | FAILED                              |        |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
| Проверить появление ошибки при некорректном значении: отриц. число<br>productsCount - 4<br>productsWeight -  ""-1"                                |                                     |        |
| Код и статус ответа 400 Bad Request                                                                                                               | FAILED                              |        |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
| Проверить появление ошибки при некорректном значении: отриц. число<br>productsCount - 1<br>productsWeight -  1<br>deliveryTime -  (-20)           | Код и статус ответа 400 Bad Request | FAILED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
| Проверить появление ошибки при некорректном значении: десятичное число<br>productsCount - 1<br>productsWeight -  1<br>deliveryTime -  20.5        | Код и статус ответа 400 Bad Request | FAILED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
| Проверить появление ошибки при некорректном значении: десятичное число<br>productsCount - 1.5<br>productsWeight - 1<br>deliveryTime - 20          | Код и статус ответа 400 Bad Request | FAILED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
| Проверить появление ошибки при пустом значении запроса:<br>productsCount - (  )<br>productsWeight - 1.5<br>deliveryTime - 20                      | Код и статус ответа 400 Bad Request | FAILED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
| Проверить появление ошибки при пустом значении запроса:<br>productsCount - 4<br>productsWeight - (  )<br>deliveryTime - 20                        | Код и статус ответа 400 Bad Request | FAILED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
| Проверить появление ошибки при пустом значении запроса:<br>productsCount - 4<br>productsWeight - 1.5<br>deliveryTime - (  )                       | Код и статус ответа 400 Bad Request | FAILED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
| Проверить появление ошибки 400 при отсутствие тегов количества продуктов:<br>productsWeight - 1.5<br>deliveryTime - 20                            | Код и статус ответа 400 Bad Request | FAILED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
| Проверить появление ошибки 400 при отсутствие тегов веса продуктов:<br>productsCount - 4<br>deliveryTime - 20                                     | Код и статус ответа 400 Bad Request | FAILED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
| Проверить появление ошибки 400 при отсутствие тегов времени доставки<br>productsCount - 4<br>productsWeight - 1.5                                 | Код и статус ответа 400 Bad Request | FAILED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
| Проверить появление ошибки 400 при отсутствие всех обязательных тегов со значениями:<br><InputModel><br></InputModel>                             | Код и статус ответа 400 Bad Request | FAILED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
| Проверить появление ошибки 400 при пустом теле запроса                                                                                            | Код и статус ответа 400 Bad Request | FAILED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
| Проверить появление ошибки 400 при слишком длинном значении (напр. 1000000000000000000)                                                           | Код и статус ответа 400 Bad Request | FAILED |
|                                                                                                                                                   | Ошибок в структуре ответа нет       | FAILED |
