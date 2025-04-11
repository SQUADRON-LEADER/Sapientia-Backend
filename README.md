# 🌟 Sapientia Backend - Sentiment Analysis 🧠

This repository contains the backend logic for **Sapientia**, an AI-powered sentiment analysis platform that processes and interprets textual data. Developed and trained using Kaggle notebooks, the model enables advanced NLP capabilities for understanding user sentiment.

## 🗂️ Project Structure

```
Sapientia-Backend/
├── sentimental-analysis.ipynb   # Main Kaggle notebook
├── requirements.txt             # Python dependencies
├── README.md                    # Project documentation
```

## 🚀 Features

- 🔍 **Sentiment Classification**: Analyze text and classify it into Positive, Negative, or Neutral sentiments.
- 🧹 **Text Preprocessing**: Includes tokenization, stopword removal, stemming/lemmatization.
- 📊 **Model Evaluation**: Confusion matrix, accuracy score, and performance metrics.
- 💾 **Model Export**: Export trained model using `pickle` or `joblib`.

## 🧪 Tech Stack

- 💻 **Python 3.10+**
- 📘 **Pandas**
- 🔤 **NLTK** / **spaCy**
- 🧠 **Scikit-learn**
- 🧪 **Jupyter Notebook / Kaggle Notebook**

## 📦 Installation

```bash
# Clone the repository
$ git clone https://github.com/yourusername/Sapientia-Backend.git
$ cd Sapientia-Backend

# Create a virtual environment
$ python -m venv venv
$ source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
$ pip install -r requirements.txt
```

## 🧾 Usage

1. Open `sentimental-analysis.ipynb` in Kaggle or Jupyter Notebook.
2. Run all cells sequentially to train and test the model.
3. You can modify the notebook to experiment with different ML models.
4. Export the model using `pickle` or `joblib` to integrate into your API/backend.

## 🔗 Frontend Repository

> The user interface is built using **Vite + React + TypeScript + Tailwind + shadcn/ui**. Find the UI repo here:

👉 [Sapientia Frontend](https://github.com/Vineetsahoo/Sapientia)

### 🧱 Frontend Highlights:

- 🧩 **Component-based structure**
- 🧠 `client/src/components`: All reusable UI components
- 🚦 `routes`: Handles routing between pages
- 🛠️ `services`: API services and helpers
- ⚙️ `vite.config.ts`, `tailwind.config.ts`: Project configuration files

## 🔮 Future Improvements

- [ ] Convert the backend into a REST API using **FastAPI**
- [ ] Deploy model on HuggingFace or Render
- [ ] Add streaming sentiment analysis via websockets

## 👨‍💻 Authors

- [Aayush]
- [Vineet Sahoo]
- [Aradhaya Rahul Pandey]
- [Bharat Chandra]

## 📝 License

This project is licensed under the MIT License.

---

> "Let your code do the talking – Sapientia deciphers the emotion." 🧠✨

