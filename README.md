# SplitShot — Crew Bill Splitter

## Deploy บน Vercel (5 นาที)

### ขั้นตอน

**1. ติดตั้ง Node.js**
ดาวน์โหลดที่ https://nodejs.org (เลือก LTS)

**2. สร้าง GitHub repo**
- ไปที่ github.com → New repository
- ชื่อ: `splitshot`
- Public หรือ Private ก็ได้

**3. อัปโหลดไฟล์**
```bash
# เปิด Terminal แล้วรันคำสั่งนี้
cd splitshot-project
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/USERNAME/splitshot.git
git push -u origin main
```

**4. Deploy บน Vercel**
- ไปที่ vercel.com → Sign up ด้วย GitHub
- กด "Add New Project"
- เลือก repo `splitshot`
- Framework Preset: **Vite**
- กด Deploy → รอ 1 นาที ✅

**5. ได้ URL แบบ** `splitshot.vercel.app` แชร์ได้เลย!

---

## ติดตั้งเป็น PWA บนมือถือ

### iPhone (iOS Safari)
1. เปิดลิงก์ใน **Safari** (ต้องเป็น Safari เท่านั้น)
2. กดปุ่ม Share (กล่องลูกศรขึ้น)
3. เลือก **"Add to Home Screen"**
4. กด Add → มี icon บนหน้าจอเลย 📱

### Android (Chrome)
1. เปิดลิงก์ใน Chrome
2. จะมีป๊อปอัพ "Install App" ขึ้นมาอัตโนมัติ
3. กด Install ได้เลย

---

## Run ในเครื่องตัวเอง

```bash
npm install
npm run dev
```
เปิด http://localhost:5173

---

## Build

```bash
npm run build
```

---

## Custom Domain (ถ้าอยากได้ domain ชื่อตัวเอง)

1. ซื้อ domain ที่ namecheap.com หรือ godaddy.com
2. ใน Vercel → Project Settings → Domains
3. เพิ่ม domain แล้วทำตามขั้นตอน DNS
