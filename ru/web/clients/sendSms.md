## clients.sendSms: Отправка SMS от имени аккаунта

> Пример запроса:

```php
<?php
$url = 'https://joinposter.com/api/clients.sendSms'
 . '?token=687409:4164553abf6a031302898da7800b59fb';

$sms = [
    'phone' => 380684113524,
    'message' => 'У вас осталось 10 бонусов на счету'
];

$data = sendRequest($url, 'post', $sms);

```

> Пример ответа:

```json
{
  "response":true
}
```

Метод отправляет SMS от имени аккаунта Poster.

<aside class="warning">
    СМС оплачиваются отдельно. Стоимость — 63 копейки для Украины или 2 рубля для России, за одно сообщение. 
    Функция доступна только для платных клиентов Poster.
    
</aside>

<aside class="info">
    На данный момент SMS можно отправлять только на российские и украинские номера. 
    Российские номера должны начинаться с 7, украинские с 380.
</aside>

### HTTP запрос

`POST https://joinposter.com/api/clients.sendSms`

### POST-параметры запроса clients.sendSms

Параметр | Описание
-------- | --------
phone | Номер телефона на которые отправляется SMS. Номер должен быть в международном формате, без лидирующего +. 
message | Текст SMS сообщения  

### Параметры ответа clients.sendSms

Параметр | Описание
-------- | --------
response | Результат отправки SMS: `true` – если отправлена, иначе вернется объект ошибки
