# Действия внутри канала

Внутри каналов вы можете делать больше, чем просто отправлять сообщения и загружать файлы. Увеличьте ваше взаимодействие с сообщениями с помощью действий для канала.

## Расположение действий для канала

Кнопки действий для канала расположены в верхней правой части экрана, когда вы находитесь внутри канала.

_Действия канала различаются в зависимости от конфигурации сервера, поэтому не все элементы, перечисленные ниже, могут быть видны в вашем случае._

## Избранное

Чтобы лучше организовать и приоритизировать ваше общение, вы можете добавить в **избранное** \(или пометить **звездочкой**\) открытые каналы, закрытые каналы и личные сообщения.

Чтобы добавить канал в изобранное, нажмите на **звездочку** слева от заголовка(названия) канала.

Добавление в избранное, переводит канал в секцию **Избранное** в перечне каналов, поэтому его становится проще найти.

## Информация о чате

Здесь вы можете увидеть всевозможную информацию о текущем канале. Если у вас есть права администратора, вы можете редактировать эту информацию. Информация о канале включает в себя:

* **Имя канала**: название канала, так пользователи видят заголовок и находят канал в поиске.
* **Тема**: тема отображается под названием канала в заголовке. Отлично подходит для предоставления дополнительной информации о канале.
* **Объявление**: объявления размещаются в строке под заголовком канала в верхней части экрана.
* **Описание**: описание канала.
* **Закрытый**: показывает, является ли канал закрытым, можно сделать канал закрытым или открытым.
* **Только для чтения**: показывает, доступен ли канал только для чтения, и позволяет сделать канал только для чтения. В каналах только для чтения публиковать сообщения могут только люди с правами администратора. Подходит для каналов объявлений.
* **Архивный**: показывает, находится ли канал в архиве, и позволяет заархивировать канал. Никто не может публиковать сообщения в архивном канале, заархивированный канал не отображается в поиске.
* **Пароль**: показывает, есть ли у канала пароль, и позволяет вам установить пароль. Если канал имеет пароль, другим пользователям необходимо ввести пароль, чтобы стать участниками канала.

Если вы не хотите чтобы в чате были видны системные сообщения(сообщения типа: @пользователь присоединился к каналу) вы можете настроить их отображение опцией **Скрыть Системные Сообщения** 

## Поиск сообщений

Поиск Rocket.Chat поддерживает основные поисковые команды, которые работают как поиск в Gmail.

Rocket.Chat так же поддерживает использование "[регулярных выражений](https://ru.wikipedia.org/wiki/Регулярные_выражения)." Регулярные выражения обеспечивают гибкость и возможность поиска сообщений в чате на любом языке, даже на тех, на которых поиск традиционно являются проблемой, например, азиатские языки \ (китайский, японский, корейский \).

### Основные поисковые команды

Вы можете использовать эти команды до или после ввода условий поиска.:

* `from:me` поиск сообщений отправленных текущим пользователем.
* `from:user.name` поиск сообщений отправленных определенным пользователем. Имя пользователя должно быть указано без пробелов. \(например, "ivan.ivanov", а не "Ivan Ivanov."\) Найдите любые упоминания пользователя, выполнив поиск по его имени.
* `has:star` возвращает сообщения, добавленные в избранное текущим пользователем.
* `is:pinned` или `has:pin` возвращает сообщения, которые закреплены в текущем канале.
* `has:url` или `has:link` возвращает сообщения, содержащие ссылку.
* `has:location` или `has:map` возвращает сообщения с прикрепленным местоположением.
* `before:dd/mm/yyyy`, `after:dd/mm/yyyy` и `on:dd/mm/yyyy` возвращает сообщения, созданные до, после или в указанную дату.

  Тире `dd-mm-yyyy` или точки `dd.mm.yyyy` можно использовать вместо косой черты(слэша). `order:asc`, `order:ascend`, и `order:ascending` сортирует сообщения по возрастанию по признаку время.

* `order:desc`, `order:descend`, или `order:descending` сортирует сообщения по убыванию по признаку время.

  Вы также можете перейти туда, где находится сообщение, наведя указатель мыши на результат поиска, нажать на кнопку **Больше**(три точки) и нажать `Перейти к сообщению`.

### Регулярные выражения

Пройдя по этим ссылкам вы можете больше узнать о **Регулярных выражениях**:

* Wikipedia - [https://en.wikipedia.org/wiki/Regular\_expression](https://en.wikipedia.org/wiki/Regular_expression)
* Regex 101 - [https://regex101.com/\#javascript](https://regex101.com/#javascript)
* Regexr - [http://regexr.com/](http://regexr.com/)
* Regex Info - [http://www.regular-expressions.info/javascriptexample.html](http://www.regular-expressions.info/javascriptexample.html)

## Список участников

Здесь вы можете увидеть всех пользователей на канале и просмотреть информацию о них. Если у вас есть соответствующие права, вы можете управлять ими на своем канале.

Сначала, в списке показываются только активные в данный момент пользователи. Чтобы увидеть всех пользователей, выберите опцию **Все пользователи** вместо **Онлайн**.

Чтобы просмотреть дополнительную информацию о пользователе, нажмите на его имя в списке.

На экране предварительного просмотра пользователя отображаются его имя, логин, роли которые у него есть, и текущий часовой пояс. Оттуда вы можете:

* Начать личную переписку с пользователем, нажав на кнопку **Direct Message**
* Начать видеозвонок с пользователем
* Установить пользователя как владельца канала
* Установить пользователя модератором канала
* Заглушить пользователя
* Удалить пользователя с канала

## Уведомления

Вы можете изменить поведение уведомлений для каналов, участником которых вы являетесь. По умолчанию канал уведомляет вас, когда кто-то упоминает вас или использует упоминание `@ all`.

Следующие параметры находятся на вкладке уведомлений канала:

* **Выключить уведомления**: Отключить все уведомления для канала.
* **Аудио**: Выберите, будет ли канал издавать звук, когда кто-то упоминает вас или публикует сообщение на этом канале. Воспроизводимый звук можно настроить.
* **Компьютер**: Управляет поведением уведомлений при использовании любого настольного приложения или браузера.
* **Мобильные устройства**: Управляет поведением push-уведомлений при использовании любого мобильного приложения.
* **Электронная почта**: Устанавливает, будет ли отправляться электронное письмо всякий раз, когда кто-то упоминает вас или публикует сообщение.

Параметры уведомлений в настройках профиля, в разделе **Сообщения**.
* **Иконка уведомлений о непрочитанных сообщениях в трее**: Управляет выделением значка в трее при появлении новых сообщений или упоминаний.

## Message list options

This section details a list of all different types of lists specific to channels:

* **Files List**: A list of all the files uploaded to the current channel.
* **Mentions**: All messages that mentioned you on the current channel.
* **Starred Messages**: All messages that you have starred in the current channel.
* **Pinned Messages**: All messages pinned to the current channel.

## Streaming

If the feature [Youtube Livestream](../administrator-guides/youtube-broadcasting.md) is enabled, the **Streaming** Tab activates on the channel actions menu.

Through the **Streaming** tab, owners of the channel of server admins can start streaming or add another stream to the channel using a URL.

### Start a stream

_Note: Depending on the settings of the server, you might be only able to link live streams from Youtube. In doubt always ask your server's admin._

1. Press the **Broadcast my Camera** button.
2. Login with a Google account. Remember that streaming must be activated through your Youtube account. For more information, see [Introduction to live streaming](https://support.google.com/youtube/answer/2474026?hl=en) Google guide\).

To add a different Livestream, get the URL \(must be from Youtube\) for the stream, enter it into the **Livestream source** field and hit save.

You can also add a message for whenever the stream is unavailable in the **Livestream not available message** field.

To add a stream with no video and only audio, use the **Enable audio only button**.

### \(Users\) Start a Live Stream

If you are not a channel owner and there is already a live stream set to that channel, press **play** on the stream tab. This starts a pop-up with the stream embedded. The pop-up does not close even if you change channels.

## Prune Messages

If you are a server admin, or your admin has given you the **clean-channel-history** permission, the **prune messages** option allows you to delete messages from a channel swiftly.

_Note: Messages and files deleted with this option are deleted forever and cannot be recovered. Be careful and double-check your arguments before pressing Prune._

Use the following parameters to delete specific messages:

* `Newer than`: Deletes all messages posted **after** a particular date.
* `Older than`: Deletes all messages posted **before** a particular date.

Fill dates for both the `Newer than` and `Older than` fields to delete all messages.

* `Users`: Allows you to specify any users to delete the content. When filled with a username, that user's messages deleted.

Refine the parameters above with the following options. Check each to enable:

* **Inclusive**: Deletes all messages that land on the exact start/end times you have specified in the `Newer than` and `Older than` fields.
* **Exclude pinned messages**: Do **not** delete pinned messages.
* **Only remove the attached files, keep messages**: Removes files but not the messages themselves

