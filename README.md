# Mina Bibliotek Client

A lightweight Node.js + React client that lets you securely log in to [minabibliotek.se](https://minabibliotek.se) and view your current library loans.

## ✨ Features
- Login with library card or personal number + PIN  
- Fetches and displays your borrowed books  
- Works with both React Web
- Uses a small Express proxy to handle authentication safely  

## ⚙️ Tech Stack
- **Backend:** Node.js, Express, Axios, Tough-Cookie, Cheerio  
- **Frontend:** React
- **Language:** JavaScript / ES Modules  

## 🚀 Getting Started

```bash
git clone https://github.com/YOURUSERNAME/mina-bibliotek-client.git
cd mina-bibliotek-client
npm install
npm run dev
```

Create an `.env` file:

```env
PORT=3000
```

Then visit [http://localhost:3000](http://localhost:3000).

## 🛡️ Security
- Credentials never stored or logged.
- All communication via HTTPS.
- Keep your `.env` and cookies private.

## 🧩 Repository Info
**Repository name:** `mina-bibliotek-client`  
**Description:** A lightweight web client for fetching and displaying your borrowed books from [minabibliotek.se](https://minabibliotek.se), built with Node.js and React. Includes a secure backend proxy that handles login and data scraping.  
**Keywords:** javascript, react, nodejs, express, cheerio, axios, web-scraping, library-app, sweden, mina-bibliotek, open-data  

## 🧱 Project Structure

```
mina-bibliotek-client/
├── README.md
├── LICENSE
├── package.json
├── server/
│   ├── index.ts
│   └── parseLoans.ts
├── client/
│   ├── src/
│   │   └── App.tsx
│   └── vite.config.ts
└── .env.example
```

## 🤝 Contributing
Pull requests and issue reports are welcome! Please open an issue before major changes.

## 📋 License
MIT — feel free to fork and contribute.
