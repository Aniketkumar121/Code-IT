
# 🚀 Code IT : DSA Search Engine

A powerful and high-performance **DSA Search Engine** built using Express.js and EJS for seamless server-side rendering and fast problem retrieval.

---

## 📌 Project Description

- Built using **Express.js** and **EJS** for server-side rendering.
- Scraped and processed **3000+ coding problems** using Selenium.
- Implemented smart keyword generation (number-to-word conversion, lemmatization, spell-checking, camel case conversion).
- Enhanced search accuracy by 30% using advanced processing techniques.
- Optimized document ranking and search results using **TF-IDF** and **BM25** algorithms.
- Optimized for in-memory (RAM-based) fast indexing and searching.

---

## 📂 Project Structure

```
📦 root
├── Problems
│   └── problem_text_*.txt     # Contains problem descriptions
├── public
│   ├── *.svg / *.png          # Icons and images for UI
│   └── styles.css             # Stylesheet
├── views
│   └── EJS Templates (optional for rendering views)
├── IDF.txt                    # Precomputed Inverse Document Frequency
├── Magnitude.txt              # Precomputed magnitude for vectors
├── TF.txt                     # Term Frequency per document
├── TFIDF.txt                  # TF-IDF values per document
├── keywords.txt               # Extracted keywords
├── length.txt                 # Length of documents
├── problem-titles.txt         # Titles of coding problems
├── problem-urls.txt           # URLs of coding problems
├── app.js                     # Main Express.js application
├── tf-gen.js                  # TF-IDF generation script
├── TF.js                      # TF logic (alternative/utility)
├── TFIDF.js                   # TF-IDF calculation logic
├── idf.js                     # IDF calculation logic
├── keywords.js                # Keywords processing logic
├── length.js                  # Document length logic
├── magnitude.js               # Magnitude calculation logic
├── titles.js                  # Handles title related functionality
├── urls.js                    # Handles URL related functionality
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

---

## 🧠 Key Features

✅ **Web Scraped 3000+ Coding Problems** using Selenium  
✅ **Advanced Search Indexing** using TF-IDF and BM25 ranking  
✅ **Spell Check, Lemmatization, Number-to-Word, CamelCase Processing** for accurate keyword extraction  
✅ **In-memory Search Engine** for lightning-fast problem retrieval  
✅ **Simple and Clean UI** using Express.js and EJS  
✅ **Optimized Document Ranking and Relevancy Scoring**

---

## 📌 Installation Instructions

### Clone the repository

```bash
git clone https://github.com/Aniketkumar121/Code-IT.git
cd Code-IT
```

### Install dependencies

```bash
npm install
```

### Run the server

```bash
node app.js
```

Server will start running locally.  
You can visit:

```
http://localhost:3000
```

and start searching for DSA problems!

---

### Hosted on Render
```
https://code-it-gvpr.onrender.com/
```

## 📈 Future Enhancements

- Add Pagination in results
- Add tags and categories to problems
- Add support for multiple search algorithms dynamically
- Create an admin interface to add/edit problems

---
