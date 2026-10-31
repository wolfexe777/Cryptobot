# Источники и лицензии Gate ZEC News

Программа GPL-3.0; полный текст LICENSE.txt. Финансовая модель broker.py и
блокировка locking.py взяты из ранее созданного GatePaper этого репозитория.
Остальные модули этой сборки реализованы самостоятельно.

Публичный Gate Futures USDT API: https://www.gate.com/docs/developers/apiv4/en/
Используются только contracts/ZEC_USDT, candlesticks, order_book и funding_rate
на https://api.gateio.ws/api/v4/futures/usdt. Закрытые API и ордера не используются.

RSS: https://z.cash/blog/feed/, https://electriccoin.co/blog/feed/,
https://zfnd.org/feed/, https://www.coindesk.com/arc/outboundfeeds/rss/,
https://cointelegraph.com/rss. Это предполагаемые публичные адреса издателей;
доступ из облака вернул 403, поэтому проверка выполняется на ПК при запуске.
Правила могут ошибаться; принадлежность публикации издателю не доказывает факт.

Издательские материалы не включены в ZIP: новостные примеры в tests являются
искусственными техническими фикстурами. Нет исторического набора новостей,
проверки прибыльности или переноса результатов ETH на ZEC.

Windows CPython: python-build-standalone Astral release 20261026; точная ссылка
и SHA256 в runtime-lock.json. Все лицензии runtime сохранены внутри runtime.
