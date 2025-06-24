# 📊 US GDP Bar Chart Visualization

This project is a **D3.js-based interactive bar chart** that visualizes the **United States Gross Domestic Product (GDP)** over time using data from FreeCodeCamp's JSON dataset.

> Built as part of the FreeCodeCamp Data Visualization Certification projects.

---

## 🌐 Live Preview

> You can open the notebook in Colab or export the HTML and run it in a browser.

Original Colab Notebook:  
[🔗 View in Google Colab](https://colab.research.google.com/drive/15O-tHjSveFNCfeWBOVivWSBdNKi2ikYW)

---

## 📁 Project Files

- `Visualize_Data_with_Bar_Chart.ipynb`: Jupyter/Colab notebook embedding the D3.js chart.
- Uses live data from:
https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json

yaml
Copy
Edit

---

## 🛠️ Features

- Responsive and interactive **bar chart**.
- Smooth **tooltip** on hover displaying:
- Year & Quarter (Q1, Q2, Q3, Q4)
- GDP in billions (formatted with commas)
- **Axes** with ticks and labels for clarity.
- Styling includes hover transitions and a clean layout.

---

## 📦 Technologies Used

- **D3.js v7**
- **HTML/CSS**
- **Google Colab / Jupyter Notebook**

---

## 🧠 How It Works

- Fetches JSON data from FreeCodeCamp’s dataset.
- Parses and maps GDP data by date.
- Renders SVG bars scaled by date and GDP value.
- Uses `d3.scaleTime()` and `d3.scaleLinear()` for axis generation.
- Tooltip appears dynamically on mouseover.

---

## 📬 Contact

If you have suggestions or questions, feel free to open an issue or reach out!

