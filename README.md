# Условие:
Вам предстоит создать приложение для управления списком задач с использованием Spring Boot 
и Spring Data JPA. Требуется реализовать следующие функции:

1. Добавление задачи.
2. Просмотр всех задач.
3. Просмотр задач по статусу (например, "завершена", "в процессе", "не начата").
4. Изменение статуса задачи.
5. Удаление задачи.

# Структура задачи:

- ID (автоинкрементное)
- Описание (не может быть пустым)
- Статус (одно из значений: "не начата", "в процессе", "завершена")
- Дата создания (автоматически устанавливается при создании задачи)

# Решение
Взаимодействие построено через вебинтерфейс.
На главной странице можно добавить *задачу* заполнив *форму*.
При создании новой *задачи*, ей автоматически присваивается номер, статус и дата создания.
Для изменения *задачи* необходимо перейти в отфильтрованный список через *поиск по статусу*
В отфильтрованном списке можно изменить или удалить задачу.
Во вкладке *изменить задачу* можно задать новые значения для:
- Название
- Задача
- Статус

