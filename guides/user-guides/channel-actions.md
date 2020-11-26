# Действия для канала

Внутри каналов вы можете делать больше, чем просто отправлять сообщения и загружать файлы. Увеличьте ваше взаимодействие с сообщениями с помощью действий для канала.

## Расположение действий для канала

Кнопки действий для канала расположены в верхней правой части экрана, когда вы находитесь внутри канала.

_Действия канала различаются в зависимости от конфигурации сервера, поэтому не все элементы, перечисленные ниже, могут быть видны в вашем случае._

## Избранное

Что бы лучше организовать и приоритизировать ваше общение, вы можете добавить в **избранное** \(или пометить **звездочкой**\) открытые каналы, закрытые каналы и личные сообщения.

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

If a [retention policy](../administrator-guides/retention-policies.md) is active on this channel, a red warning box appears saying when messages or files are deleted.

## Search Messages

Rocket.Chat search supports basic search commands which work like Gmail search.

Rocket.Chat also supports the use of "[regular expressions](https://en.wikipedia.org/wiki/Regular_expression)." Regular expressions provide flexibility and the ability to search chat entries in any language, even ones which are traditionally a challenge like "CJK" languages \(Chinese, Japanese, Korean\).

### Basic Search Commands

You can use these commands before or after entering search terms:

* `from:me` to search for messages only created by the current user.
* `from:user.name` to search for messages created by a specific user. The username entered must be the format without spaces \(i.e., "john.doe" and not "John Doe."\) Search for any mentions of a user by searching for their username.
* `has:star` returns messages that are starred by the current user.
* `is:pinned` or `has:pin` returns messages that pin in the current channel.
* `has:url` or `has:link` returns messages that contain a link.
* `has:location` or `has:map` returns messages that have a location attached.
* `before:dd/mm/yyyy`, `after:dd/mm/yyyy` and `on:dd/mm/yyyy` return message that were created before, after, or on the provided date.

  Dashes `dd-mm-yyyy` or dots `dd.mm.yyyy` can be used instead of slashes. `order:asc`, `order:ascend`, or `order:ascending` sorts messages by ascending timestamp.

* `order:desc`, `order:descend`, or `order:descending` sorts messages by descending timestamp.

  You can also jump to where a message is located by hovering the mouse over the search result and selecting `jump to message.`

### Regex

These references tell more about the powerful world of regex:

* Wikipedia - [https://en.wikipedia.org/wiki/Regular\_expression](https://en.wikipedia.org/wiki/Regular_expression)
* Regex 101 - [https://regex101.com/\#javascript](https://regex101.com/#javascript)
* Regexr - [http://regexr.com/](http://regexr.com/)
* Regex Info - [http://www.regular-expressions.info/javascriptexample.html](http://www.regular-expressions.info/javascriptexample.html)

## Members List

Here you can see all the users on the channel and see more information about them. If you have the proper permission, you can manage them on your channel.

At first, the list only shows currently active users. To see all users, click the **show all**.

To see more information on a user, click their name on the list.

The user preview screen shows their name, username, any role tags they might have, and their current timezone. From there, you can:

* Start a direct conversation with the user by clicking the `conversation` option
* Start a video call with the user
* Set the user as channel owner
* Set the user as a channel's moderator
* Mute the user
* Remove the user from the channel

## Notifications

You can change the behavior of notifications for channels where you are a member. By default, a channel notifies you whenever someone mentions you or uses the `@all` mention.

These options are on the channel notifications tab:

* **Disable Notifications**: Disable all notifications for the channel.
* **Audio**: Select whether the channel will emit a sound whenever someone mentions you or posts a message in that channel. The sound played can be customized.
* **Desktop**: Controls notification behavior when using any desktop app or browser.
* **Mobile**: Controls push notification behavior when using any mobile app.
* **Email**: Set whether an email sends whenever someone mentions you or posts a message, or disable email notifications.
* **Unread Room Status**: Control whether the channel on the channel list highlights when there is a new message or mention.
* **Unread Tray Icon**: Controls whether the tray icon highlights when there are new messages or mentions on the current channel.

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

