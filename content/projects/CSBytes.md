---
title: "CSBytes"
date: 2024-05-28T17:27:51+03:00
url: '/projects/csbytes/'
#draft: true
---
[Github 
repo](https://github.com/MM58-crypto/CSBytes)

[Try it out!](https://csbytes.streamlit.app/)
# CSBytes: Cheat Sheet Generator
()

![CS gen UI](/cs_gen.png)

CSBytes is designed to generate cheat sheets based on user preferences and selections, whether it's for a programming language or a particular computer science topic. Powered by the advanced Gemini API, CSBytes delivers concise and tailored cheat sheets that users can easily download as PDF files. The application provides a user-friendly interface for seamless navigation and efficient cheat sheet generation.



## Features
- Genre-Based Suggestions: Users can select specific programming languages or CS topics.
- Concise Sheets: Provides succinct cheat sheets tailored to user selections.
- Downloadable PDFs: Generated sheets can be downloaded as PDF files.
- User-Friendly Interface: Easy to use and intuitive design.

## Built With 
- Streamlit
- Python
- Gemini API

## Prerequisites
The following packages are required to run this app locally:
1. Streamlit:

```
pip install streamlit
```

2. FPDF:

```
pip install fpdf
```

3. Google Generative AI:

``` 
pip install google-generativeai
```

## Installation
Follow the steps below to ensure that the project runs as intended locally:

1. Clone the repo:

```
git clone https://github.com/MM58-crypto/CSBytes.git
```

2. Inside the project directory, create a virtual environment by running the following command:

```
python -m venv your_virtual_environment_name (e.g., env)
```

3. Activate your virtual environment:
On Windows:

```
.\env\Scripts\activate
```

On macOS/Linux:

```
source env/bin/activate
```

4. Install the required packages from the <a href="#prerequisites"> Prerequisites</a> section:

5. Within the same directory, create a new file "config.py":

6. Within the config.py file, paste your own Gemini API key:
```
GEMINI_API_KEY = “YOUR_API_KEY”
```

(can be obtained https://aistudio.google.com/app/apikey)

7. Run the app by using the following command in the terminal:
streamlit run CS2.py


