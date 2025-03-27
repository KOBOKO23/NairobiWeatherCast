Got you, Philip! 💯 If you're seeing the asterisks (`*`) appear **as actual asterisks** on GitHub instead of formatting the text, it’s likely because:

- You’re wrapping the whole block in triple backticks \(```markdown`\), which **tells GitHub to treat the whole thing as code**, not Markdown text.

### ✅ Solution:

To make your **README display proper formatting**, **don’t wrap the entire thing in triple backticks**. Just use normal Markdown syntax **without the outer ```markdown code block**.

Here’s your updated README version — **clean and GitHub-ready**, with proper formatting for bold, code, and headings:

---

# 🌦 NairobiWeatherCast

**NairobiWeatherCast** is a simple weather forecasting app built for educational purposes, focusing on **rainfall prediction in Nairobi**. This MVP was created as part of an *Operational Training Course in Meteorology* to show that it’s possible to build a custom weather forecasting model using open-source tools.

---

## 🎯 Project Goals

- Predict rainfall in Nairobi using historical weather data.  
- Build and train a machine learning model from scratch.  
- Visualize forecasts in a clean, user-friendly web interface.  
- Provide a solid foundation for future expansion (temperature, APIs, etc.).

---

## 🛠 Technologies Used

- **Python** – Programming language  
- **Flask** – Web framework  
- **pandas** – Data processing  
- **matplotlib** – Data visualization  
- **scikit-learn** *(or TensorFlow)* – Machine learning modeling  

---

## 📁 Project Structure

```
nairobiweathercast/
├── static/
│   ├── scripts/
│   └── images/
├── templates/
│   └── index.html
├── data/
│   └── historical_weather.csv
├── app.py
├── model.py
├── utils.py
├── console.py
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/nairobiweathercast.git
   cd nairobiweathercast
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate   # On Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask app**
   ```bash
   python app.py
   ```

5. **Open in your browser**
   ```
   http://127.0.0.1:5000/
   ```

---

## 📊 Features

- Upload and process historical weather data  
- Train a basic ML model to forecast rainfall  
- Display forecast results in graph form  
- Simple and intuitive interface  

---

## 🌱 Future Ideas

- Predict temperature alongside rainfall  
- Add real-time weather data via external APIs  
- Improve accuracy with deep learning models  
- Mobile and responsive UI design  

---

## 👨‍💻 Author

**Philip Koboko**  
Meteorology Student & Developer  
Built for academic and training purposes.

---