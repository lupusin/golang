Weather API на Go
Простое веб-приложение на Go для получения данных о погоде через OpenWeather API.


Функциональность
GET /hello - приветственное сообщение

GET /weather/{city} - получение данных о погоде для указанного города



Требования
Go 1.16+

API ключ от OpenWeather Map



Установка и настройка

git clone <repository-url>
cd <project-directory>
Получите API ключ на OpenWeather Map
Создайте файл конфигурации .apiConfig:

{
  "OpenWeatherApiKey": "ваш_api_ключ_здесь"
}

go run main.go

Структура проекта
.
├── main.go          # Основной файл приложения
├── .apiConfig       # Файл конфигурации с API ключом
└── README.md        # Документация 