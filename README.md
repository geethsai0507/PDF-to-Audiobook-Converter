# PDF to Audiobook Converter

## Description
This project is a **Streamlit-based web application** that converts PDF documents into audiobooks in different languages. It extracts text from a PDF file, translates it into the desired language, and generates speech using **Google Text-to-Speech (gTTS)**. The app is designed for **language learners, visually impaired individuals, and anyone looking to listen to textual content on the go**.

---

## Features
* 📂 **Upload PDFs**: Users can upload any English-language PDF.
* 🌍 **Multilingual Support**: Choose from multiple languages for translation.
* 🎧 **Text-to-Speech Conversion**: Converts text into speech using gTTS.
* 📝 **Batch Processing**: Handles large PDFs efficiently by processing in 60-page chunks.
* 📥 **Download Options**: Provides downloadable text and audio files.
* 🎵 **Audio Playback**: Listen to the generated audiobook directly in the browser.
* 📊 **Progress Tracking**: Displays real-time progress for conversion.

---

## Installation
### 1️⃣ Clone the repository
```sh
git clone https://github.com/your-username/pdf-to-audiobook.git
cd pdf-to-audiobook
```

### 2️⃣ Create a virtual environment (optional but recommended)
```sh
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### 3️⃣ Install dependencies
```sh
pip install -r requirements.txt
```

### 4️⃣ Run the application
```sh
streamlit run main1.py
```

---

## Dependencies
* **Streamlit**: Web application framework
* **PyPDF2**: Extracts text from PDFs
* **Google Translator API**: Translates text into multiple languages
* **gTTS**: Converts text to speech
* **Deep Translator**: An alternative translation API

Install all dependencies using:
```sh
pip install -r requirements.txt
```

---

## Usage
1. Run the app using `streamlit run main1.py`
2. Upload a PDF file.
3. Choose the target language for translation.
4. Enter the output directory where audio files will be saved.
5. Click the **Process** button to extract, translate, and generate audio.
6. Listen to the generated audiobook or download the translated text.

---

## Contributing
Contributions are welcome! If you'd like to improve this project, feel free to fork the repository and submit a pull request.

---

## Contact
For any questions or issues, feel free to reach out!
mail:[geethsai0507@gmail.com](url)

