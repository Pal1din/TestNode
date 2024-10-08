# Тестовое задание: Backend-разработчик (Nest.js, JavaScript)

## **Цель задания**

_Разработать RESTful API с использованием Nest.js, который будет управлять списком задач (todo list). API должно поддерживать основные операции CRUD (Create, Read, Update, Delete) и обеспечивать оптимальную производительность и читаемость кода._

## Описание задачи

Создать простое приложение для управления задачами (todo list) с использованием Nest.js. Приложение должно включать следующие функции:

1. Создание задачи: POST /tasks

   * Запрос должен содержать информацию о задаче (название, описание, статус).
   * Вернуть созданную задачу с уникальным идентификатором.

2. Получение списка всех задач: GET /tasks

   * Вернуть список всех задач.

3. Получение задачи по ID: GET /tasks/{id}

   * Вернуть задачу с указанным ID.

4. Обновление задачи: PUT /tasks/{id}

   * Обновить информацию о задаче по ID.
   * Вернуть обновлённую задачу.

5. Удаление задачи: DELETE /tasks/{id}

   * Удалить задачу по ID.
   * Вернуть статус операции.

## Требования к выполнению задания

* Использовать Nest.js и TypeScript.
* Организовать структуру приложения с использованием модулей, контроллеров и сервисов.
* Описать код с использованием JSDoc или аналогичного инструмента для документации.
* Обеспечить покрытие тестами с использованием Jest или AVA.js.
* Использовать Docker для контейнеризации приложения. Приложить Dockerfile и docker-compose.yml для сборки и запуска проекта.
* Предоставить краткое описание архитектуры приложения и решений, принятых в процессе разработки.

## Бонусные требования (необязательно, но приветствуется):

* Использование Kubernetes для оркестрации контейнеров.
* Оптимизация кода для повышения производительности.
* Добавление документации API с использованием Swagger или аналогичного инструмента.
* Использование Flow или других типов проверки типов в JavaScript.
* Включить логику для управления состоянием задач (например, установка статуса задачи на "выполнено").
* Оценка задания

## Будут оцениваться:

* Чистота и структура кода.
* Соответствие задания требованиям.
* Использование современных подходов и лучших практик в разработке на Nest.js и JavaScript.
* Наличие документации и тестов.
* Оптимизация и производительность кода.

## Как предоставить решение

_Решение должно быть загружено на GitHub или другой репозиторий и предоставлена ссылка на него. В репозитории должно быть README с инструкциями по сборке и запуску проекта._
