# 🎥 ChatTube

**ChatTube** is an AI-powered application that allows users to interact with YouTube videos conversationally. It extracts subtitles using the YouTube Transcript API and enables users to ask questions directly related to the video content. The responses are generated using Grok AI as the chat model and Hugging Face for embeddings.

---

## 🚀 Features

- 🔍 Extract subtitles (transcripts) from any public YouTube video
- 💬 Ask any question about the video — get intelligent, context-aware responses
- 🧠 Uses **Grok AI** as the chatbot for natural and fluent answers
- 🧩 Utilizes **Hugging Face embedding models** to semantically understand video content
- 🛠️ Lightweight and easy to run

---

## 🧠 Tech Stack

| Component | Technology |
|-----------|------------|
| Subtitle Extraction | YouTube Transcript API |
| Embedding Model | Hugging Face Transformers |
| Chat Model | Grok AI |
| Language | Python |
| Interface | Streamlit |

---

## 📦 Installation

```bash
git clone https://github.com/your-username/chattube.git
cd chattube
pip install -r requirements.txt
```

---

## 🔧 Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/chattube.git
   cd chattube
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```env
   GROK_API_KEY=your_grok_api_key_here
   HUGGINGFACE_API_KEY=your_huggingface_api_key_here
   ```

4. **Run the application**
   ```bash
   streamlit run app.py
   ```

---



## 🎯 Usage

1. **Launch the app**
   ```bash
   streamlit run app.py
   ```

2. **Enter a YouTube URL**
   - Paste any public YouTube video URL
   - The app will automatically extract the transcript

3. **Start chatting**
   - Ask questions about the video content
   - Get AI-powered responses based on the transcript

### Example Queries
- "What are the main points discussed in this video?"
- "Can you summarize the key takeaways?"
- "What did the speaker say about [specific topic]?"
- "At what timestamp was [topic] mentioned?"

---

## 🔑 API Keys Required

You'll need API keys for:

1. **Grok AI** - Get your API key from [Grok AI Platform](https://grok.x.ai)
2. **Hugging Face** - Get your API key from [Hugging Face](https://huggingface.co/settings/tokens)

---

## 📋 Requirements

```txt
streamlit==1.28.1
youtube-transcript-api==0.6.1
sentence-transformers==2.2.2
openai==1.3.3
python-dotenv==1.0.0
numpy==1.24.3
scikit-learn==1.3.0
requests==2.31.0
beautifulsoup4==4.12.2
```

---

## 🚀 Features in Detail

### Transcript Extraction
- Automatically fetches YouTube video transcripts
- Supports multiple languages
- Handles auto-generated and manual captions

### Semantic Search
- Uses advanced embedding models to understand context
- Finds relevant transcript segments for user queries
- Supports complex question answering

### AI Chat Integration
- Powered by Grok AI for natural conversations
- Context-aware responses based on video content
- Maintains conversation history during session

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 🐛 Troubleshooting

### Common Issues

**"No transcript available"**
- Ensure the video has captions enabled
- Try with a different video that has auto-generated captions

**API Key Errors**
- Double-check your API keys in the `.env` file
- Ensure you have sufficient API credits

**Installation Issues**
- Use Python 3.8 or higher
- Consider using a virtual environment:
  ```bash
  python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate
  pip install -r requirements.txt
  ```

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🌟 Acknowledgments

- [YouTube Transcript API](https://github.com/jdepoix/youtube-transcript-api) for transcript extraction
- [Hugging Face](https://huggingface.co/) for embedding models
- [Grok AI](https://grok.x.ai) for conversational AI
- [Streamlit](https://streamlit.io/) for the web interface

---


**⭐ If you found this project helpful, please give it a star!**
