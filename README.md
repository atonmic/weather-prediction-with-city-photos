# weather-prediction-with-city-photos
A Python GUI application using Tkinter that fetches real-time weather data and displays relevant city images using OpenWeatherMap and Unsplash APIs. Users can enter a city name to view current weather conditions and browse through beautiful images of the city.
# 🌤 Weather Predictor with City Image Viewer

A Python desktop application built using **Tkinter** that fetches real-time weather data and displays beautiful images of the searched city using the **OpenWeatherMap API** and **Unsplash API**.

## 🧰 Features

- 🌍 Get real-time weather info for any city worldwide.
- 🌡️ Displays temperature, humidity, wind speed, and weather description.
- 🖼️ Fetches and displays high-quality images of the city.
- ⏪⏩ Navigate through multiple city images (Previous/Next).

## 📸 Preview

![Weather App Demo](preview.gif) *(Add your own screenshot or GIF here)*

---

## 🚀 Getting Started

### 📦 Prerequisites

- Python 3.x
- `pip` installed

### 🔧 Installation

1. **Clone this repository**:

   ```bash
   git clone https://github.com/yourusername/weather-image-app.git
   cd weather-image-app
   ```

2. **Install dependencies**:

   ```bash
   pip install requests pillow
   ```

3. **Add your API keys**:
   - Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)
   - Get a free API key from [Unsplash](https://unsplash.com/developers)

   Open the `main.py` file and replace:
   ```python
   WEATHER_API_KEY = 'your_openweathermap_api_key'
   IMAGE_API_KEY = 'your_unsplash_access_key'
   ```

---

## 🖥️ How to Run

```bash
python main.py
```

---

## 🛠 Tech Stack

- **Python**
- **Tkinter** – GUI library
- **Requests** – For making API calls
- **Pillow (PIL)** – For image handling
- **OpenWeatherMap API**
- **Unsplash API**

---

## 📌 To Do

- [ ] Add unit tests
- [ ] Improve UI with custom themes
- [ ] Add support for more weather details (e.g. forecast)
- [ ] Offline caching of images

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📃 License

[MIT License](LICENSE)

---

## 🙌 Acknowledgments

- [OpenWeatherMap](https://openweathermap.org)
- [Unsplash](https://unsplash.com)
- [Tkinter Documentation](https://docs.python.org/3/library/tk.html)
