# 📝 Story & Poem Generator App

This is a Streamlit web app that uses the Hugging Face API to generate creative **stories** and **poems** based on user input. The app offers a fun and interactive way to experiment with storytelling by customizing key elements of the narrative.

---

## 🚀 Features

- 📚 Generate **stories** or **poems**
- 🎭 Choose **genre** (e.g., fantasy, horror, sci-fi)
- 😄 Select **tone** (e.g., serious, funny, emotional)
- 👁️ Define **narrative perspective** (first person, third person, etc.)
- 👤 Input a **protagonist** (e.g., a robot detective)
- 🌍 Set the **setting** (e.g., post-apocalyptic Earth)
- ✨ Add **special requirements** (e.g., include a talking dog, must rhyme)

---

## 🧠 Powered By

- [Streamlit](https://streamlit.io/) – For the web interface
- [Hugging Face Transformers](https://huggingface.co/) – For text generation via API
- [Python](https://python.org/) – Core language
- Other packages: `requests`, `python-dotenv`, `fpdf`, `pandas`, `numpy`

---

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/story-poem-generator.git
   cd story-poem-generator
Install dependencies:
bash
pip install -r requirements.txt

Set up environment variables:
Create a .env file and add your Hugging Face API key:

ini
HUGGINGFACE_API_KEY=your_api_key_here

Run the app:
streamlit run app.py

🌐 Deploy on Render
Add the following settings when deploying on Render:

Build Command: pip install -r requirements.txt

Start Command: streamlit run app.py

Environment Variable: HUGGINGFACE_API_KEY with your key

✍️ Example Use Case
Generate a funny fantasy story written in third person about a lonely vampire living in a haunted castle, with the special requirement: "must include a ghost chicken that gives advice."

<img width="1061" height="729" alt="image" src="https://github.com/user-attachments/assets/92591fff-ae3e-4f46-a4b8-ec92ab56e6ea" />
