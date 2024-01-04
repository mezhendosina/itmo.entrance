![Frame 10 (2)](https://github.com/mezhendosina/itmo.entrance/assets/80736171/cfd4d240-d88f-4852-87f1-10d2ebf9e86d)

# itmo.Entrance
Пропуск во все корпуса университета ИТМО в часах на WearOS
> Необходимо иметь аккаунт itmo.id и быть студентом ИТМО :)

## Как это работает?
С приложения на смартфоне необходимо авторизоваться под своим аккаунтом itmo.id. После этого на часы передается SSO токен ИСУ, который далее хранится на часах. 

Когда Вы заходите в приложение на часах, они вставляют этот SSO в куки и делают запрос до QR-кода с пропуском

## Что использовалось?
📱 Android-приложение:
- XML
- Retrofit
- Hilt

⌚ WearOS приложение:
- Compose
- Retorift
- Hilt