# 🚀 facefacebuck

**facefacebuck** คือเว็บแอปพลิเคชันประเภท Social Network (Facebook Clone) แบบ Full-stack ที่พัฒนาด้วย TypeScript ทั้งในส่วนของ Frontend และ Backend

---

## 🛠️ Tech Stack

### **Frontend (`fakebuck-web`)**

- **Framework:** Next.js (React / TypeScript)
- **Styling:** Tailwind CSS, Shadcn UI / Radix UI
- **Form & Validation:** React Hook Form, Zod

### **Backend (`fakebuck-api`)**

- **Framework:** NestJS (Node.js / TypeScript)
- **Database & ORM:** Prisma ORM
- **Authentication:** JWT (JSON Web Tokens), Passport / Auth Guard

---

## 📁 Project Structure

```text
facefacebuck/
├── fakebuck-api/          # Backend Service (NestJS + Prisma)
│   ├── src/
│   │   ├── auth/          # Authentication module (Login / Register)
│   │   └── ...
│   └── prisma/            # Database schema & migrations
│
└── fakebuck-web/          # Frontend Web App (Next.js)
    ├── src/
    │   ├── app/           # Next.js App Router
    │   ├── components/    # UI Components
    │   └── ...
🚀 Getting Started
Prerequisites
Node.js (v18+)

pnpm / npm / yarn

1. Clone Repository
Bash
git clone [https://github.com/PoohxzycChonlasit/facefacebuck.git](https://github.com/PoohxzycChonlasit/facefacebuck.git)
cd facefacebuck
2. Setup & Run Backend (fakebuck-api)
Bash
cd fakebuck-api
pnpm install
cp .env.example .env
npx prisma db push
pnpm start:dev
3. Setup & Run Frontend (fakebuck-web)
Bash
cd ../fakebuck-web
pnpm install
cp .env.example .env
pnpm dev
✨ Features
🔐 User Authentication: สมัครสมาชิก, เข้าสู่ระบบด้วย JWT

👤 User Profile: จัดการข้อมูลส่วนตัว, อัปโหลดรูปโปรไฟล์และรูปปก

👥 Friend System: ระบบเพิ่มเพื่อน, คำขอเป็นเพื่อน

📱 Responsive Design: รองรับการใช้งานบนทุกขนาดหน้าจอ

📝 License
This project is for educational and portfolio presentation purposes.
```
