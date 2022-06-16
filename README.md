# TVassal
## Описание
TVassal призван, чтобы упростить жизнь IT-специалистам в тех ситуациях, когда им необходимо регулярно тестировать новый функционал Web-сервисов с помощью отправки соответствующих HTTP-запросов в ручном или автоматическом режимах. 

Философия Вассала проста: Импорт API -> Сборка тестовых сценариев на базе импортированного API -> Выполнение Тест-плана(ов) на базе собранных тестовых сценариев.

А все остальное служит лишь для того, чтобы этот процесс был максимально простым и быстрым.
Например,
1. автоматическая работа с системами аутентификации-авторизации - задаем профиль аутентификации и при отправке запроса автоматически будет сделано все, чтобы провести запрос через процедуры аутентификации и авторизации.
2. сборка сценария из вызовов API-методов с заданными параметрами
3. вызов других сценариев для максимального переиспользования

## Релиз
Смотри раздел [releases](https://github.com/DenisTerentyev/TVassal/releases)

## Рекомендованный пайплайн работы с TVassal
1. Импортировать API сервиса в соответствующую директорию через меню импорта API (Панель -> Подсистемы -> Импорт API)
2. Перейти в раздел "Тестирование" и в соответствующей директории собрать необходимые сценарии тестирования
3. Перейти в раздел "Тест-планы" и собрать новый тест-план, выбрав все необходимые сценарии тестирования.
4. Задать настройки выполнения тест-плана и выполнить его. ~~Радоваться, видя как не проходят тесты~~ Получить отчет о выполнении.

## Контакты
Для обращений можно писать на почту - tvassal@yandex.ru
