# Dedicated Server 2026 by Cryptor aka CryptoeDev aka Артём Петров

### Полностью рабочий сервер боев **Warface**, который поддерживает:

- **PvE режимы.** Рабочая AI-система, передвижение ботов (Movement), стрельба.  
- **PvP режимы** и полные конфигурации к ним.  
- Полностью восстановленная **CGame структура**, необходимая для функционирования сервера боя.  
- Восстановленные вызовы пакетов:  
  `update_achievement`, `setserver`, `mission_load`, `mission_update`, `mission_unload`, `telemetry_stream`, `getprofile`, `set_rewards_info`.

### Бонусы в комплекте:
- Конфигурации (`dedicated.pak` → содержимое папки `content`).  
- `GameScriptsC_X64.pak` — обязательный файл для `.lua` скриптинга, на котором работает AI-система.  
- **AntiCheat:** Фрагмент защиты, предотвращающий использование читов. Обнаруживает нелегитимные попадания по гранатам и отправляет пакет дисконнекта при аномально частых пакетах `Climb` (характерно для невидимки/десинхронизации).

**GameClient:** `warfacedistrib525`

---

**Автор:** GitHub: [cryptoeDev](https://github.com/cryptoeDev) Discord: cryptowallettelegram
