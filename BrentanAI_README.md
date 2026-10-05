# Brentan.ai V2

## Run on your computer

1. Install Node.js LTS.
2. Copy `.env.example` and rename the copy to `.env`.
3. Put your OpenAI API key in `.env`.
4. Open a terminal in this folder.
5. Run:

```bash
npm install
npm start
```

6. Open http://localhost:3000

If your API account does not have access to `gpt-6-astra`, change `OPENAI_MODEL` in `.env` to a model your account can use.

Never publish your `.env` file or expose your API key in browser code.
