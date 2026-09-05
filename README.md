# Portfolio Assistant API

A secure serverless API for **Kiệt Assistant** — an AI-powered guide embedded in my personal portfolio.

## Purpose

The assistant helps visitors learn about:

- My background and current learning journey
- Featured projects
- Technologies used in my portfolio
- Contact information

## Architecture

```text
GitHub Pages portfolio
        ↓
Vercel Serverless API
        ↓
OpenAI Responses API
```

## Security

- API keys are stored only in Vercel Environment Variables.
- No API key is committed to this repository.
- Requests are restricted to my portfolio website origin.
- The assistant only answers using predefined portfolio information.
- Conversation history is limited to recent messages.

## Tech Stack

- JavaScript
- Node.js
- Vercel Serverless Functions
- OpenAI Responses API

## Local Environment Variables

```text
OPENAI_API_KEY=your_secret_key
OPENAI_MODEL=gpt-5-mini
```

> Never commit a `.env` file or expose an API key in browser code.

## Author

**Trương Gia Kiệt**  
Portfolio: [jiaystm17.github.io/Personal-portfolio](https://jiaystm17.github.io/Personal-portfolio/)  
GitHub: [@JiaysTM17](https://github.com/JiaysTM17)
