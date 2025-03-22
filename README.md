# WeatherMap_b1_windParticle
# 🌬️ Real-Time Wind Particle Simulation 🌍

![Wind Simulation Demo](https://i.imgur.com/vexpWmo.gif)

A real-time wind particle visualization web app powered by **Leaflet.js** and **Open-Meteo API**.  
Displays live wind direction and speed as flowing particles over an interactive dark-themed map.

---

## 🚀 Features
- 📍 Interactive map centered on **Malta**
- 🌪️ Live wind data fetched from **Open-Meteo API**
- 💨 Particle-based wind flow animation
- 🧭 Real-time cardinal wind direction display
- 🎨 Dark aesthetic with smooth canvas overlay

---

## 🛠️ Technologies Used
- HTML5 + CSS3
- JavaScript (Vanilla)
- [Leaflet.js](https://leafletjs.com/)
- [Open-Meteo API](https://open-meteo.com/)
- Canvas 2D rendering

---

## 🌐 How to use
> _Host this HTML file or open directly in your browser to see it in action!_

```bash
git clone https://github.com/danielsuperone/WeatherMap_b1_windParticle
cd your-repo
```

- Now simply double click `index.html` and open it in your desired browser!
  <br><br><br><br>

  
⚙️ How it Works
- Fetches windspeed and wind direction

- Calculates wind vector (U, V) components

- Generates 500 particles randomly within map bounds

- Animates particles moving according to wind flow

- Updates wind data every 60 seconds

📌 Screenshot / Demo
![Wind Simulation Demo](https://i.imgur.com/vexpWmo.gif)

🗺️ Map Tiles
Tiles by CARTO

Dark mode tiles for better contrast with particles

📥 API Example
Example API call for real-time wind:
```bash
https://api.open-meteo.com/v1/forecast?latitude=35.9&longitude=14.5&current_weather=true&windspeed_unit=ms
```
<br><br>
✨ Customize
```bash
Change location (latitude, longitude) in the API URL

Adjust particleCount or pixelScale for different visual effects

Replace tile layer URL for a different map style
```

📄 License
```bash
MIT License
```


Let me know if you want:
✅ A "Usage" section  
✅ A "Contributing" section  
✅ File/folder structure  
✅ Deployed GitHub Pages link section
