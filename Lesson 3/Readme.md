# Разработка сетевого приложения на C#

## Урок 1. Работа с сетью: чтение и запись данных в сеть. Клиентские и серверные приложения

### Задание

Попробуйте переработать приложение, добавив подтверждение об отправке сообщений как в сервер, так и в клиент.

### Решение

Решение размещено в папках Task1 и Task1Client. Task1Client запускается из командной строки с использованием 2 аргументов: строка "отправитель", строка "получатель".

## Урок 2. Синхронизации: многопоточность, создание и завершение потоков

### Задание

Добавьте возможность ввести слово Exit в чате клиента, чтобы можно было завершить его работу. В коде сервера добавьте ожидание нажатия клавиши, чтобы также прекратить его работу.

### Решение

Решение запускается аналогично заданию №1.

## Урок 3. PLINQ и асинхронность: как работает, области применения

### Задание

Добавьте использование Cancellationtoken в код сервера, чтобы можно было правильно останавливать работу сервера.

### Решение

В код сервера добавлены ```CancellationTokenSource``` и ```CancellationToken``` для остановки сервера.

## Урок 4. GOF: паттерны проектирования в .Net разработке

### Задание 

Структурируйте код клиента и сервера чата, используя знания о шаблонах.

### Решение

Код клиента и чата был написан с учетом знаний о шаблонах.

