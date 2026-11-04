# shamaa-backende

## Git setup and first push

```bash
# 1. الدخول إلى مجلد المشروع
cd shamaa-backend

# 2. تهيئة نظام Git
git init

# 3. إضافة جميع الملفات الجديدة للتتبع
git add .

# 4. توثيق هذه الإضافة كأول التزام (Commit)
git commit -m "feat: Initial commit for Shamaa FastAPI Backend with Clean Architecture"

# 5. تسمية الفرع الرئيسي بـ main
git branch -M main

# 6. ربط الكود بمستودعك السحابي (استبدل USERNAME باسم مستخدم GitHub الخاص بك)
git remote add origin https://github.com/USERNAME/shamaa-backend.git

# 7. رفع الكود إلى المستودع السحابي
git push -u origin main
```