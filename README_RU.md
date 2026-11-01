# FireGames.ru — сайт разработчика

Этот репозиторий содержит главную страницу разработчика FireGames и отдельный раздел игры Save The Lost.

## Структура
- `index.html` — главная страница FireGames.
- `save-the-lost/index.html` — страница игры Save The Lost.
- `save-the-lost/privacy.html` и `privacy-en.html` — политика конфиденциальности RU/EN.
- `save-the-lost/rights.html` и `rights-en.html` — права пользователей RU/EN.
- `save-the-lost/terms.html` и `terms-en.html` — условия использования RU/EN.
- `site-config.js` — общие данные разработчика для сайта и юридических страниц.
- `styles.css` — оформление.
- `PRE_RELEASE_CHECKLIST_RU.md` — список проверок перед публикацией.
- `CONSENT_DIALOG_SAMPLE_RU_EN.md` — пример текста согласия на рекламные технологии; это не готовая реализация SDK.

## До публикации
1. Заполни `site-config.js` и удали все тестовые значения.
2. Проверь фактическое поведение установленной сборки, список SDK и разрешений Android.
3. Сверь требования RuStore к раскрытию сведений физического лица и не публикуй домашний адрес/налоговый номер без проверки правового основания и требований магазина.
4. Проверь политику Яндекс Рекламы и механизм получения/передачи согласия, особенно для пользователей из ЕЭЗ/Швейцарии.
5. Проверь каждую страницу на русском и английском.

## GitHub Pages
1. Загрузи содержимое этой папки в корень репозитория `FireGames.ru` (не саму папку целиком).
2. В Settings → Pages выбери `Deploy from a branch`, branch `main`, folder `/(root)`.
3. После публикации проверь ссылки. При имени репозитория `FireGames.ru` проектный URL обычно имеет вид `https://ВАШ-USERNAME.github.io/FireGames.ru/`.

## Ссылки для магазинов
После публикации (замени username на свой GitHub username):
- RuStore Privacy Policy: `https://ВАШ-USERNAME.github.io/FireGames.ru/save-the-lost/privacy.html`
- RuStore Terms: `https://ВАШ-USERNAME.github.io/FireGames.ru/save-the-lost/terms.html`
- Huawei Privacy Policy: `https://ВАШ-USERNAME.github.io/FireGames.ru/save-the-lost/privacy-en.html`
- Huawei Data Subject Rights: `https://ВАШ-USERNAME.github.io/FireGames.ru/save-the-lost/rights-en.html`

GitHub Pages URL не становится собственным доменом `FireGames.ru` автоматически. Для этого отдельно нужен зарегистрированный домен и его подключение в настройках Pages.

Документы являются шаблонами и требуют проверки на соответствие фактической сборке и применимому законодательству; они не заменяют юридическую консультацию.
