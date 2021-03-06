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

### Настройки уведомлений

Есть несколько настроек уведомлений, которые вы можете применить к каналам. Чтобы найти настройки уведомлений для определенного канала, перейдя в канал нажмите на иконку **Показать больше**(в виде трех точек) в правом верхнем углу экрана, затем выберите **Настройки уведомлений**.

* **Выключить/Включить:** Позволяет настроить, получать ли уведомления от этого канала или нет.
* **Получать упоминания @all и @here/Отключить звук для упоминаний @all и @here:** Позволяет настроить получение уведомлений по упоминанями `@username`, `@all` или `@here` в этом канале.
* **Скрыть счетчик/Показывать счетчик:** Показывать или скрывать количество непрочитанных сообщений.
* **Звук уведомлений:** Вы можете настроить звук уведомлений для **компьютера**. Для **мобильных устройств** и **электронной почты** в настоящий момент предоставляются только урезанные настройки.

> There are some default choices for audio provided by Rocket.Chat. However, you also get to choose custom audio files for the same. Get further information about [Custom Sounds](../administrator-guides/custom-sounds.md).
> Rocket.Chat по умолчанию предоставляет звуки для уведомлений. Однако вы также можете выбрать другие аудиофайлы для этой цели. Дополнительная информация о [Пользовательские звуки] (../ administrator-guides / custom-sounds.md).

## Присоединение к новым каналам и начало общения в личных сообщениях

Существует три способа подключения к открытому каналу: через поиск, приглашение или упоминание.

Для личного сообщения вы можете либо найти пользователя, с которым хотите поговорить, через поиск либо нажав на аватару этого пользователя и нажать на кнопку **Direct Message**.

Для поиска каналов и пользователей нажмите на иконку лупы в верхнем левом углу экрана. Или вы можете нажать Ctrl / Cmd + k, чтобы быстро получить доступ к строке поиска.

Поиск найдет каналы \ (включая те, в которых вы состоите \) и пользователей. Вы не можете искать внутри закрытых каналов.

При нажатии на результат поиска может произойти следующее:

* Если результатом является канал, в котором вы не состоите, вы присоединитесь к этому каналу;
* Если результатом является пользователь, вы начнете личную переписку с этим пользователем;

## Выход из каналов

Есть два варианта выхода из канала:

1. **Скрыть:** Вы останетесь участником канала, но удалите его из перечня каналов на левой панели.
2. **Покинуть комнату:** Вы удалите канал из перечня каналов и выйдите из канала.

У каждого канала есть **владелец**, и владелец канала не может покинуть канал, пока не назначит другого владельца этого канала.

Чтобы покинуть канал, введите команду «/ part» или «/ leave» в окне сообщения. Или наведите указатель мыши на канал в списке каналов в левой части экрана и нажмите кнопку **показать больше**(три точки) далее нажмите **Покинуть комнату**.

Чтобы скрыть канал, в списке каналов, в левой части экрана, выберите канал и нажмите на кнопку **показать больше**(три точки) далее нажмите **Скрыть**.

## Создание каналов

Чтобы создать канал, вам нужно нажать на иконку с карандашом рядом с иконкой поиска каналов.

Откроется всплывающее окно. В нем вы можете выбрать имя нового канала, выбрать, является ли канал открытым или закрытым, установить канал только для чтения, или сделать широковещательный канал, а так же пригласить пользователей.

В каналах только для чтения сообщения могут отправляться только пользователями с правами на отправку сообщений. Все остальные пользователи могут реагировать на сообщения в этом канале. Каналы только для чтения наиболее подходят для объявлений и голосования.

Опция зашифрованный канал. В зашифрованных каналах, сообщения будут зашифрованы сквозных шифрованием. См .: [Сквозное шифрование] (end-to-end-encryption.md) для дополнительной информации. (нет опции)

Широковещательные каналы ведут себя как **каналы только для чтения**, и только пользователи с соответствующими правами могут публиковать сообщения. Отличия от канала только для чтения:

* Пользователи без прав \(те же права, что и на каналы только для чтения \) внутри этого канала не смогут видеть друг друга в списке пользователей.
* Пользователи без прав не смогут реагировать на сообщения.
* Каждое сообщение содержит кнопку ответа, которая перенаправляет пользователя в личную переписку с пользователем, отправившим сообщение.
* Этот канал нельзя снова преобразовать в канал только для чтения или в открытый.
