# 📚 Semantic Book Recommender

A powerful content-based book recommendation system that leverages semantic similarity using state-of-the-art language models. Instead of relying on keyword matches, it understands the *meaning* of a user query and returns the most relevant books.

---

## 🚀 Features

✅ Semantic matching using Sentence Transformers  
✅ Content-based recommendations (no user history required)  
✅ Fast cosine similarity search  
✅ Streamlit web interface for easy use  
✅ Modular and extendable architecture  

---

## 🛠️ Tech Stack

- **Python 3**
- Streamlit
- Sentence Transformers (Hugging Face)
- Pandas
- scikit-learn
- dotenv

---

## 🗂️ Project Structure

semantic-book-recommender/
│
├── app.py # Streamlit application
├── semantic.py # core recommendation logic
├── data/ # (dataset, excluded from repo)
├── requirements.txt
├── .env # (excluded from repo)
├── screenshots/ # UI screenshots
└── README.md


## ⚙️ Setup & Installation

> **Note**: Make sure you have Python installed, and your `.env` file created with your Hugging Face token.

```bash
git clone https://github.com/simrandalal/semantic-book-recommender.git
cd semantic-book-recommender
pip install -r requirements.txt


Then add a .env file:
HUGGINGFACEHUB_API_TOKEN=your_token_here

and place your dataset in the data/ folder (expected as a CSV with book details).

## ▶️ How to Run
streamlit run app.py
This will launch the app on localhost:8501 in your browser.

## 📊 Dataset
Dataset is excluded for privacy.
You can use your own CSV dataset with columns like:

title
author
description

## 💡 How It Works
✅ Loads book descriptions
✅ Embeds them into semantic vectors with a transformer model
✅ Calculates cosine similarity to find the closest matches
✅ Displays them interactively via Streamlit


## 🌟 Future Enhancements
- Add user ratings and collaborative filtering
- Pagination for large datasets
- Deploy to cloud (e.g., Streamlit Cloud, Heroku)
- Add genre-based filtering

## 🤝 Contributing
PRs are welcome! Please open an issue first to discuss proposed changes.

📝 License
This project is licensed under the MIT License.

🙋‍♀️ Author
Simran Dalal
GitHub

Feel free to adapt or ask me to edit this further — I’m here to help! 🚀
