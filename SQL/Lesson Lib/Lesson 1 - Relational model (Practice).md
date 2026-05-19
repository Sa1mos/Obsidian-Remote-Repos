## Проделанная работа вне домашней работы

- Установлен и первично настроен Git (Указан user.name, user.email(взят безопасный noreply с GitHub))
- Установлен Obsidian и настроена синхронизация с Git (Создан репозиторий, создан access token (classic), плагин Git в обсидиан связан с репозиторием в GitHub)
## Домашняя работа

[Ссылка на ДЗ к занятию 1](https://greg-mentor.yonote.ru/share/2caca3e6-384f-4257-abf7-41b66d72a13e)

[Исправленная схема БД](https://dbdiagram.io/d/Marketplace-Database-6a0b4a479f1f8ec47b444d35)
- Были добавлены новые связи в `orders` и `customers`
	  - таблица `orders` зависела от строки `status`, поэтому была добавлен справочник `status_lib`, хранящая виды статусов заказа, и `orders` теперь связан с ней с помощью внешнего ключа
	  - `customers` зависела от строки `city` - был добавлен справочник городов `city_lib` и внешний ключ к нему из таблицы `customers`
- Добавлена новая проверка в `order_items`
	  - добавлен `check unit_ptice > 0` 

[Задача leetcode "Combine Two Tables"](https://leetcode.com/problems/combine-two-tables/description/)

[Задача leetcode "Employee Earning more than Their Manager"](https://leetcode.com/problems/employees-earning-more-than-their-managers/description/)

### Уточнить на занятии

- Объяснение задачи "Employee Earning more than Their Manager"