# DualMind-AI

# Gemini LLM Q&A Application

A Streamlit-based application that integrates with Google's Gemini Pro generative AI model for generating text and analyzing images. The app provides an interactive interface for users to input queries and receive real-time responses powered by Google's generative AI.

---

## Features

- **Interactive Text-Based Q&A**: Ask questions and receive responses in real-time using the Gemini LLM.
- **Image Analysis**: Upload images for AI-powered insights with optional text prompts.
- **Chat History**: View a session's conversation history for improved usability.
- **Streamed Responses**: Get results as the model processes your query.

---

## Technologies Used

- **Python**: Core programming language.
- **Streamlit**: Web framework for the interactive user interface.
- **Google Generative AI**: Provides the Gemini LLM for natural language and image processing.
- **dotenv**: For managing environment variables securely.
- **Pillow**: For handling uploaded image files.

---

## Prerequisites

- Python 3.8 or above
- A valid Google API Key for Gemini Pro (set in `.env` file as `GOOGLE_API_KEY`).

---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repo-name.git
   cd repo-name
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up your `.env` file:
   - Create a file named `.env` in the root directory.
   - Add your Google API key:
     ```env
     GOOGLE_API_KEY=your_api_key_here
     ```

5. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## Usage

1. Open the app in your browser (usually at `http://localhost:8501`).
2. Input your question or upload an image to analyze.
3. View AI-generated responses in real-time.

---

## Directory Structure

```
repo-name/
├── app.py               # Main application file
├── .env                 # Environment variables
├── requirements.txt     # List of dependencies
├── README.md            # Project documentation
├── .gitignore           # Ignored files for version control
```

---

## Sample `.env` File

```env
GOOGLE_API_KEY=your_api_key_here
```

---

## Future Enhancements

- Add support for multi-language queries.
- Improve the UI/UX for better accessibility.
- Integrate additional models or APIs for extended functionality.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contributors

- [Bhuvanyu Geel](https://github.com/bhuvanyu09)

---
