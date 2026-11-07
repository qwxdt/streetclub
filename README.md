# Street Club — сайт магазина

Демо-сайт магазина [The Street Club](https://t.me/streetclubbb): каталог, карточка с блоком «Наличие» (в наличии / под заказ с датой), корзина, оформление с галочкой для вещей под заказ, заказ уходит в Telegram @danilovidd.

Статический сайт без сборки: `index.html` + `img/` + `fonts/`.

## Запуск локально
```
python3 -m http.server 8000
```
и открыть http://localhost:8000

## Хостинг
Подходит любой статический хостинг: Cloudflare Pages / Vercel / Netlify (подключить репо, build command пустой, output — корень).
