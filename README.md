# ToDo

## Описание

ToDo — это приложение для создания списков задач.

## Функции

* Добавить новую задачу 
* Удаление всего списка задач или одной задачи
* Просмотр списка добавленных задач
* Изменить статус задачи, нажав на ее название
* Фильтрация по статусу задачи.
* Просмотр счетчика выполненных и незавершенных задач

## Минимальные требования

_Убедитесь, что у вас установлен Node.js версии 20.1 или выше_

## Начинаем

### Склонируйте репозиторий

```bash
git clone git@github.com:ByteSpectre/ToDo.git
```

### Установите зависимости

```bash
make install
```

### Забилдите

```bash
make run-build
```

### Запустите программу

```bash
make start
```

### Проверка линтера

```bash
make lint
```

## Docker

_Make sure you have Docker installed and running_

### Создайте контейнер

```bash
sudo docker build -t "[IMAGE NAME]"
```

### Запустите контейнер

```bash
sudo docker run -d --rm -p 3000:3000 [IMAGE NAME]
```