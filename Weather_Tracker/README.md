Weather API на Go
Простое веб-приложение на Go для получения данных о погоде через OpenWeather API.


Функциональность
GET /hello - приветственное сообщение

GET /weather/{city} - получение данных о погоде для указанного города


Требования
Go 1.16+

API ключ от OpenWeather Map


Установка и настройка
Клонируйте репозиторий:

git clone <repository-url>
cd <project-directory>

Получите бесплатный API ключ на OpenWeather Map

Создайте файл конфигурации .apiConfig в корне проекта:

{
  "OpenWeatherApiKey": "ваш_api_ключ_здесь"
}

Запустите приложение:

bash
go run main.go

Cервер запустится на порту 8000
