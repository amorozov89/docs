# Каналы

Общение в Rocket.Chat происходит в **каналах**. Каналы - это чаты с полезными функциями, которые помогают улучшить общение и совместную работу.

Есть три вида каналов: [открытые каналы](channels.md#public-channels), [закрытые каналы](channels.md#private-groups), и [личные сообщения (1 на 1)](channels.md#direct-messages).

## Открытые каналы

**Открытые каналы** \(коротко - **каналы**\) выступают основой для всех типов каналов. Используйте каналы для общения со всей вашей командой. Любой член вашей команды может присоединиться к каналу.

С помощью каналов легко понять что происходит в команде. Новые люди могут присоединиться к каналу и прочитать все сообщения, ранее написанные другими пользователями.

Когда сомневаешься, создай канал. Публичные беседы помогут вам с минимальными усилиями создать базу знаний вашей организации. Например, создать канал для отдела компании или для обсуждения конкретного языка программирования.

## Закрытые каналы

**Закрытые каналы** видны только их членам. Используйте частные группы для тем, которые являются чувствительными, конфиденциальными или ограничиваются небольшим кругом людей.

К закрытым каналам присоединяются только по приглашению. Администратор устанавливает права, определяющие, кто может приглашать других в закрытый канал. По умолчанию, только администраторы, владельцы комнат и модераторы могут приглашать других в приватные комнаты.

## Личные сообщения

**Личные сообщения \(ЛС\)** это личная переписка один на один между членами команды. Они могут быть отправлены любому пользователю на вашем сервере.

**Личные сообщения между несколькими пользователями** Существует функция, которая позволяет вам общаться с несколькими пользователями в ЛС. Для получения дополнительной информации, смотрите [Личные сообщения между несколькими пользователями](direct-messages-between-multiple-users.md).

## Перечень каналов

Вы можете найти открытые и закрытые каналы за которыми вы наблюдаете в левом боковом меню в разделе **Каналы**.

Открытые каналы отмечены знаком решетки(хэштегом) перед названием канала, закрытые каналы помечены замочком.

### Непрочитанные сообщения (блок документации отличается от последней версии поведения чата)

Каналы с новыми сообщениями выделены жирным шрифтом.

Вы можете настроить перечень каналов таким образом, чтобы каналы с непрочитанными сообщениями оказывались в верху перечня. Для этого, в верхней части левого бокового меню нажмите на иконку сортировки (стрелка вниз четверная иконка слева) и поставьте галочку на опции **Непрочитанное наверх**.

### Упоминания  (блок документации отличается от последней версии поведения чата, меняется цвет уведомления если личный то красное, если all или here то желтая)

Когда кто то упоминает вас с помощью `@username`, `@all` или `@here`, рядом с именем канала появится номер, который показывает количество раз когда вас упоминали. Когда вас упоминают по имени, с помощью `@username`,  номер будет красного цвета. Когда вас упоминают с помощью `@all` или `@here` номер будет желтого цвета.

### Notifications Preferences

There are several notification settings a user can customize to channels. To find notification settings for a specific channel, go to the channel and click the **More** symbol at the top-right of the chat view. Then, select **Notification Preferences**.

* **Mute/Receive alerts:** Receive or mute any notifications from a channel.
* **Mute/Receive mentions:** Receive or mute notifications for mentions while receiving notifications for messages in a channel.
* **Hide/Show counter:** Show the number of unread messages for a channel.
* **Notification sound:** Choose a sound for notifications besides the alerts default **Desktop**.  Mobile currently supports only the alerts inside your mobile device. You can also select when to play the alert, duration of the alert, and the alert itself.

> There are some default choices for audio provided by Rocket.Chat. However, you also get to choose custom audio files for the same. Get further information about [Custom Sounds](../administrator-guides/custom-sounds.md).

## Joining new channels and starting direct messages

There are three ways of joining a public channel; through search, invites, or mentions.

For starting a direct message, you can either search the user you want to talk or click on that user's avatar and click on the **Conversation Button**.

To search for channels and users, use the search bar under your account box. Alternatively you can press Ctrl/Cmd + k to access the search bar quickly.

A search will find channels \(including the ones you are part of\) and users. You can not search inside private channels.

When you click on a search result, the following can happen:

* If the result is a channel, and you already aren't part of it, you will join that channel;
* If the result is a user, you will start a direct message with that user;

## Leaving channels

There are two options for leaving a channel:

1. **Hide:** Remain a member of the channel but remove it from your list of channels on the left-hand pane.
2. **Leave:** Remove the channel your list of channels and abdicate membership.

Every channel has an **owner**, and the owner of a channel cannot leave a channel until setting someone else as the owner of that channel.

To leave a channel, enter the command `/part` or `/leave` in the message window. Alternatively, hover your mouse over the channel in the list of channels on the left-hand side and click on the **leave channel** button.

To hide a channel, hover your mouse over the channel in the list of channels on the left-hand side and click on the **hide channel** button.

## Creating Channels

To create a channel, you need to click on the plus `+` button that is alongside the channel search bar.

A pop-up opens. You can set the name of that channel, choose if the channel is public or private, set the channel to read-only, broadcast the channel, and invite users.

In read-only channels, messages can only be sent by users with write permissions. All users can react to messages in this channel. Read-only channels are most suitable for announcements and voting.

Encrypted channels, messages will be end to end encrypted. See: [End to End Encryption](end-to-end-encryption.md) for details.

Broadcasted channels behave like read-only channels, with only users with the right permission being able to post there. The differences to a read-only channel are:

* Users without permission \(the same one to post on read-only channels\) inside this channel won't be able to see each other in the user list.
* Users without permission won't be able to react to messages.
* Every message contains a reply button that redirects the user to a direct message with the user that posted the message.
* This channel cannot be converted to a read-only or open channel again.

