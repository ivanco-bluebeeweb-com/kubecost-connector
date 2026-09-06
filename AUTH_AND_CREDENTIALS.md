# Kubecost Connector — Auth & Credentials Standard

**Compliance:** AUTH_AND_CREDENTIALS_STANDARD.md (B1–B10)

## Схема аутентификации
- **Метод:** Basic Auth / Bearer Token / Port-forwarding
- **Хранение:** Секреты сохраняются изолированно в хранилище секретов платформы Imperal.
- **Валидация:** При сохранении ключа выполняется тестовый запрос `GET /model/allocation`.
- **Отключение:** Удаление локальных ключей без воздействия на аккаунт вендора.
