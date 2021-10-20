# Вакансии

Используется стандартное [API Suite CRM](https://docs.suitecrm.com/developer/api/developer-setup-guide/)

## Получение списка наименований вакансий

Предварительно необходимо [зарегистрировать](https://talentforce.ru/) приложение.

**Запрос**

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

**Пример ответа**

```json
{
    "token_type": "Bearer",
    "expires_in": 3600,
    "access_token": "полученный_access_token",
    "refresh_token": "полученный_refresh_token"
}
```

### Создание наименования вакансии

Предварительно необходимо [зарегистрировать](https://talentforce.ru/) приложение.

**Запрос**

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

**Пример ответа**

```json
{
    "token_type": "Bearer",
    "expires_in": 3600,
    "access_token": "полученный_access_token",
    "refresh_token": "полученный_refresh_token"
}
```

#### Получение user ID из user_name созданного наименования вакансии

Предварительно необходимо [зарегистрировать](https://talentforce.ru/) приложение.

**Запрос**

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

**Пример ответа**

```json
{
    "token_type": "Bearer",
    "expires_in": 3600,
    "access_token": "полученный_access_token",
    "refresh_token": "полученный_refresh_token"
}
```

#### Создание вакансии

Предварительно необходимо [зарегистрировать](https://talentforce.ru/) приложение.

**Запрос**

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

**Пример ответа**

```json
{
    "token_type": "Bearer",
    "expires_in": 3600,
    "access_token": "полученный_access_token",
    "refresh_token": "полученный_refresh_token"
}
```
