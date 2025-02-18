
```markdown:README.md
# 🌐 Multilingual Translator

A powerful web application built with Streamlit that allows users to translate text and PDF documents into multiple languages using Google's Gemini AI model.

## 🚀 Features

- **Text Translation**: Translate any text input into 100+ languages
- **PDF Translation**: Upload and translate PDF documents while preserving structure
- **Download Options**: Download translated content as text files
- **User-Friendly Interface**: Clean and intuitive web interface
- **Multiple Language Support**: Supports 100+ languages including:
  - Major languages (English, Spanish, Chinese, French, German, etc.)
  - Regional languages (Hindi, Bengali, Telugu, etc.)
  - Rare languages (Hawaiian, Luxembourgish, Scots Gaelic, etc.)

## 🛠️ Technology Stack

- **Frontend**: Streamlit
- **AI Model**: Google Gemini 2.0 Flash
- **PDF Processing**: PyPDF2
- **Language Chain**: LangChain with Google Generative AI

## 📋 Prerequisites

- Python 3.8 or higher
- Google API key for Gemini AI

## ⚙️ Installation

1. Clone the repository:
```bash
git clone <repository-url>
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Set up your Google API key:
   - Get an API key from Google AI Studio
   - Replace the API key in `app.py` or set it as an environment variable

## 🚀 Usage

1. Run the application:
```bash
streamlit run app.py
```

2. Access the web interface through your browser (typically http://localhost:8501)

3. For text translation:
   - Enter text in the text area
   - Select target language from the dropdown
   - Click "Translate Text"
   - Download the translation if needed

4. For PDF translation:
   - Upload PDF through the sidebar
   - Select target language
   - Click "Translate PDF"
   - Download the translated content

## 🌍 Supported Languages

The application supports translation into 100+ languages, including:
- European languages (French, German, Italian, etc.)
- Asian languages (Chinese, Japanese, Korean, etc.)
- African languages (Swahili, Zulu, Afrikaans, etc.)
- Indian languages (Hindi, Tamil, Telugu, etc.)
- And many more!

## ⚠️ Important Notes

- Large PDF files may take longer to process
- The quality of translation depends on the Gemini AI model
- Ensure your PDF files are text-searchable for best results
- Keep your API key secure and never share it publicly

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Support

For support, please open an issue in the repository or contact the maintainers.

## 🙏 Acknowledgments

- Google Gemini AI for providing the translation capabilities
- Streamlit for the wonderful web framework
- The open-source community for various dependencies
```
