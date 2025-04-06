## 📚 Book Recommendation Chatbot\
This project was developed as part of an internship task at **Future Interns**. It features a conversational AI chatbot that recommends books based on user preferences using Natural Language Processing (NLP) and a recommendation system.

## 📁 Dataset\
The chatbot is trained and tested using a **Books Dataset**, which contains information such as:

- Book titles
- Authors
- Genres
- Descriptions
- Ratings

## 🎯 Objective\
To build an intelligent chatbot that:

- Interacts with users conversationally
- Understands their reading preferences
- Recommends suitable books accordingly

## 🧠 Technologies & Skills Applied

- **Natural Language Processing (NLP)** using NLTK
- **Conversational AI** using ChatterBot
- **Recommendation System** using Scikit-learn (TF-IDF / Cosine Similarity)

## 📊 Core Features

- Intent recognition from user queries
- Content-based filtering to recommend books
- Text similarity-based matching using TF-IDF
- Predefined and dynamic responses from chatbot

## 🛠️ Installation\
Install all required libraries:

```bash
pip install pandas numpy nltk scikit-learn chatterbot chatterbot_corpus
```

## 📦 Files Included

- `task 3.ipynb`: Complete code for chatbot creation and book recommendation logic
- `books.csv`: Dataset used for recommendations
- `README.md`: Project overview and instructions

## 🚀 How to Run the Project

1. Ensure the dataset (`books.csv`) is in the same directory.
2. Open and run all cells in `task 3.ipynb` using Jupyter Notebook.
3. Interact with the chatbot by entering your book preferences (e.g., "I like mystery novels").
4. Receive personalized book recommendations.

## 📈 Output Includes

- Interactive chatbot interface in the notebook
- List of recommended books with titles and authors
- Console-based chat simulation

## 🗂️ Future Improvements

- Add a GUI using Tkinter or Streamlit
- Improve NLP pipeline using spaCy or BERT
- Enhance recommendation logic with hybrid filtering or user feedback loop

## 👨‍💻 Author

Sumit — developed as an internship project for **Future Interns**

