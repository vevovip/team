Отпечаток браузера
===

## Что такое Browser Fingerprint?

Это идентификация браузеров (присвоение идентификатора браузеру).

## Для чего используется Browser Fingerprint?

* для учета неавторизованных пользователей
* если пользователь пришел во второй раз, мы хотим знать, на какие страницы он заходил, что он до этого делал
* внутренняя аналитика

## Технические делати

Отпечаток отправляется в виде заголовка `X-Agent-Fingerprint`.

Например:

```json
{
		"X-Agent-Fingerprint": "976f3f264393f32e5e1544c54c09afd8"
}
```