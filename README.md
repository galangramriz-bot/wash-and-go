# WASH&GO - Platform Layanan Cuci Sepatu

🧼 Platform booking dan tracking layanan cuci sepatu dengan sistem pembayaran online dan admin dashboard.

## 🎯 Fitur Utama

- ✅ **Sistem Booking & Reservasi** - Pesan layanan cuci sepatu dengan mudah
- ✅ **Katalog Layanan** - Lihat berbagai paket dan harga
- ✅ **Customer Profile** - Kelola profil dan riwayat transaksi
- ✅ **Admin Dashboard** - Kelola order, layanan, dan laporan
- ✅ **Payment Gateway** - Pembayaran online yang aman
- ✅ **Tracking Status** - Pantau status cuci sepatu real-time
- ✅ **Geometric Design** - UI/UX modern dengan geometric style
- ✅ **Responsive** - Bekerja di web dan mobile

## 🛠️ Tech Stack

### Frontend
- **Next.js 14+** - React framework dengan SSR
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling dengan geometric design
- **Axios** - HTTP client
- **Redux Toolkit** - State management

### Backend
- **Node.js + Express.js** - REST API
- **TypeScript** - Type safety
- **MySQL** - Database relasional
- **Sequelize** - ORM untuk MySQL
- **JWT** - Authentication
- **Midtrans** - Payment gateway

### Database
- **MySQL 8.0+** - Primary database

## 📁 Project Structure

```
wash-and-go/
├── frontend/                # Next.js Application
│   ├── app/
│   ├── components/
│   ├── lib/
│   ├── styles/
│   ├── public/
│   ├── package.json
│   └── tsconfig.json
├── backend/                 # Node.js Express API
│   ├── src/
│   │   ├── routes/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── middleware/
│   │   ├── services/
│   │   ├── config/
│   │   └── index.ts
│   ├── package.json
│   ├── tsconfig.json
│   └── .env.example
├── database/
│   ├── schema.sql
│   └── migrations/
├── docker-compose.yml
├── .gitignore
└── README.md
```

## 🚀 Cara Memulai

### Prerequisites
- Node.js v18+
- npm atau yarn
- MySQL 8.0+
- Docker & Docker Compose (opsional)

### Installation

1. **Clone Repository**
```bash
git clone https://github.com/galangramriz-bot/wash-and-go.git
cd wash-and-go
```

2. **Setup Backend**
```bash
cd backend
npm install
cp .env.example .env
# Edit .env dengan konfigurasi database Anda
npm run dev
```

3. **Setup Frontend**
```bash
cd frontend
npm install
cp .env.local.example .env.local
# Edit .env.local dengan API URL
npm run dev
```

4. **Buka Browser**
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000

## 🐳 Docker Setup (Opsional)

```bash
docker-compose up -d
```

## 📖 API Documentation

API documentation tersedia di `/api/docs` setelah backend running.

## 🔐 Environment Variables

### Backend (.env)
```
NODE_ENV=development
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=password
DB_NAME=washgo_db
JWT_SECRET=your_jwt_secret
MIDTRANS_SERVER_KEY=your_midtrans_key
```

### Frontend (.env.local)
```
NEXT_PUBLIC_API_URL=http://localhost:5000/api
NEXT_PUBLIC_APP_NAME=WASH&GO
```

## 📱 Platform Support

- ✅ Web (Desktop & Mobile)
- ✅ Progressive Web App (PWA)
- 🔄 Mobile App (React Native - coming soon)

## 👨‍💼 Author

**M. Galang Rambu Rizqi**

## 📄 License

MIT License - feel free to use this project

---

**Build with ❤️ for WASH&GO Platform**
