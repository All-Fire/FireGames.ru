# Пример текста окна согласия для Save The Lost / Yandex Ads

Этот текст — пример для интерфейса игры, а не готовая техническая реализация или юридическая гарантия соответствия.

## Русский

**Заголовок:** Реклама и конфиденциальность

**Текст:** В Save The Lost используется рекламная система Yandex Ads. При согласии Yandex Mobile Ads SDK может обрабатывать рекламный идентификатор и техническую информацию об устройстве и сетевом соединении для загрузки, показа и измерения рекламы, а также защиты от недействительных показов и кликов. Подробнее о данных и обработке — в [Политике конфиденциальности] и [Политике рекламных сервисов Яндекса].

**Кнопки:** `Принять` · `Отклонить` · `Подробнее`

**Короткое пояснение:** Отказ от согласия не должен блокировать основной игровой процесс. Доступность или персонализация рекламы может измениться.

## English

**Title:** Advertising and Privacy

**Text:** Save The Lost uses Yandex Ads. If you consent, the Yandex Mobile Ads SDK may process your advertising ID and technical information about your device and network connection to request, display and measure ads and prevent invalid impressions or clicks. Learn more in our [Privacy Policy] and [Yandex Advertising Services Privacy Policy].

**Buttons:** `Accept` · `Decline` · `Learn more`

**Short note:** Declining consent should not block the core gameplay. Ad availability or personalisation may be affected.

## Техническая проверка

Документация Yandex указывает, что для пользователей из ЕЭЗ и Швейцарии согласие нужно передавать в SDK при каждом запуске приложения. Перед интеграцией проверь API именно той версии SDK, которая фактически встроена в UE-плагин. В документации SDK отдельно сказано, что параметры политик конфиденциальности нужно настроить до инициализации SDK.
