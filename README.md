[![ImbaChat](http://imbachat.com/themes/imbachat/assets/img/logo.svg "ImbaChat")](http://imbachat.com "ImbaChat")

# Виджет чата для October CMS

Это бесплатный плагин для интеграции October CMS с сервисом чатов imbachat.com 
Позволяет бесплатно добавить виджет чата между пользователями вашего сайта. 

# Ссылки

[Демо сайт](http://octobercms.imbachat.com/user)

[Плагин для October cms](https://github.com/imbasynergy/ImbaChat-OctoberCMS)

[Исходный код демо сайта](https://github.com/imbasynergy/ImbaChat-OctoberCMS-demo)

[Техническая поддержка](http://imbachat.com/help)

# Особенности

* Полная интеграция с базой пользователей вашего сайта
* Единый механизм авторизации в чате и на сайте
* Переписка между пользователями 1 на 1
* Отправка картинок
* Отправка геопозиции
* Отправка смайлов
* Real time доставка сообщений
* Не нагружает ваш сервер (Виджет чата использует сервера проекта imbachat.com  )
* Можно использовать на shared хостинге
* Продолжает корректную работу даже без интернета (сообщения отправятся сразу после того как появится интернет)

[![Chat demo](http://imbachat.com/storage/app/uploads/public/docs/demo.gif "Chat demo")](https://imbachat.com "Chat demo")


## Шаги для установки виджета чата:

- Установите на свой сайт этот плагин
- Зарегистирируйтесь на сайте [imbachat.com](https://imbachat.com)
- Зайдите на [страницу с виджетами](https://imbachat.com/admin/widgets). и создайте себе виджет
- В процессе создания виджета надо будет выбрать "Интеграция с October CMS" и следовать инструкциям

### Вставка компонента чата на страницу
- Подключите `[imbaChat]` компонент в файле страницы.
- `[imbaChat]` компонент вставляет javascript, который инициализиует виджет чата

```{% component 'ImbaChat'  %}```
