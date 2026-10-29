# Кейіпкерлер аквариумы — орнату

## 1. Firebase
1. https://console.firebase.google.com → Add project (Analytics керек емес).
2. Build → Firestore Database → Create database (Production mode, жақын аймақ).
3. Firestore → Rules → `firestore.rules` мазмұнын қойып, Publish.
4. Project settings (⚙) → Your apps → Web (</>) → тіркеп, `firebaseConfig` мәндерін көшір.
5. `index.html` ішіндегі `firebaseConfig` ішіне қой («ЖАЗ» орнына).

## 2. GitHub Pages
1. github.com → New repository (Public), `index.html` жүкте.
2. Settings → Pages → Branch: main / root → Save.
3. Бірнеше минуттан кейін сайт: https://<логин>.github.io/<репозиторий>/

## 3. Қолдану
- Ұстаз тақтасы: `.../?room=7a#teacher` (суретті басып өшіруге болады, «Тазарту» түймесі бар)
- Тақта (көрсету): `.../?room=7a`
- Оқушыларға: `.../?room=7a#upload`
- `room=` кодын әр сыныпқа өзгерт, галереялар араласпайды.
