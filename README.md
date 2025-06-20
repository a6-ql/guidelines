# Chat Application User Manual

## Table of Contents
1. [Installation Guide](#installation-guide)
2. [System Requirements](#system-requirements)
3. [Getting Started](#getting-started)
4. [Features and Usage](#features-and-usage)
5. [Troubleshooting](#troubleshooting)

## Installation Guide

### Prerequisites
Before installing the application, ensure you have the following installed:
- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)
@back-end
- Python (v3.8 or higher)
- pip (Python package manager)
@AI
- openai
- pinecone-client
- tqdm
- numpy
- pandas
- scikit-learn
- sentence-transformers
- requests
- python-dotenv
- google-generativeai


### Backend Setup
@back-end
Backend setup instructions will be added later.
### RAG pipeline Setup
Follow the steps below to set up and run the RAG-based chatbot:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/TareKelKhateb/InstaBot.git
   cd InstaBot
   ```

2. **Create a `.env` File**

   In the root directory, create a `.env` file and add your API keys:
   ```env
   PINECONE_API_KEY=your_pinecone_api_key
   GEMINI_API_KEY=your_gemini_api_key
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**
   ```bash
   python main.py
   ```
### Frontend Setup
```bash
cd frontend #Navigate to the frontend directory
npm install #Install Node.js dependencies
npm start   #Start the development server
```
The frontend application will run on http://localhost:5173

## System Requirements

### Minimum Requirements
- Operating System: Windows 10/11, macOS 10.15+, or Linux
- RAM: 4GB minimum
- Storage: 1GB free space
- Internet connection for API calls

### Recommended Requirements
- RAM: 8GB or higher
- Storage: 2GB free space
- High-speed internet connection
- 6 VRAM GPU

## Getting Started

1. After installation, open your web browser and navigate to http://localhost:5173/
2. You'll be presented with the login page
3. Enter your credentials to access the application
4. Upon successful login, you'll be redirected to the main dashboard

## Features and Usage

### Conversation List
- View all your conversations in a paginated list
- Each conversation shows:
  - Summary of the conversation
  - Sentiment analysis
  - Date and time
- Click on any summary to view the full conversation details
- Use the pagination controls to navigate through multiple pages

### Sentiment Analysis
The application provides sentiment analysis for each conversation:
- Positive (Green badge)
- Negative (Red badge)
- Neutral (Yellow badge)
- None (Gray badge)

### Navigation
- Use the navigation bar at the top to access different sections
- The current page is highlighted in the navigation menu

## Troubleshooting

### Common Issues and Solutions

1. **Backend Server Not Starting**
@back-end
Backend troubleshooting details will be added later.

2. **Frontend Not Loading**
   - Ensure Node.js and npm are properly installed
   - Check if all dependencies are installed
   - Verify port 3000 is available

3. **API Connection Issues**
@back-end
API connection troubleshooting details will be added later.

### Getting Help
If you encounter any issues not covered in this manual:
1. Check the error messages in the browser console
2. Review the server logs
3. Contact the support team at [support@example.com]

## Support
For additional support or to report issues:
- Email: support@example.com
- Issue Tracker: [GitHub Issues Page]
- Documentation: [Documentation Link]

---

*Last Updated: [Current Date]*
