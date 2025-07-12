# ✅ คู่มือฉบับสมบูรณ์: วิธีทำ Commit มากกว่า 10 ครั้งใน GitHub ก่อนวันที่ 1 กรกฎาคม เพื่อเข้าร่วม Zama Developer Program

คู่มือนี้จะช่วยให้เพื่อนๆสามารถทำ **15 commits ใน GitHub** ได้ภายในวันเดียว โดยใช้ **GitHub Codespaces** ได้ง่ายๆ ซึ่ง Codespace จะไม่ได้เกี่ยวข้องกับหรือยุ่งเกี่ยวกับคอมเรา ทำให้ปลอดภัยมากขึ้น พร้อมสำหรับเข้าร่วม  Developer Program

---

## 🛠️ ขั้นตอนการทำงานแบบ Step-by-Step

### 1️⃣ สร้าง Repository ใหม่

- ไปที่: [https://github.com/new](https://github.com/new)
- ตั้งชื่อว่า `zama-commit` หรืออะไรก็ได้
- ตั้งค่าเป็น Public
- ✅ ติ๊ก "Add a README file"
- คลิก **Create repository**

---

### 2️⃣ เปิด GitHub Codespaces

- เข้าไปที่ Repository ที่เราพึ่งสร้างใหม่
- กดปุ่มสีเขียว `<> Code`
- เลือก `Open with Codespaces` → `+ Create Codespace on Main`
- รอโหลด (~20 วินาที)

---

### 3️⃣ เปิด Terminal ใน Codespace

- กด `Ctrl + \`` หรือเลือกเมนู `Terminal` → `New Terminal`

---

### 4️⃣ วางคำสั่งทั้งหมดใน Terminal

คัดลอกและวางคำสั่งชุดนี้ทีเดียว โดยคำสั่งนี้จะมีระบุเวลาการ Commit ซึ่งผมตั้งไว้ให้แล้วว่าก่อนวันที่ 1 July ตามเกนท์ของทาง Zama เพื่อนๆสามารถปรับเปลี่ยนวันเองได้และเพิ่มจำนวน Commit ตามต้องการได้ครับ:

```bash
echo "Commit 1 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-02T10:12:17" GIT_COMMITTER_DATE="2025-06-02T10:12:17" git commit -m "Commit 1"

echo "Commit 2 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-04T14:43:02" GIT_COMMITTER_DATE="2025-06-04T14:43:02" git commit -m "Commit 2"

echo "Commit 3 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-06T08:25:39" GIT_COMMITTER_DATE="2025-06-06T08:25:39" git commit -m "Commit 3"

echo "Commit 4 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-08T19:17:11" GIT_COMMITTER_DATE="2025-06-08T19:17:11" git commit -m "Commit 4"

echo "Commit 5 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-10T13:55:46" GIT_COMMITTER_DATE="2025-06-10T13:55:46" git commit -m "Commit 5"

echo "Commit 6 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-12T16:38:29" GIT_COMMITTER_DATE="2025-06-12T16:38:29" git commit -m "Commit 6"

echo "Commit 7 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-14T09:05:03" GIT_COMMITTER_DATE="2025-06-14T09:05:03" git commit -m "Commit 7"

echo "Commit 8 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-17T20:20:57" GIT_COMMITTER_DATE="2025-06-17T20:20:57" git commit -m "Commit 8"

echo "Commit 9 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-18T11:48:21" GIT_COMMITTER_DATE="2025-06-18T11:48:21" git commit -m "Commit 9"

echo "Commit 10 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-20T17:35:40" GIT_COMMITTER_DATE="2025-06-20T17:35:40" git commit -m "Commit 10"

echo "Commit 11 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-22T07:19:10" GIT_COMMITTER_DATE="2025-06-22T07:19:10" git commit -m "Commit 11"

echo "Commit 12 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-24T22:27:58" GIT_COMMITTER_DATE="2025-06-24T22:27:58" git commit -m "Commit 12"

echo "Commit 13 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-26T12:06:44" GIT_COMMITTER_DATE="2025-06-26T12:06:44" git commit -m "Commit 13"

echo "Commit 14 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-28T18:42:33" GIT_COMMITTER_DATE="2025-06-28T18:42:33" git commit -m "Commit 14"

echo "Commit 15 line" >> README.md
git add README.md
GIT_AUTHOR_DATE="2025-06-30T23:55:51" GIT_COMMITTER_DATE="2025-06-30T23:55:51" git commit -m "Commit 15"
```

5️⃣ ส่ง Commit ขึ้น GitHub ด้วย git push
เมื่อทำ Commit ครบทั้ง 15 ครั้งแล้ว ขั้นตอนสุดท้ายคือการส่งขึ้น GitHub ด้วยคำสั่งนี้:

```bash
git push
```
- ปกติจะ push ขึ้นทันที หรือรอประมาณ ไม่เกิน 10 นาที
- เปิดหน้า GitHub Profile (เช่น github.com/yourusername)
- ✅ จะเห็น Commit ทั้งหมดแสดงบน Timeline เป็นอันเสร็จ โดยให้กลับไปที่ : [https://guild.xyz/zama/developer-program](https://guild.xyz/zama/developer-program) แล้วรอซักพักว่า Verify แล้วรียัง
