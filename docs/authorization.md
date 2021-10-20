# Авторизация

Для выполнения большинства запросов к API необходимо передавать access-токен.
Авторизация осуществляется по протоколу [OAuth 2.0](#links).

## Получение access-токена

Предварительно необходимо [зарегистрировать](https://talentforce.ru/) приложение.

Необходимо отправить POST-запрос на:

`{{talentforce.url}}/Api/access_token`

В *Body* передать:

```json
{
"client_id":"полученный_client_id",
"client_secret":"полученный_client_secret",
"username":"полученный_username",
"password":"полученный_password"
"grant_type":"password"
}
```

*Пример ответа*

```json
{
    "token_type": "Bearer",
    "expires_in": 3600,
    "access_token": "полученный_access_token",
    "refresh_token": "полученный_refresh_token"
}
```

## Использование access-токена

Приложение должно использовать полученный `access_token` для авторизации,
передавая его в заголовке в формате:

```Authorization: Bearer полученный_access_token```

или используя тип авторизации = OAuth 2.0:

```Available Tokens: полученный_access_token```
