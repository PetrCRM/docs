## menu.getProducts: Список товаров и тех. карт

> Пример запроса:

```php
<?php
$url = 'https://joinposter.com/api/menu.getProducts'
 . '?token=687409:4164553abf6a031302898da7800b59fb'
 . '&category_id=15'
 . '&type=products';

$data = sendRequest($url);
```

> Пример ответа:

```json
{
   "response":[
      {
         "barcode":"4820098749621",
         "category_name":"Вода",
         "unit":"",
         "cost":"100",
         "cost_netto":"83",
         "fiscal":"0",
         "menu_category_id":"15",
         "workshop":"1",
         "nodiscount":"0",
         "photo":"/upload/4/menu/product_1403094564_139.jpg",
         "photo_origin":"/upload/4/menu/product_1403094564_139_original.jpg",
         "product_code":"",
         "product_id":"139",
         "product_name":"Borjomi",
         "sort_order":"999",
         "tax_id":"0",
         "product_tax_id":"2",
         "type":"3",
         "weight_flag":"0",
         "color":"white",
         "ingredient_id":"9",
         "cooking_time": "1201",
         "fiscal_code": null,
         "modifications":[
            {
               "modificator_id":"147",
               "modificator_name":"Сок яблочный для кальяна ",
               "modificator_selfprice":"0",
               "order":"0",
               "modificator_barcode":"",
               "modificator_product_code":"",
               "spots":[
                  {
                     "spot_id":"1",
                     "price":"68100",
                     "profit":"68100",
                     "profit_netto":"56750",
                     "visible":"1"
                  },
                  {
                     "spot_id":"2",
                     "price":"68100",
                     "profit":"68100",
                     "profit_netto":"56750",
                     "visible":"1"
                  },
                  {
                     "spot_id":"1",
                     "price":"68100",
                     "profit":"68100",
                     "profit_netto":"56750",
                     "visible":"1"
                  },
                  {
                     "spot_id":"2",
                     "price":"68100",
                     "profit":"68100",
                     "profit_netto":"56750",
                     "visible":"1"
                  }
               ],
               "ingredient_id":"0",
               "fiscal_code": "1234567890"
            }
         ],
         "out":0
      },
      {
         "barcode":"",
         "category_name":"Вода",
         "unit":"",
         "cost":"654",
         "cost_netto":"545",
         "fiscal":"0",
         "menu_category_id":"15",
         "workshop":"3",
         "nodiscount":"0",
         "photo":"/upload/4/menu/product_1403094497_138.jpg",
         "photo_origin":"/upload/4/menu/product_1403094497_138_original.jpg",
         "product_code":"",
         "product_id":"138",
         "product_name":"Evian",
         "sort_order":"999",
         "tax_id":"0",
         "product_tax_id":"0",
         "type":"3",
         "weight_flag":"0",
         "color":"white",
         "spots":[
            {
               "spot_id":"1",
               "price":"19000",
               "profit":"18346",
               "profit_netto":"15288",
               "visible":"1"
            },
            {
               "spot_id":"2",
               "price":"19000",
               "profit":"18346",
               "profit_netto":"15288",
               "visible":"1"
            }
         ],
         "ingredient_id":"8",
         "cooking_time": "0",
         "fiscal_code": "1231231234",
         "out":0
      },
      {
         "barcode":"",
         "category_name":"Главный экран",
         "unit":"kg",
         "cost":"0",
         "cost_netto":"0",
         "fiscal":"0",
         "hidden":"0",
         "menu_category_id":"0",
         "workshop":"1",
         "nodiscount":"0",
         "photo":"",
         "photo_origin":null,
         "price":{
            "1":"30000",
            "2":"30000"
         },
         "product_code":"",
         "product_id":"30",
         "product_name":"Обеденное меню",
         "profit":{
            "1":"30000",
            "2":"30000"
         },
         "sort_order":"999",
         "tax_id":"0",
         "product_tax_id":"0",
         "type":"2",
         "weight_flag":"0",
         "color":"white",
         "spots":[
            {
               "spot_id":"1",
               "price":"30000",
               "profit":"30000",
               "profit_netto":"30000",
               "visible":"1"
            },
            {
               "spot_id":"2",
               "price":"30000",
               "profit":"30000",
               "profit_netto":"30000",
               "visible":"1"
            }
         ],
         "ingredient_id":"0",
         "cooking_time":"0",
         "different_spots_prices":"0",
         "fiscal_code":"",
         "group_modifications":[
            {
               "dish_modification_group_id":29,
               "name":"Напитки",
               "num_min":1,
               "num_max":3,
               "is_deleted":0,
               "modifications":[
                  {
                     "dish_modification_id":142,
                     "name":"Кола",
                     "ingredient_id":77,
                     "type":2,
                     "brutto":1,
                     "price":99.99,
                     "photo_orig":"",
                     "photo_large":"",
                     "photo_small":"",
                     "last_modified_time":"2020-05-26 15:33:30"
                  },
                  {
                     "dish_modification_id":143,
                     "name":"Фанта",
                     "ingredient_id":33,
                     "type":10,
                     "brutto":200,
                     "price":99.99,
                     "photo_orig":"",
                     "photo_large":"",
                     "photo_small":"",
                     "last_modified_time":"2020-05-26 15:33:30"
                  },
                  {
                     "dish_modification_id":147,
                     "name":"Спрайт",
                     "ingredient_id":39,
                     "type":10,
                     "brutto":200,
                     "price":99.99,
                     "photo_orig":"",
                     "photo_large":"",
                     "photo_small":"",
                     "last_modified_time":"2020-05-26 15:33:30"
                  }
               ]
            },
            {
               "dish_modification_group_id":30,
               "name":"Еда",
               "num_min":1,
               "num_max":999,
               "is_deleted":0,
               "modifications":[
                  {
                     "dish_modification_id":144,
                     "name":"Картофель фри",
                     "ingredient_id":0,
                     "type":0,
                     "brutto":0,
                     "price":99.99,
                     "photo_orig":"",
                     "photo_large":"",
                     "photo_small":"",
                     "last_modified_time":"2020-05-26 15:33:30"
                  },
                  {
                     "dish_modification_id":145,
                     "name":"Снэки",
                     "ingredient_id":178,
                     "type":10,
                     "brutto":200,
                     "price":99.99,
                     "photo_orig":"",
                     "photo_large":"",
                     "photo_small":"",
                     "last_modified_time":"2020-05-26 15:33:30"
                  }
               ]
            }
         ],
         "out":100,
         "product_production_description":"",
         "ingredients":[
            {
               "structure_id":"828",
               "ingredient_id":"32",
               "pr_in_clear":"0",
               "pr_in_cook":"0",
               "pr_in_fry":"0",
               "pr_in_stew":"0",
               "pr_in_bake":"0",
               "structure_unit":"kg",
               "structure_type":"1",
               "structure_brutto":100,
               "structure_netto":100,
               "structure_lock":"1",
               "structure_selfprice":"0",
               "structure_selfprice_netto":"0",
               "ingredient_name":"Sugar",
               "ingredient_unit":"kg",
               "ingredient_weight":0,
               "ingredients_losses_clear":"0",
               "ingredients_losses_cook":"0",
               "ingredients_losses_fry":"0",
               "ingredients_losses_stew":"0",
               "ingredients_losses_bake":"0"
            }
         ]
      }
   ]
}
```

Метод возвращает список товаров и тех. карт

### HTTP запрос

`GET https://joinposter.com/api/menu.getProducts`

### GET-параметры запроса menu.getProducts

Параметр | Описание
-------- | --------
category_id | Id категории товаров. По умолчанию не передаётся.
type | Тип: products — товары, batchtickets — тех. карты. По умолчанию не передаётся.

### Параметры ответа menu.getProducts

Параметр | Описание
-------- | --------
response | Массив объектов

Внутри параметра `response` лежит массив, в каждом элементе которого есть следующие параметры:

Параметр | Описание
-------- | --------
barcode | Штриховой код товара
category_name | Название категории в которой содержится товар
hidden | Признак что товар скрыт: 0 — виден, 1 — скрыт 
unit | Единица измерения товара
cost | Себестоимость товара в копейках
cost_netto | Себестоимость товара без НДС в копейках. Возвращается если включена настройка «Считать себестоимость и прибыль нетто»
fiscal | Фискальный признак товара: 0 — не фискальный, 1 — фискальный
menu_category_id | Id категории в которой содержится товар
workshop | Id цеха товара
nodiscount | Признак, могут ли применяться скидки к этому товару: 0 — не могут, 1 — могут
photo | Фотография товара
photo_origin | Оригинал фотографии товара
product_code | Складская учётная единица товара, например, SKU
product_id | Id товара
product_name | Название товара
sort_order | Порядок сортировки товара
tax_id | Id налога товара
product_tax_id | Признак, что налог товара унаследован от налога категории: 0 — не унаследован, 1 — унаследован
type | Тип товара: 1 — полуфабрикат, 2 — тех.карта, 3 — товар
weight_flag | Признак, что товар весовой: 0 — не весовой, 1 — весовой
color | Цвет карточки товара в терминале
spots | Заведения в которых доступен товар
ingredient_id | Id ингредиента (возвращается, если товар)
cooking_time | Время приготовления блюда в секундах
product_production_description | Описание процесса приготовления
fiscal_code | Код УКТ ВЭД. Доступен только для аккаунтов из Украины, использующих фискализацию
group_modifications | Наборы модификаций  тех.карты. Возвращается, если у тех.карты есть модификации
out | Сумма нетто всех ингредиентов тех. карты, для товара всегда 0
ingredients | Список ингредиентов (возвращается, если тех. карта)

Внутри параметра `spots` лежит массив, в каждом элементе которого есть следующие параметры:

Параметр | Описание
-------- | --------
spot_id | Id заведения
price | Цена на товар в этом заведении в копейках
profit | Чистая прибыль с товара в этом заведении в копейках
profit_netto | Чистая прибыль с товара в этом заведении без НДС в копейках. Возвращается если включена настройка «Считать себестоимость и прибыль нетто»
visible | Признак, что товар скрыт в этом заведении: 0 — скрыт, 1 — виден

Внутри параметра `group_modifications` лежит массив, в каждом элементе которого есть следующие параметры:

Параметр | Описание
-------- | --------
dish_modification_group_id | Id набора модификаций тех.карты
name | Название набора модификаций тех. карты
num_min | Минимальное количество модификаций тех. карты, которые можно выбрать в заказе из набора
num_max | Максимальное количество модификаций тех. карты, которые можно выбрать в заказе из набора
is_deleted | Удален ли набор модификаций. 0 - нет, 1 - да
modifications | Модификации тех. карты из набора

Внутри параметра `modifications`, который содержится в `group_modifications` лежит массив, в каждом элементе которого есть следующие параметры:

Параметр | Описание
-------- | --------
dish_modification_id | Id модификации тех. карты
name | Название модификации тех. карты
ingredient_id | Id ингредиента (возвращается, если товар или ингредиент)
type | Тип модификации тех. карты: 1 - товар, 2 - тех. карта, 3 - полуфабрикат, 8 - модификатор товара, 10 - ингредиент, 0 - без списания
brutto | Брутто модификации тех. карты
price | Цена модификации тех. карты в деньгах
photo_orig | Оригинал фотографии модификации тех. карты
photo_large | Увеличенная фотография модификации тех. карты
photo_small | Уменьшенная фотография модификации тех. карты
last_modified_time | Время последнего изменения модификации тех. карты

Внутри параметра `ingredients` лежит массив, в каждом элементе которого есть следующие параметры:

Параметр | Описание
-------- | --------
structure_id | Id элемента тех. карты
ingredient_id | Id ингредиента 
pr_in_clear | Признак, что используется метод приготовления «очистка»: 0 — не используется, 1 — используется
pr_in_cook | Признак, что используется метод приготовления «запекание»: 0 — не используется, 1 — используется
pr_in_fry | Признак, что используется метод приготовления «жарка»: 0 — не используется, 1 — используется
pr_in_stew | Признак, что используется метод приготовления «тущение»: 0 — не используется, 1 — используется
pr_in_bake | Признак, что используется метод приготовления «варка»: 0 — не используется, 1 — используется
structure_unit | Единица измерения элемента тех. карты
structure_type | Тип элемента тех. карты: 1 — ингредиент, 2 — полуфабрикат
structure_brutto | Брутто элемента тех. карты
structure_netto | Нетто элемента тех. карты
structure_lock | Зависимость нетто от брутто: 0 — ручная, 1 — автоматическая
structure_selfprice | Цена элемента тех. карты
structure_selfprice_netto | Цена элемента тех. карты без НДС. Возвращается если включена настройка «Считать себестоимость и прибыль нетто»
ingredient_name | Название ингредиента
ingredient_unit | Единица измерения ингредиента: l — литры, kg — килограммы, p — штуки 
ingredient_weight | Количество списания ингредиента
ingredients_losses_clear | Коэффициент потерь при очистке ингредиента
ingredients_losses_cook | Коэффициент потерь при запекании ингредиента
ingredients_losses_fry | Коэффициент потерь при жарке ингредиента
ingredients_losses_stew | Коэффициент потерь при тущении ингредиента
ingredients_losses_bake | Коэффициент потерь при варке ингредиента
