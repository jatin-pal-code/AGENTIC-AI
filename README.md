# AGENTIC-AI Project

## Environment Setup

### 1. API Keys Configuration

To protect your API keys from being committed to GitHub:

1. **Copy the example file:**
   ```bash
   cp env.example .env
   ```

2. **Edit the `.env` file** and add your actual API keys:
   ```bash
   # Google Gemini API Configuration
   GEMINI_API_KEY=your_actual_api_key_here
   ```

3. **Never commit the `.env` file** - it's already in `.gitignore`

### 2. Getting Your Gemini API Key

1. Go to [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create a new API key
3. Copy the key to your `.env` file

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## Project Structure

- `1-LangchianBasics/` - LangChain basics and examples
- `main.py` - Main application entry point
- `.env` - Your API keys (not committed to git)
- `env.example` - Template for environment variables

## Security Notes

- ✅ `.env` files are ignored by git
- ✅ API keys are loaded from environment variables
- ✅ Example files don't contain real secrets
- ❌ Never hardcode API keys in your code
