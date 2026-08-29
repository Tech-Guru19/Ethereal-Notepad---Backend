# Ethereal Notepad - Backend API

## Overview

The Express and MongoDB backend for Ethereal Notepad. The API handles note storage, user data management, media uploads through Cloudinary, and transactional email delivery.

## Key Features

- **MongoDB storage:** Schema-driven data persistence with Mongoose
- **Media upload pipeline:** Multer receives images, converts them to base64, uploads to Cloudinary, and returns secure URLs
- **Email automation:** Nodemailer and Resend for OTP and notification delivery
- **Secure configuration:** CORS and environment-variable-based configuration

## Technology Stack

- Node.js with Express 5
- MongoDB with Mongoose 9
- Multer (file uploads)
- Cloudinary (media storage)
- Nodemailer and Resend (email)

## Getting Started

### Prerequisites

- Node.js (v18 or later)
- MongoDB instance
- Cloudinary account

### Installation

```bash
git clone https://github.com/Tech-Guru19/Ethereal-Notepad---Backend.git
cd Ethereal-Notepad---Backend
npm install
# Create a .env file with: PORT, URI (MongoDB), cloudName, cloudApiKey, cloudApiSecret
npm start
```

## API Endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| POST | /uploadMedia | Upload an image and return a Cloudinary URL |

## Author

[Obiasogu Esther Chizaram](https://github.com/Tech-Guru19)
