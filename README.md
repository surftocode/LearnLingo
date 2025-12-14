# LearnLingo React ve NodeJS kullanarak öğretmenleri ve öğrencileri buluşturan, öğrendilerin öğretmenlerin yetkin oldukları alan hakkında bilgi alabildiği ve istediklerini favorilerine ekleyebildiği, öğretmen ve öğrencileri buluşturan bir site.


NEDEN BÖYLE BİR PROJE YAPTIK?
Hangi problemi çözüyor?

Neden bu projeyi yaptın?

Alternatiflerden farkı ne?



FEATURES
Kullanıcılar Google hesaparı ile login ya da register olabilirler.
Güvenli yetkilendirme
Öğretmen arama
Favori listesi
Favori listesini yönetebilme
Pagination


TECH STACK
Frontend: React, Tailwind
Backend: Node.js, Express,Google OAuth login,JWT authntication
Database: MongoDB
Auth: Google OAuth, JWT

## Project Structure
LearnLingo/
├── client/  # React frontend
└── server/  # Node.js backend


SETUP
## Prerequisites
- Node.js (v18+)
- npm 
- MongoDB Atlas



---

### 1. Clone the repository

 bash
git clone https://github.com/surftocode/LearnLingo.git)
cd LearnLingo

START BACKEND
cd server
npm install

START FRONTEND
cd client
npm install


md 
`server` dosyasında bir `.env` dosyası oluşturun:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
GOOGLE_CALLBACK_URL=http://localhost:5000/auth/google/callback



START BACKEND
cd server
npm start
http://localhost:5000

START FRONTEND
cd client
npm run dev
http://localhost:5173









