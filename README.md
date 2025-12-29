
> Steps to run code locally:
     **Prerequisites:**  Node.js
     1. Install dependencies:
     `npm install`
     2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
     3. Run the app:
     `npm run dev`

> Tech Stack:
    1. Node.js + TypeScript
    2. Vite
    3. React
    4. Gemini API

Project Structure:
.
├── components/       # React components
├── services/         # API service files
├── index.tsx         # Entry point
├── App.tsx           # Main app component
├── package.json      # Dependencies
├── tsconfig.json     # TypeScript config
├── vite.config.ts    # Vite config
└── .env.local        # Environment variables (not committed)
