# 🧠 Text Analysis Using Python (Streamlit)

### 📘 Project Description
**Text Analysis Using Python (Streamlit)** is an interactive Natural Language Processing (NLP) project that allows users to process, analyze, and visualize textual data directly in the browser.  
The main goal of this project is to turn raw text data into meaningful insights using Python libraries like **pandas**, **NLTK**, **matplotlib**, and **wordcloud**, and present results interactively via **Streamlit**.

This project is suitable for:
- Word frequency analysis  
- Text preprocessing and cleaning  
- Visualizing text data (bar charts, word clouds)  
- Learning and experimenting with Python NLP and interactive dashboards  

---

## 🌐 Live Demo

Try the app online here:  
👉 **[Text Analysis Using Python - Streamlit App](https://s5rngy5cqgen9wjcnoqs7g.streamlit.app/)**

Features of the live app:
- Upload your own CSV with textual data  
- Explore word frequency charts and distributions  
- Generate interactive visualizations with minimal setup  

No installation required — just open the link and start analyzing text!  



## 🧐 Overview

This project provides a workflow to analyze textual datasets in CSV format.  
The script `graph.py` and the Streamlit app load and process text, generate word frequency distributions, and visualize patterns through interactive charts.  

Use it to:
- Understand common words and themes in text  
- Perform exploratory text data analysis (EDA)  
- Visualize textual patterns in an interactive manner  

---

## ✨ Features

✅ Text preprocessing (lowercase, punctuation removal, stopwords removal)  
✅ Word frequency analysis  
✅ Visualizations: bar charts, word clouds  
✅ Modular Python code (`graph.py`)  
✅ Streamlit interactive dashboard  
✅ Easy-to-extend for more NLP tasks  

---

## 📁 Repository Structure

```
Text-Analysis-Using-Python-Streamlit/
│
├── data.csv              # Sample text dataset
├── graph.py              # Script for text visualization and analysis
├── requirements.txt      # Python dependencies
├── LICENSE               # License information
└── README.md             # Project documentation
```

---

## 🧰 Dependencies / Requirements

Python packages (listed in `requirements.txt`):

```
numpy
pandas
matplotlib
nltk
wordcloud
scikit-learn
streamlit
```

> 🐍 Python 3.8+ recommended  

---

## ⚙️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/LaxmidharPenta/Text-Analysis-Using-Python-Streamlit.git
cd Text-Analysis-Using-Python-Streamlit
```

2. **Create a virtual environment (recommended)**
```bash
python -m venv venv
venv\Scripts\activate     # Windows
# or
source venv/bin/activate  # Linux/Mac
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Optional:** Download NLTK resources
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

---

## ▶️ Usage

### Run Python script locally
```bash
python graph.py
```

### Run Streamlit app locally
```bash
streamlit run graph.py
```

**Features:**
- Load text data (`data.csv` or your own CSV)  
- Generate word frequency distributions  
- Create interactive visualizations  

---

## 📊 Example Output

- Bar charts of top frequent words  
- Word clouds of the most used terms  
- Distribution plots of text length  

*(You can include screenshots here if desired.)*

---

## 🧩 Data

- **File:** `data.csv`  
- **Description:** Contains sample text entries (one text per row).  
- Users can replace it with their own dataset for custom analysis.  

---

## 🚀 Future Enhancements

- Sentiment analysis (TextBlob, VADER)  
- Named Entity Recognition (NER) with spaCy  
- Topic modeling using LDA  
- Interactive dashboards and filters in Streamlit  

---

## 🤝 Contributing

1. Fork the repository  
2. Create a branch: `git checkout -b feature/YourFeature`  
3. Make changes and commit: `git commit -m "Add feature XYZ"`  
4. Push your branch: `git push origin feature/YourFeature`  
5. Open a Pull Request  

Follow Python style conventions and include docstrings.

---

## 📜 License

MIT License — see [LICENSE](LICENSE) file for details.

---

## 📬 Contact

👤 **Author:** Laxmidhar Penta  
🔗 GitHub: [LaxmidharPenta](https://github.com/LaxmidharPenta)  
📧 Email: *(laxmidharpenta@gmail.com)*

---

> 💡 *If you find this project useful, please ⭐ star the repository and share feedback!*
