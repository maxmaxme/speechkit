# Бот для перевода голосовых сообщений в текст
- https://vk.com/speechkit
- https://www.the-village.ru/business/news/252947-bot-dlya-vkontakte-raspoznayuschiy-golosovuyu-rech
- https://tjournal.ru/flood/38764-razrabotchik-sozdal-bota-dlya-vkontakte-raspoznayushchego-golosovuyu-rech

Бот, который переводит присланные ему голосовые сообщения в текстовые.<br>
Работает на VK Api и Yandex Speech Kit Cloud API.

В скрипте присутствуют следующие ключи доступа:<br>
— $api_key — access–токен от Яндекса. Получать тут: https://developer.tech.yandex.ru/<br>
— $vkToken — access–токен от группы ВК с правами на сообщения. Получать тут: https://vk.com/speechkit?act=tokens<br>
— $vkConfirmationKey — Confirmation–ключ от VK для настройки Callback API. Получать тут: https://vk.com/speechkit?act=api<br>

На следующей странице (https://vk.com/speechkit?act=api) необходимо прописать URL до вашего скрипта и в типах событий поставить "Входящие сообщения".
