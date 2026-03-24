# Техническая архитектура системы управления автопарком

## Ключевые компоненты

- **Fleet Management System (FMS)** — диспетчеризация, управление парком
- **Ride-hailing платформа** — мобильное приложение для пользователей
- **Vehicle Control Unit** — бортовой компьютер
- **Remote Monitoring & Takeover** — дистанционное управление
- **Maps & Localization** — HD-карты, GPS + LiDAR
- **AI/ML pipeline** — детекция объектов, принятие решений

## Стратегия: Build vs Buy vs Partner

На раннем этапе — использовать open-source autonomous driving стеки:
- [Autoware](https://autoware.org/) — open-source autonomous driving
- [Apollo Open Platform](https://apollo.baidu.com/) — Baidu

Фокус: fleet management и локализация под рынок Казахстана.

## Открытые вопросы

- [ ] Выбор базовой autonomous driving платформы
- [ ] Партнёрство с автопроизводителем
- [ ] V2X и 5G инфраструктура в Астане
- [ ] Требования к сертификации ТС в РК
