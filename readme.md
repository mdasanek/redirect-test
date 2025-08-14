# QR-код редирект с Google Analytics

Простая страница для редиректа с отслеживанием переходов через QR-код.

## Настройка

1. **Замените `GA_MEASUREMENT_ID`** в `index.html` на ваш ID Google Analytics (формат: G-XXXXXXXXXX)
2. **Измените целевой URL** `https://xsolla.com/backpack` на нужный вам адрес

## Как получить GA Measurement ID

1. Зайдите в [Google Analytics](https://analytics.google.com/)
2. Создайте новое свойство или выберите существующее
3. В настройках найдите "Measurement ID" (начинается с G-)

## Деплой

### GitHub Pages
1. Создайте публичный репозиторий
2. Загрузите `index.html`
3. В настройках включите GitHub Pages
4. URL будет: `https://USERNAME.github.io/REPO-NAME/`

### Netlify
1. Загрузите папку с `index.html` на Netlify
2. Получите URL вида `https://*.netlify.app/`

## Отслеживание

После настройки вы сможете видеть:
- Количество переходов через QR-код
- Время переходов
- Устройства пользователей
- Географию

В GA4 смотрите: **Reports → Engagement → Events → qr_scan**
