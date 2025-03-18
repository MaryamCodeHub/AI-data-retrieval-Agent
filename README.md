# KnowledgeScribe: AI Document Generator for Google Colab

KnowledgeScribe is a Python-based document generation tool that leverages Google's Gemini AI to create comprehensive research documents on any topic.

## 📋 Features
  - Generate detailed, well-structured research documents on any topic
  - Comprehensive document structure with overview, key aspects, history, applications, and future outlook
  - Download generated documents in Markdown format

## 🚀 Usage Instructions
  1. Open Google Colab (https://colab.research.google.com/)
  2. Create a new notebook
  3. Install the required library:
     ```python
     !pip install -q google-generativeai

Copy the entire Python script and paste it into a cell
# Run the document generator function:
    generate_document()

Follow the interactive prompts to:
Enter your Gemini API key
Specify your research topic
Preview and save the generated document

🔑 Obtaining a Gemini API Key
To use this tool, you'll need a Gemini API key:
    Visit Google AI Studio
    Sign in with your Google account
    Navigate to "Get API key" in your settings
    Create a new API key
    Copy the key to use with KnowledgeScribe
  
📝 Document Format
Generated documents follow this structure:

Overview - A brief introduction to the topic
    Key aspects and components
    Historical background or development
    Current state and importance
    Applications or use cases
    Future outlook or trends

⚠️ Important Notes
Your API key is not stored anywhere by the script
The script doesn't send your data anywhere except to the Google Gemini API

📄 License
MIT License


