Для запуска нужно перейти в папку ./config/bot_data.py выставить токен бота, id - админа и id каналов

Все основные настройки хранятся в ./config/settings_res.py - туда вписаны все настройки бота, включая его экономику

Текста расположены в файле ./config/bot_text.py

Текста событий/отзывов расположены в файлах:
- ./events_text - текста отзывов
- ./text_for_review - текста событий

Все события происходят индивидуально для каждого пользователя в зависимости от характеристик ресторана






- Создание событий: Админ может создавать разные события который будут влиять на характеристики ежедневного отчета
- Рассылка
- Добавление заданий
- Реферальная система
- Ежедневный отчет где будет указываться какие события ресторана прошли за 24 часа (отчет можно вызывать самостоятельно при команде /call_task)