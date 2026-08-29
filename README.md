# ⚙️ Ethereal Notepad — Backend API

The **Express + MongoDB backend** for Ethereal Notepad. Handles note storage, user data, media uploads (via Cloudinary), and transactional email.

## ✨ Highlights

- 🗄️ **MongoDB with Mongoose** — flexible, schema-driven data storage
- 🖼️ **Media upload pipeline** — Multer receives images → converted to base64 → uploaded to **Cloudinary** → secure URL returned
- 📧 **Email automation** — Nodemailer + Resend for OTPs and notifications
- 🔒 **CORS + env-based configuration** — clean, secure setup

## 🧱 Tech Stack

- Node.js + Express 5
- MongoDB + Mongoose 9
- Multer
- Cloudinary
- Nodemailer & Resend

## 🚀 Getting Started

```bash
git clone https://github.com/Tech-Guru19/Ethereal-Notepad---Backend.git
cd Ethereal-Notepad---Backend
npm install
# create .env with: PORT, URI (MongoDB), cloudName, cloudApiKey, cloudApiSecret
npm start
```

## 🔌 Key Endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| POST | `/uploadMedia` | Upload an image → returns Cloudinary URL |

## 👩‍💻 Author

**[Obiasogu Esther Chizaram](https://github.com/Tech-Guru19)**
