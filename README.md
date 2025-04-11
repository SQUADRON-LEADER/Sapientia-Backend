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

## 🖼️ ScreenShot
![Screenshot 2025-04-11 125603](https://github.com/user-attachments/assets/5854586b-6842-4569-9b9f-fce986b9c2d6)
enshots
![Screenshot 2025-04-11 125613](https://github.com/user-attachments/assets/f0bcb9e3-cf4e-4874-9c7b-b45ac0b53268)
![Screenshot 2025-04-11 125620](https://github.com/user-attachments/assets/fcfe8e30-4728-4824-8c14-d0b76da8be4f)
![Screenshot 2025-04-11 125628](https://github.com/user-attachments/assets/f9589678-5560-4637-b562-df5b537b73d1)



> 📸 *Add your screenshots to `.github/assets/` or any public image host and replace the links above.*

## 🔮 Future Improvements

- [ ] Convert the backend into a REST API using **FastAPI**
- [ ] Deploy model on HuggingFace or Render
- [ ] Add streaming sentiment analysis via websockets

## 👨‍💻 Authors

- [Aayush]
- [Vineet Sahoo]
- [Aradhaya Pandey]
- [Bharat Chandra]
- 

## 📝 License

This project is licensed under the MIT License.

---

> "Let your code do the talking – Sapientia deciphers the emotion." 🧠✨

