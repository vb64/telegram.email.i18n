# EmailGateBot FAQ

- [Насколько надежный хостинг у бота?](#%D0%BD%D0%B0%D1%81%D0%BA%D0%BE%D0%BB%D1%8C%D0%BA%D0%BE-%D0%BD%D0%B0%D0%B4%D0%B5%D0%B6%D0%BD%D1%8B%D0%B9-%D1%85%D0%BE%D1%81%D1%82%D0%B8%D0%BD%D0%B3-%D1%83-%D0%B1%D0%BE%D1%82%D0%B0-%D0%BD%D0%B0%D1%81%D0%BA%D0%BE%D0%BB%D1%8C%D0%BA%D0%BE-%D0%B2%D0%B5%D0%BB%D0%B8%D0%BA-%D1%88%D0%B0%D0%BD%D1%81-%D1%87%D1%82%D0%BE-%D0%B1%D0%BE%D1%82-%D0%BF%D0%B5%D1%80%D0%B5%D1%81%D1%82%D0%B0%D0%BD%D0%B5%D1%82-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%D1%82%D1%8C-%D0%B2-%D1%81%D0%B0%D0%BC%D1%8B%D0%B9-%D0%BE%D1%82%D0%B2%D0%B5%D1%82%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9-%D0%BC%D0%BE%D0%BC%D0%B5%D0%BD%D1%82)
- [Что означает сообщение 'обработано ранее'?](#%D0%B2%D0%B5%D1%87%D0%B5%D1%80%D0%BE%D0%BC-%D1%8F-%D0%B7%D0%B0%D0%B1%D1%8B%D0%BB-%D1%80%D0%B0%D0%B7%D1%80%D0%B5%D1%88%D0%B8%D1%82%D1%8C-%D0%BF%D0%BE%D1%81%D1%82%D0%B8%D0%BD%D0%B3-%D0%B2-%D0%BC%D0%BE%D0%B9-%D0%BA%D0%B0%D0%BD%D0%B0%D0%BB-%D0%B4%D0%BB%D1%8F-%D0%BD%D0%BE%D0%B2%D0%BE%D0%B3%D0%BE-%D0%B0%D0%B4%D1%80%D0%B5%D1%81%D0%B0-email-%D1%83%D1%82%D1%80%D0%BE%D0%BC-%D1%8F-%D0%BD%D0%B0%D0%B6%D0%B0%D0%BB-%D0%BA%D0%BD%D0%BE%D0%BF%D0%BA%D1%83-%D1%87%D1%82%D0%BE%D0%B1%D1%8B-%D1%80%D0%B0%D0%B7%D1%80%D0%B5%D1%88%D0%B8%D1%82%D1%8C-%D0%BF%D0%BE%D1%81%D1%82%D0%B8%D0%BD%D0%B3-%D0%B8-%D1%83%D0%B2%D0%B8%D0%B4%D0%B5%D0%BB-%D1%81%D0%BE%D0%BE%D0%B1%D1%89%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BE%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%D0%BD%D0%BE-%D1%80%D0%B0%D0%BD%D0%B5%D0%B5-%D1%87%D1%82%D0%BE-%D0%BF%D1%80%D0%BE%D0%B8%D0%B7%D0%BE%D1%88%D0%BB%D0%BE)

## Насколько надежный хостинг у бота? Насколько велик шанс, что бот перестанет работать в самый ответственный момент?

Бот реализован на платформе Google App Engine Standard Environment и использует в качестве хостнига
[датацентр Google в городе Council Bluffs](https://www.google.com/about/datacenters/inside/locations/council-bluffs/), штат Айова, США.
Оборудование этого датацентра также обеспечивает работу штатных служб Google (Поиск, Почта, Карты и т.д.).

Так что шанс отказа бота по вине хостинга равен шансу прекращения работы служб Google в соответствующем регионе США. Большой или маленький это шанс, каждый пользователь бота может оценить самостоятельно.

## Вечером я забыл разрешить постинг в мой канал для нового адреса email. Утром я нажал кнопку, чтобы разрешить постинг, и увидел сообщение 'обработано ранее'. Что произошло?

Запрос на обработку входящей почты активен в течение одного часа.
Если вы не ответили на запрос в течение часа, то входящий емейл игнорируется.

Перейти в [@EmailGateBot](http://t.me/EmailGateBot?start=utm_KDaxQG000_github-ru-faq)
