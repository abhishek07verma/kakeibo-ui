# Kakeibo UI

Web front-end for Kakeibo — a Japanese-inspired household budgeting and conscious spending application.

## Tech Stack

- **Runtime / Framework**: [React](https://react.dev/) (v18)
- **Bundler / Dev Server**: [Vite](https://vitejs.dev/)

## Project Structure

```
kakeibo-ui/
├── index.html
├── package.json
├── vite.config.js
├── .env.example
├── public/
└── src/
    ├── assets/
    ├── components/
    ├── pages/
    ├── services/
    ├── App.jsx
    ├── App.css
    ├── index.css
    └── main.jsx
```

## Getting Started

### 1. Install Dependencies
```bash
npm install
```

### 2. Environment Configuration
Copy `.env.example` to `.env`:
```bash
cp .env.example .env
```

### 3. Start Development Server
```bash
npm run dev
```

The application will be accessible at `http://localhost:3000`.

### 4. Build for Production
```bash
npm run build
```
