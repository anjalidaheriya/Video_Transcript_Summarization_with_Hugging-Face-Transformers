# 🎬 Video Transcript Summarization with Hugging Face Transformers

This project focuses on **automated summarization of video transcripts** using powerful transformer-based models from the **Hugging Face Transformers** library. It extracts meaningful, concise summaries from long-form video content—making it easier to digest key insights from lectures, podcasts, or meetings.

> 🔗 **Try it in Colab:**  
[Open Notebook in Google Colab](https://colab.research.google.com/drive/1Isc4hwCXnLISFTnW-FjYBzIT_uHENN6W?usp=sharing)

---

## 📌 Project Overview

The system performs **abstractive summarization** on video transcripts. It uses **pretrained models** such as `BART`, `T5`, or `DistilBART` to generate human-like summaries that go beyond copy-pasting sentences.

### Key Steps:
- Accept raw transcript text (e.g., from YouTube, Zoom, etc.)
- Clean and chunk text to meet token limits
- Apply Hugging Face summarization pipelines
- Combine and post-process segment summaries

---

## 🛠️ Tech Stack

- 🧠 **Hugging Face Transformers**
- 💬 **BART / T5 / DistilBART models**
- 🐍 Python 3.10+
- 📚 Datasets (optional): YouTube subtitles, Whisper transcripts
- 🚀 Google Colab for execution

---

## 🧪 Example Output

**Input:** A 10-minute educational video transcript  
**Output Summary:**  
> "The video introduces linear regression, explaining how it models the relationship between variables using a best-fit line. The speaker walks through a hands-on coding example in Python using scikit-learn."

---

## 📊 Evaluation

Summaries were evaluated using:
- **ROUGE Scores** (Recall-Oriented Understudy for Gisting Evaluation)
- **Manual review** for coherence, relevance, and readability

---

## 🚀 Future Enhancements

- Integrate automatic transcription (YouTube API / Whisper)
- Add extractive + abstractive summary comparison
- Build a simple UI for non-technical users

---

## 👩‍💻 Author

**Anjali Daheriya**  
Feel free to connect, contribute, or fork this project!

---


