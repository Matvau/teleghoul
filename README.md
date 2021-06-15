# Я - Гуль (бот), теперь работает в чатах

![Работа бота](https://github.com/error1001es/teleghoul/blob/main/screenshots/bot_work.png)

**Отблагодарить автора за проделанную работу можно [здесь](#пожертвовать)**<br>
**Помощь с установкой [тут](#помощь)**

___
## Установка на Андроид
**После установки перейдите в раздел [*Запуск*](#Запуск)**<br>

Скачиваем приложение [Termux](https://play.google.com/store/apps/details?id=com.termux) в Play Market<br>
Открываем и пишем команды снизу поочерёдно<br>

#### Для копирования команды нажмите справа от неё

*Обновляем*

	apt-get update
*Ставим git и python*

	apt-get install git python
Если спросит `Do you want to continue? [Y/n]` отвечаем `Y` и продолжаем<br>
*Устанавливаем pyrogram*

	pip install pyrogram
*Клонируем репозиторий*

	git clone https://github.com/error1001es/teleghoul.git
**После установки перейдите в раздел [*Запуск*](#Запуск)**<br>

___
## Установка на Пк
**После установки перейдите в раздел [*Запуск*](#Запуск)**<br>

Скачиваем [git](https://git-scm.com/downloads) и [python](https://www.python.org/downloads/)<br>
**При установке Python обязательно ставим галочку `Add to PATH`**<br>

*Устанавливаем pyrogram*

	pip install pyrogram
*Клонируем репозиторий*

	git clone https://github.com/error1001es/teleghoul.git
___
## Запуск
*Введите* и ждите пока бот запросит номер телефона, привязанный к **ВАШЕМУ** телеграму

	python teleghoul/index.py
	
В **ТЕЛЕГРАМ** придёт код, введите его и бот заработает

![Запуск](https://github.com/error1001es/teleghoul/blob/main/screenshots/startup.png)<br>

Если у вас стоит *двухфакторная аутентификация*, то бот запросит пароль<br>

**После запуска бот даст тебе знать, *последующие запуски выполняются без каких-либо установок***<br>

<pre>
    <kbd>Ctrl</kbd>+<kbd>С</kbd> - Отключение бота
</pre>
___
## Команды в Телеграме
`.ghoul-c` - табличка<br>
`.ghoul-spam` - спам<br>
`.ghoul` - редактирование одного сообщения<br>


*Одновременно запускать лучше только в один чат*<br>

***Пожалуйста, не тестируйте работу на мне***<br>

___


## Пожертвовать
Сбер: 5469450014457196<br>
Тинькофф: 5536913879572820<br>
[Мой Киви](https://donate.qiwi.com/payin/4sadly)<br>
[Сервис донатов](https://donate.stream/4sadly)

___
## Помощь
При возникновении ошибок проверьте правильность написания/копирования команд<br>
Попробуйте еще раз и только потом пишите мне в [**ЛС**](https://t.me/ghoul4s) вместе со скриншотом!

___
## Обновление бота
*Заходим в папочку с ботом*

	cd teleghoul
	
*Обновляем*	

	git pull
	
*Выходим из папки, для удобного последующего запуска*

	cd ../

___
## Дополнительные возможности
Вы можете открыть файл *config.py* в файловом менеджере или командой `nano teleghoul/config.py`<br>
end_message - сообщение после конца цикла (для всех команд)<br>
messages_per_second - кол-во сообщений в секунду (для `.ghoul-spam`)<br>
sleep_time_ghoul - время между обновлениями (для `.ghoul-c`)

