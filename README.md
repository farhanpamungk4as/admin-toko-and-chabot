# Test Projects - Admin Toko & AI Chatbot

Repository ini berisi 2 proyek test:

1. **Admin Toko** - Sistem admin page untuk manajemen pembelian
2. **AI Chatbot** - Chatbot dengan integrasi multi-provider AI

## 📁 Struktur Repository

```
test-projects/
├── admin-toko/
│   ├── app.js
│   ├── package.json
│   ├── views/
│   │   ├── layout.ejs
│   │   ├── dashboard.ejs
│   │   ├── produk.ejs
│   │   ├── pembelian.ejs
│   │   └── tambah-pembelian.ejs
│   └── README.md
├── chatbot-ai/
│   ├── index.html
│   └── README.md
└── README.md (file ini)
```

## 🚀 Quick Start

### Proyek 1: Admin Toko

```bash
# Masuk ke folder proyek
cd admin-toko

# Install dependencies
npm install

# Jalankan aplikasi
npm start

# Akses di browser
http://localhost:3000
```

### Proyek 2: AI Chatbot

```bash
# Masuk ke folder proyek
cd chatbot-ai

# Buka langsung di browser
# Atau gunakan local server
python -m http.server 8000

# Akses di browser
http://localhost:8000
```

## 📋 Requirements

### Admin Toko
- Node.js v14 atau lebih tinggi
- npm atau yarn

### AI Chatbot
- Web browser modern (Chrome, Firefox, Safari, Edge)
- API Key dari provider AI yang dipilih (kecuali Ollama)

## 🛠️ Teknologi

### Admin Toko
- Node.js & Express.js
- EJS (Template Engine)
- SQLite3 (Database)
- HTML/CSS (UI)

### AI Chatbot
- HTML5
- CSS3
- Vanilla JavaScript
- Integration dengan OpenAI, DeepSeek, Gemini, Ollama

## 📝 Fitur Utama

### Admin Toko
✅ Dashboard dengan statistik  
✅ Manajemen produk dan stock  
✅ Input pembelian baru  
✅ Pembatalan pembelian  
✅ Update stock otomatis  

### AI Chatbot
✅ Multi-provider AI support  
✅ UI modern dan responsif  
✅ Konfigurasi mudah  
✅ Quick action buttons  
✅ Typing indicator  

## 🔧 Konfigurasi

### Admin Toko
- Port default: 3000
- Database: SQLite (auto-create)
- 10 produk sample otomatis

### AI Chatbot
- Konfigurasi melalui UI settings
- API key disimpan di localStorage
- Support 4 AI providers

## 📸 Screenshots

### Admin Toko - Dashboard
![Dashboard](https://via.placeholder.com/800x400?text=Admin+Toko+Dashboard)

### AI Chatbot - Interface
![Chatbot](https://via.placeholder.com/800x400?text=AI+Chatbot+Interface)

## 👤 Author

[Your Name]

## 📄 License

ISC

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## ⚠️ Catatan Penting

1. **Admin Toko**: Database akan dibuat otomatis saat pertama kali dijalankan
2. **AI Chatbot**: Jangan lupa mengatur API Key sebelum menggunakan (kecuali Ollama)

## 📞 Support

Jika ada pertanyaan atau masalah, silakan buat issue di repository ini.