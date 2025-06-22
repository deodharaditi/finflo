# Personal Finance Advisor

A simple AI-powered personal finance advisor with both terminal and web interfaces.

## Features

- Natural language interface for financial queries
- Check account balances (mock data)
- Analyze spending patterns
- Get investment recommendations
- Web interface using Streamlit
- Terminal interface for CLI lovers

## Setup

1. Create a virtual environment (recommended):
```bash
python -m venv venv
# On Windows:
.\venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up your environment variables:
   ```bash
   # Copy the example file
   cp .env.example .env
   
   # Edit the .env file with your actual API keys
   # (Use a text editor to open .env and replace the placeholder values)
   ```
   
   You'll need to get an API key from [OpenAI](https://platform.openai.com/api-keys).
   Optionally, you can also get a [Perplexity API key](https://www.perplexity.ai/) for enhanced features.

## Running the Application

### Terminal Version
```bash
python finance_advisor.py
```

### Web Interface (Streamlit)
```bash
streamlit run app.py
```
Then open your browser to the URL shown in the terminal (usually http://localhost:8501)

## Example Questions

- "What's my current bank balance?"
- "Analyze my spending for the last month"
- "Suggest investments for medium risk tolerance"

## Note

This is a demo application using mock data. For real financial data, you would need to integrate with actual banking APIs.
