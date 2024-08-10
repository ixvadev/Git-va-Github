# Git va GitHub bilan ishlash

## Git nima?
Git — bu Versiya Boshqarish Tizimi (Version Control System, VCS) bo‘lib, dasturiy ta'minotning barcha versiyalarini nazorat qilish, o‘zgarishlarni kuzatish va ularni saqlash imkonini beradi.

### Gitning afzalliklari:
- Kod versiyasini nazorat qilish;
- Qanday o‘zgarishlar kiritilganligi haqida ma’lumot beradi;
- Kiritilgan o‘zgarishlarning kim tomonidan va qachon kiritilganligini ko‘rsatadi;
- Loyihalar bilan jamoaviy ishlash imkoniyatini yaratadi.

## Git va GitHub farqi
- **Git** — Local Version Control System
- **GitHub** — Online Version Control System Hosting Service

### Gitni o'rnatish va sozlash
### O'rnatish:
- **Windows** uchun: Git Bash
- **MacOS** uchun: Terminal, iTerm, Kitty

### Sozlash:
- Git foydalanuvchisi ismi va emailini sozlash:
  ```bash
  git config --global user.name "username"
  git config --global user.email "email"
### Barcha sozlamalarni ko‘rsatish:
    git config --list
### Gitda yangi loyiha yaratish (Repository):
### Yangi git loyihani boshlash:
    git init
### O‘zgarishga uchragan holatni tekshirish:
    git status
### O'zgarishlarni qo'shish va saqlash
### Yangi fayllar va o'zgarishlarni qo‘shish:
    git add faylnomi
    git add .
## Navbatdagi o‘zgarishlarni saqlash:
    git commit -m "xabaringiz"
### Navbatsiz o‘zgarishlarni saqlash:
    git commit --amend -m "xabaringiz"
### Tarixni ko'rish
### Commitlar tarixini ko‘rish:
    git log
### Fayl o'zgarishlarini bekor qilish
### Maxsus fayl yoki barcha fayllarni bekor qilish:
    git checkout -- faylnomi
    git checkout -- .
### Loyihaning xohlagan versiyasiga qaytish:
    git checkout maxsuskod
    git checkout master
    Branch/Merge
### Hozirgi mavjud branchlar ro‘yxatini ko‘rish:
    git branch
### Yangi branch yaratish:
    git branch nom
### Branchga o'tish:
    agit checkout nom
### Branchlarni birlashtirish:
    git merge branchnomi
