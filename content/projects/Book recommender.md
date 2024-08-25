---
title: "Book Recommender"
date: 2024-08-25T19:25:31+03:00
#draft: true
---

[Github repo](https://github.com/MM58-crypto/Book-recommender)

![br ui](/book-recommender.png)

# Book Recommender

This simple book recommender webapp is designed to provide personalized book suggestions based on user preferences. Users can input their favorite genres, and the system generates curated recommendations to explore new reading choices.

## Features
- Genre-Based Suggestions: Users can input preferred genres for book recommendations.
- Personalized Recommendations: Curated suggestions based on user inputs.
- User-Friendly Interface: easy to use and intuitive design.
- Book summarizer: Users can input the book title of one of the recommended books and a summary of the selected book  will be displayed. (new)

## Built with (Frameworks)
- Streamlit  


## Prerequisites
The following packages are required to run this app locally:
1. Streamlit:
```
pip install streamlit
```
2. OpenAI:
```
pip install openai
```

## Installation
Follow the steps below to ensure that the project runs as intended locally:

1. Clone the repo
```
git clone https://github.com/MM58-crypto/Book-recommender.git
```
2. Inside the project directory, create a virtual environment by running the following command:
```
python -m venv your_virtual_environment_name (eg: env)
```
3. Activate your virtual environment:

```
source env/bin/activate
```
4. Install the required packages from the <a href="#prerequisites">Prerequisites</a> section

5. Within the same directory, create a new file "config.py"

6. Within the config.py file, paste your own OpenAI API key:

(can be obtained from openai.com, API keys > + Create new secret key)
```
OPENAI_API_KEY ="YOUR_API_KEY"
```
7. Run the app by using the following command in the terminal:
```
streamlit run main.py
```

