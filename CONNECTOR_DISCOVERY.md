# Kubecost Connector — Connector Discovery

**Vendor API Baseline:** https://kubecost.com

## Архитектура API
- **Базовый адрес:** `http://<kubecost-endpoint>:9090/model`
- **Протокол:** REST / HTTPS (JSON)
- **Аутентификация:** Basic Auth / Bearer Token / Port-forwarding
- **Ключевые эндпоинты:**
  - распределение затрат (/allocation)
  - утилизация ресурсов (/assets)
  - рекомендации (/recommendations)
- **Тестовая точка проверки подключения:** `GET /model/allocation`.
