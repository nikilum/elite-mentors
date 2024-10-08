# Функционал, доступный элитным менторам
Описанный ниже функционал доступен только тем людям, которые состоят в группе "ОМ: Элитные Менторы" в Telegram. Как только вы выходите из этого чата, весь функционал перестаёт работать

## Глобальная статистика по боту
Глобальная статистика по боту позволяет вам увидеть, какие запросы на поиск ментора делают пользователи бота, сколько суммарно запросов и кликов по отзывам было сделано. Также в глобальной статистике есть записи о том, по чьим отзывам кликали пользователи.
Чтобы получить глобальную статистику, зайдите в бота [найти ментора.](https://t.me/find_it_mentor_bot).
1. Запустите бота с помощью команды /start
2. Откройте "Меню элитного ментора"

    ![image](https://github.com/user-attachments/assets/f48c9c9b-f07f-4c8c-a2ed-96c6968b7549)

3. Нажмите на кнопку "Посмотреть глобальную статистику по боту"

Также получить глобальную статистику по боту можно написав /statistics в чате "ОМ: Элитные Менторы"

![image](https://github.com/user-attachments/assets/9603fa75-6f80-4e82-8a47-17324bf4b473)

## Личная аналитика
В личной аналитике можно посмотреть вашу статистику в таблице менторов. Например, там есть информация о том, сколько раз кликали по ссылкам на вас в графах "отзывы", "контакт", "описание", "цена" таблицы.
Чтобы получить личную аналитику, зайдите в бота [найти ментора.](https://t.me/find_it_mentor_bot).
1. Запустите бота с помощью команды /start
2. Откройте "Меню элитного ментора"

    ![image](https://github.com/user-attachments/assets/f48c9c9b-f07f-4c8c-a2ed-96c6968b7549)

3. Нажмите на кнопку "Посмотреть аналитику"

## Получить свой Telegram-ID
Получить свой Telegram-ID можно в боте [найти ментора.](https://t.me/find_it_mentor_bot). Для этого надо произвести следующие действия:
1. Запустите бота с помощью команды /start
2. Откройте "Меню элитного ментора"

    ![image](https://github.com/user-attachments/assets/f48c9c9b-f07f-4c8c-a2ed-96c6968b7549)

3. Нажмите на кнопку "Получить свой id"

    ![image](https://github.com/user-attachments/assets/df227a85-208b-436e-8870-5699f7615c77)

Также получить свой id можно с помощью команды /id в чате "ОМ: Элитные менторы"

![image](https://github.com/user-attachments/assets/f224b8e8-5773-495d-93c5-1f8374ad1349)

## Встраиваемые отзывы
Если вы элитный ментор, то у вас есть возможность встроить свои отзывы из группы [IT менторы](https://t.me/it_mentors) в ваш прайс-лист. Для этого вам необходимо сделать следующие действия:
1. Получить свой Telegram-ID с помощью бота. О том, как это сделать, написано выше.
2. Выбрать тему, которая будет использоваться в ваших отзывах. Доступные темы: `notion-light`, `notion-dark`, `teletype-light`, `teletype-dark`
3. Вставить свой Telegram-ID вместо текста **"YOUR_TELEGRAM_ID_HERE"**, а также название темы вместо текста **YOUR_REVIEWS_THEME_HERE** в данную ссылку:
   `https://reviews.it-mentors.ru/reviews?id=YOUR_TELEGRAM_ID_HERE&theme=YOUR_REVIEWS_THEME_HERE`

### Если вы используете Notion
4. Зайдите на необходимую вам страницу и начните писать /embed. Вам покажется подсказка, выберите там вариант "Embed"

    ![image](https://github.com/user-attachments/assets/33b3f023-39f4-4799-abed-ac899b83322a)

5. Вставьте ссылку, которую вы сделали в поле для ввода и нажмите на кнопку "Embed Link"

     ![image](https://github.com/user-attachments/assets/53d0f467-d029-4077-8c50-830f0fc591b4)

6. После недолгой загрузки, ваши отзывы будут показаны на странице:

     ![image](https://github.com/user-attachments/assets/8b23f3fc-ad77-4527-98e8-e33fb6cbf861)

### Если вы используете Teletype

4. Зайдите на необходимую вам страницу и начните писать /iframe. Вам покажется подсказка, выберите там вариант "Iframe"

   ![image](https://github.com/user-attachments/assets/69422afc-6107-469c-924d-3530c7f7519d)

5. Вставьте свою ссылку вместо текста **YOUR_LINK_HERE** в данный код `<iframe src="YOUR_LINK_HERE">`.
6. Вставьте код в поле Iframe

    ![image](https://github.com/user-attachments/assets/be73bafa-c2e6-48fd-8bd1-ee507fb13e14)

7. Нажмите Enter, и отзывы появятся.

    ![image](https://github.com/user-attachments/assets/cd11761e-b8d2-4a2b-ae11-bdd55f1c70e1)


## Получение отзывов в формате JSON
Если вам необходимо встроить отзывы в ваш сайт, или вы хотите кастомизировать их внешний вид, то вы можете воспользоваться получением отзывов с помощью JSON. Для этого вам необходимо сделать следующее:
1. Получить свой Telegram-ID с помощью бота. О том, как это сделать, написано выше.
3. Вставить свой Telegram-ID вместо текста **"YOUR_TELEGRAM_ID_HERE"**, в данную ссылку:
   `https://reviews.it-mentors.ru/reviews-json?id=YOUR_TELEGRAM_ID_HERE`
4. При переходе по данной ссылке вам будет возвращаться JSON с 10 отзывами. Если вы хотите переключиться на страницу вперёд/назад, то вам достаточно перейти по ссылке, которая приходит в поле "next"/"prev" JSON-файла.

    ![image](https://github.com/user-attachments/assets/2c2488d9-bee5-48fb-a101-653ac289ddc1)

6. Если "prev" или "next" нет, значит предыдущей или следующей страницы не существует.
