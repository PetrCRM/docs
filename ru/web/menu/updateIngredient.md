## menu.updateIngredient: Изменение свойств ингредиента

> Пример запроса:

```php
<?php
$url = 'https://joinposter.com/api/menu.updateIngredient'
 . '?token=687409:4164553abf6a031302898da7800b59fb';

$ingredient = [
    'id'                => 811,
    'ingredient_name'   => 'Лимон',
    'category_id'       => 4,
    'type'              => 'p',
    'weight_ingredient' => 150,
];

$data = sendRequest($url, 'post', $ingredient);
```

> Пример запроса:

```json
{
  "id": 811,
  "ingredient_name": "Лимон",
  "category_id": 4,
  "type": "p",
  "weight_ingredient": 150
}
```

> Пример ответа:

```json
{  
  "response": 811
}
```

Метод изменяет свойства ингредиента

### HTTP запрос

`GET https://joinposter.com/api/menu.updateIngredient`

### POST-параметры запроса menu.updateIngredient

Параметр | Описание
-------- | --------
id | Id ингредиента
ingredient_name | Название ингредиента
category_id | Id категории ингредиента
ingredient_barcode | Штрихкод ингредиента
type | Единица измерения ингредиента: kg — килограммы, p — штуки, l — литры. Нельзя менять единицу измерения ингредиента, если он уже поставлялся на склад.
weight_ingredient | Вес ингредиента, если ингредиент штучный
loss_clear | Коэффициент потерь при очистке ингредиента, если ингредиент не штучный
loss_cook | Коэффициент потерь при запекании ингредиента, если ингредиент не штучный
loss_fry | Коэффициент потерь при жарке ингредиента, если ингредиент не штучный
loss_stew | Коэффициент потерь при тущении ингредиента, если ингредиент не штучный
loss_bake | Коэффициент потерь при варке ингредиента, если ингредиент не штучный
partial_write_off | Признак, что можно списывать штучный ингредиент, как дробный: 0 — нельзя, 1 — можно

### Параметры ответа menu.updateIngredient

Параметр | Описание
-------- | --------
response | Id изменённого ингредиента
