[README.txt](https://github.com/user-attachments/files/34862735/README.txt)
OSINTGRAPH MOBILE PRO — STATIC, NO API KEYS REQUIRED

МОБИЛЬНАЯ АДАПТАЦИЯ:
- Телефонный интерфейс с нижней навигацией: Граф / Узлы / Поиск / Детали / Ещё.
- Панели открываются на весь экран; крупные элементы управления.
- Рабочее поле занимает основную часть экрана.
- Десктопный интерфейс автоматически показывает боковые панели.

ФУНКЦИИ ГРАФА:
- 16 типов сущностей: Person, Telegram, Instagram, TikTok, Email, Domain, IP, Phone, Username, Image, Location, Company, Device, Document, URL, Hash.
- Добавление, перемещение, редактирование, удаление, дублирование узлов.
- Связи между узлами, подписи и цвета связей.
- Поиск по графу, раскладки, zoom/pan, fit view.
- Black/White theme, размер узлов, толщина линий.
- Undo/Redo, autosave в LocalStorage, импорт/экспорт JSON.
- Экспорт PNG с водяным знаком t.me/osintgraph0.

ПОИСКИ БЕЗ API:
- Web: DuckDuckGo, Google, Bing, Brave, GitHub, Reddit — открываются поисковые страницы.
- Username: быстрые ссылки на публичные профили GitHub, Reddit, Telegram, Instagram, TikTok, YouTube, X, Twitch. Наличие профиля проверяется вручную.
- Domain: RDAP/WHOIS, DNS A/AAAA/MX/NS/TXT через публичный Cloudflare DNS-over-HTTPS, Certificate Transparency через crt.sh.
- IP: RDAP lookup публичного IP-диапазона и веб-поиск.
- Hash: веб-поиск точного хеша и публичная страница VirusTotal.
- Никакие приватные базы или обход авторизации не используются.

ОГРАНИЧЕНИЯ:
- Поисковые сайты открываются отдельно; браузерные запросы к публичным сервисам могут быть ограничены CORS или доступностью.
- Это клиентский инструмент, не серверная система. Проекты сохраняются в LocalStorage конкретного браузера. Регулярно экспортируй JSON.
- Не добавляй чужие чувствительные персональные данные без законного основания.
