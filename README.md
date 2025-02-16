# Telegram Bot with NestJS

## Overview
This project is a Telegram bot built using the NestJS framework. The bot provides daily weather updates to users and includes an admin panel with Google authentication to manage bot settings and user accounts.

## Features
### User Features:
- Subscribe to receive daily weather updates.
- Unsubscribe from weather updates.

### Admin Features:
- Google Login authentication for secure access.
- Manage bot settings, including API keys.
- Block and delete users.

## Technologies Used
- **NestJS** - Backend framework.
- **MongoDB** - Database for storing user data and settings.
- **Telegram Bot API** - For bot interactions.
- **OpenWeather API** - Fetching weather updates.
- **Google OAuth** - For admin authentication.

## Setup and Installation
### Prerequisites:
- Node.js (>= 16.x)
- MongoDB
- A Telegram bot token (obtain via @BotFather on Telegram)
- OpenWeather API key
- Google OAuth credentials (Client ID and Client Secret)

### Steps to Run the Project:
1. **Clone the Repository**
   ```sh
   git clone https://github.com/agraharisaumya/WeatherGenieBot.git
   cd telegramWeatherBot
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
OPENWEATHER_API_KEY=your_openweather_api_key
MONGO_URI=your_mongodb_connection_string
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
SESSION_SECRET=your_session_secret

