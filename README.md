# Restaurant Review Website

## รายละเอียดโปรเจค
โปรเจคเว็บไซต์์ที่ไว้ใช้สำหรับดู และรีวืวร้านอาหารต่างๆ

## เทคโนโลยีที่ใช้
- Frontend: React 18 + Vite
- Backend: Node.js + Express
- Database: JSON File Storage

## Features ที่ทำได้
### Required Features (70 คะแนน)
- [x] แสดงรายการร้านอาหาร
- [x] ค้นหาร้าน
- [x] กรองตามหมวด/rating/ราคา
- [x] ดูรายละเอียดร้าน
- [x] เพิ่มรีวิว
- [x] Validation
- [x] อัพเดท rating อัตโนมัติ

### Bonus Features (ถ้ามี)
- [x] Sort restaurants
- [x] Responsive design
- [x] Animations

## วิธีติดตั้งและรัน

### Backend
\`\`\`bash
cd backend
npm install
cp .env.example .env
npm run dev
\`\`\`

### Frontend
\`\`\`bash
cd frontend
npm install
npm run dev
\`\`\`

## API Endpoints
- GET `/api/restaurants` - ดึงรายการร้านทั้งหมด
- GET `/api/restaurants/:id` - ดึงร้านตาม ID
- POST `/api/reviews` - เพิ่มรีวิว
- GET `/api/stats` - ดึงสถิติ

## Screenshots
### หน้าแรก
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/4ea34ad9-c43d-47ea-82ed-54e88a3036fe" />


### รายละเอียดร้าน
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/2c577bc4-36bc-4cf1-b9d0-2124a4cd1e2b" />


### ฟอร์มรีวิว
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/f226cf5a-bf3c-4ee5-8b3a-1047df45a1f2" />


## ผู้พัฒนา
- ปวริศ คูณศรี
- 67543210037-7
- pawaris_ko67@live.rmutl.ac.th

## License
MIT License
