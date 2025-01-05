# Phidata Multimodal Video Summarizer Using AI Agents 🎥

A powerful video analysis tool that leverages Gemini 2.0 Flash Exp and Phidata to provide intelligent insights from video content. This application can analyze videos and answer specific queries about their content using advanced AI capabilities.

## Features

- 🎥 Upload and analyze video files (MP4, MOV, AVI)
- 🤖 Powered by Google's Gemini 2.0 Flash Exp model
- 🔍 Context-aware video analysis using DuckDuckGo integration
- 💡 Natural language query interface
- 📊 Detailed insights and analysis results

## Requirements

- Python 3.8+
- Streamlit
- Phidata
- Google Generative AI
- Other dependencies listed in `requirements.txt`

## Setup

1. Clone the repository:
```bash
git clone https://github.com/Omadithya07/Phidata-Multimodal-Video-Summarizer-Using-AI-Agents.git
cd Phidata-Multimodal-Video-Summarizer-Using-AI-Agents
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the root directory and add your Google API key:
```env
GOOGLE_API_KEY=your_api_key_here
```

4. Run the application:
```bash
streamlit run app.py
```

## Usage

1. Open the application in your web browser
2. Upload a video file using the file uploader
3. Enter your question or specify what insights you're looking for
4. Click "Analyze Video" to process and receive AI-generated insights
5. Review the detailed analysis provided by the AI agent

## Features in Detail

- **Video Processing**: Supports multiple video formats and provides real-time processing status
- **AI Analysis**: Uses Gemini 2.0 Flash Exp for advanced video understanding
- **Web Research Integration**: Enhances analysis with additional context from DuckDuckGo searches
- **User-Friendly Interface**: Clean and intuitive Streamlit-based UI
- **Error Handling**: Robust error management and user feedback
- **Temporary File Management**: Secure handling of uploaded videos

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


## Acknowledgments

- Built with [Phidata](https://github.com/phidata-public/phidata)
- Powered by Google's Gemini 2.0 Flash Exp
- Uses Streamlit for the frontend interface

## Note

Remember to keep your API keys confidential and never commit them to the repository. Always use environment variables for sensitive information.
