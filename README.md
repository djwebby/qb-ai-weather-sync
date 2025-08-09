QBCore AI Weather & Time Sync
🚀 AI-generated QBCore Weather & Time Sync Script for FiveM
Adds dynamic weather rotation, global time synchronization, and admin control for your RP server. Built with the help of artificial intelligence and optimized for performance.

🌟 Features
🌦 Dynamic Weather – Rotates through realistic weather types on a timer.

⏰ Time Sync – Keeps all players on the same in-game time.

🛠 Admin Commands – Easily change, freeze, or adjust weather/time.

⚙ Configurable – Adjust defaults, rotation speed, and permissions in config.lua.

💾 Lightweight – Minimal performance impact, works out of the box with QBCore.

📦 Installation
Download the latest release or clone the repo:

bash
Copy
Edit
git clone https://github.com/YOURUSERNAME/qbcore-ai-weather-sync.git
Place the folder in your resources directory.

Add this line to your server.cfg:

ruby
Copy
Edit
ensure qb-weather
Edit config.lua to customize weather types, rotation speed, default time, and permissions.

🔧 Commands
Command	Description
/weather <type>	Change weather instantly (e.g., RAIN, CLEAR, THUNDER)
/time <hour> <minute>	Set in-game time (24-hour format)
/freezeweather	Toggle frozen weather
/freezetime	Toggle frozen time

Note: Permissions can be set via QBCore admin roles or ACE permissions.

⚙ Configuration (config.lua)
lua
Copy
Edit
Config.TimeCycleSpeed = 2.0 -- In-game speed multiplier
Config.StartHour = 12
Config.StartMinute = 0
Config.DefaultWeather = 'EXTRASUNNY'
Config.WeatherChangeInterval = 15 -- Minutes
Config.AvailableWeatherTypes = { "EXTRASUNNY", "CLEAR", "CLOUDS", "OVERCAST", "RAIN", "THUNDER", "SMOG", "FOGGY" }
Config.AdminPermission = 'weatheradmin' -- ACE or QBCore group
📜 License
This resource is free to use and modify for personal or server use.
Attribution is appreciated but not required.
