# TC1004B---IoT-Golife
## Description 📝
A complete Internet of Things system implementing an environmental monitoring through DHT sensor data collection on NodeMCU ESP8266. This repo is a solution with real-time data transmission to a web-based dashboard for visualization and analysis.

## Tech Stack 🗜️🔧
| Layer    | Technologies      | Key Components                             |
| -------- | ----------------- | ------------------------------------------ |
| Hardware | ESP8266, DHT11    | NodeMCU, DHTesp library                    |
| Network  | WiFi, HTTP        | ESP8266WiFi, ESP8266HTTPClient             |
| Backend  | PHP, MySQL        | dbwrite.php, dbread.php, mysqli            |
| Frontend | HTML5, JavaScript | Bootstrap, Chart.js, jQuery                |
| Database | MySQL             | microsoft2 database, medidas/planta tables |

## Sequence Diagram 🔄
![image](https://github.com/user-attachments/assets/11018aa4-9050-4f55-b52b-67cf7cc2bcb4)

## Features ✅
- **Data Collection Frequency:** 5-second intervals for sensor readings
- **Communication Protocol:** HTTP POST requests with form-encoded data
- **Error Handling:** NaN value detection with fallback to default values
- **Status Monitoring:** LED-based visual feedback for system states
- **Web Interface:** Auto-refreshing dashboards with real-time data visualization
