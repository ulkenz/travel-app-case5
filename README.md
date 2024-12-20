# Дневник путешествий case5

Проект представляет собой веб-приложение "Дневник путешествий", позволяющее пользователям записывать свои путешествия, просматривать путешествия других пользователей, а также добавлять подробную информацию о месте, изображениях, стоимости, культурных и природных объектах.

## Описание

### Функциональные возможности
1. Создание пользователя системы
2. Запись путешествия для пользователя
3. Просмотр путешествий других пользователей
4. Добавление 3 из следующих функций о путешествии:
    - Местоположение (с привязкой к геопозиции)
    - Изображение мест
    - Стоимость путешествия

## Стек технологий
- Next.js
- MongoDB
- NextAuth

## Установка

Для запуска проекта необходимо выполнить несколько простых шагов:

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/ulkenz/travel-app-case5.git
    ```
2. Установите зависимости

    ```bash
    npm install
    ```

3. Запустите проект

    ```bash
    npm run dev
    ```

После этого проект будет доступен по адресу [http://localhost:3000](http://localhost:3000).

---

## Пример использования

На главной странице пользователь может создать аккаунт или войти в систему с помощью NextAuth.
В профиле можно добавить новое путешествие, указав все необходимые данные:
- Геопозиция
- Изображения
- Стоимость
- Оценки и места для посещения

В разделе "Путешествия" можно просматривать добавленные другие пользователями путешествия.

---

## Скриншоты

- **Добавление путешествия**  
  ![Добавление путешествия](https://s3.radikal.cloud/2024/12/07/screencapture-localhost-3000-write-a-journey-2024-12-07-12_48_067c93c9d9202f4e14.md.png)

- **Профиль пользователя**  
  ![Профиль пользователя](https://s3.radikal.cloud/2024/12/07/screencapture-localhost-3000-account-2024-12-07-12_49_1873a5650d9ada03bf.md.png)

---

## Анализ выполнения задачи

- **Процесс создания пользователя**: Реализован процесс регистрации и авторизации с использованием NextAuth.
- **Запись путешествия**: Пользователь может указать местоположение и добавить изображения.
- **Просмотр путешествий**: Разработана функциональность для просмотра путешествий других пользователей.
- **Геопозиция**: Интегрирована возможность указания геопозиции с использованием карты.
- **Изображения мест**: Реализована возможность загрузки изображений для путешествия.
- **Стоимость путешествия**: Возможность добавления стоимости путешествия.

---

## Рекомендации по устранению ошибок

1. Провести тестирование на различных устройствах для проверки корректности отображения информации.
2. Добавить обработку ошибок при загрузке изображений (например, проверку формата и размера).
3. Улучшить интерфейс для мобильных устройств, так как некоторые элементы плохо отображаются на малых экранах.
4. Реализовать возможность фильтрации путешествий по критериям (стоимость, тип путешествия, рейтинг и т.д.).
5. Добавить возможность удаления или редактирования собственных путешествий.
