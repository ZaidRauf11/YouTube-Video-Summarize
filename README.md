# 🎥 YouTube Video Summarizer

An **AI-powered YouTube video analyzer** built with **Streamlit, Agno, and Groq LLMs**.
It extracts video transcripts, processes metadata, and generates a structured summary with key highlights.

---

## 🚀 Features

* 📝 **Summarize any YouTube video** using AI
* ⏱ **Timestamps** for key sections (when available)
* 📜 **Transcript-based fallback** if video metadata isn’t accessible
* 🎨 **Streamlit UI** for a clean and simple experience

---

## 📂 Project Structure

```
📦 youtube-summarizer
 ┣ 📜 app.py            # Main Streamlit app
 ┣ 📜 requirements.txt  # Dependencies
 ┣ 📜 .env              # API key (not shared publicly)
 ┗ 📜 README.md         # Project documentation
```

---

## ⚙️ Installation

1. **Clone this repo**

```bash
git clone https://github.com/ZaidRauf11/youtube-summarizer.git
cd youtube-summarizer
```

2. **Create a virtual environment**

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Add your API key**
   Create a `.env` file in the root directory:

```
GROQ_API_KEY=your_api_key_here
```

---

## ▶️ Usage

Run the Streamlit app:

```bash
streamlit run app.py
```

1. Paste a YouTube video URL
2. Click **Summarize Video**
3. Get an AI-generated summary instantly 🎉

---

## 🛠 Tech Stack

* [Streamlit](https://streamlit.io/) – UI framework
* [Agno](https://pypi.org/project/agno/) – AI agent framework
* [Groq](https://groq.com/) – LLM model provider
* [YouTube Transcript API](https://pypi.org/project/youtube-transcript-api/) – For fetching captions

---

## 📌 Example Query

👉 Input:

```
https://www.youtube.com/watch?v=dQw4w9WgXcQ
```

👉 Output:

```
📄 Summary:
- Introduction to the topic
- Key highlights with timestamps
- Closing remarks
```

---

## ⚠️ Notes

* Some videos may not have transcripts, which limits summarization.
* Ensure your **Groq API key** is valid and added in `.env`.

---

## 📜 License

This project is licensed under the **MIT License**.

---

Do you want me to also generate a **`requirements.txt`** file for this app so you can run it without errors?
