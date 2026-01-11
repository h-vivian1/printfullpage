# PrintFullPage

A "Vibe Coder" Fullstack application for capturing full-page screenshots of websites.

## 🚀 Features

- **Full Page Capture**: Uses Puppeteer to scroll and capture entire webpages.
- **Multiple Formats**: Support for `.png`, `.webp`, and `.pdf`.
- **Cyberpunk Aesthetic**: "Vibe Tech" UI with animated backgrounds and glassmorphism.
- **Local Storage**: Saves captures directly to `server/downloads/PRINTEDPAGES`.

## 🛠️ Stack

- **Frontend**: React, TypeScript, Vite, Lucide React.
- **Backend**: Node.js, Express, Puppeteer.

## 📦 Installation & Usage

1. **Backend**:
   ```bash
   cd server
   npm install
   node index.js
   ```
   Server runs on `http://localhost:3001`.

2. **Frontend**:
   ```bash
   cd client
   npm install
   npm run dev
   ```
   Client runs on `http://localhost:5173` (by default).

3. **Usage**:
   - Open the frontend.
   - Paste links (one per line).
   - Select format.
   - Click "Processar Capturas".
