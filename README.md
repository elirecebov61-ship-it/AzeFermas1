# AZE Ferma Railway Python deploy

Bu paketdə saytın HTML-i, logo/farm şəkilləri və bütün API-lər `bot.py` faylının içindədir.

## Railway
1. GitHub repoda köhnə Node fayllarını silə bilərsən və bu paketdəki faylları yüklə.
2. Railway-də PostgreSQL əlavə et ki, `DATABASE_URL` avtomatik gəlsin.
3. Variables bölməsində `JWT_SECRET` və `ADMIN_KEY` əlavə et.
4. Deploy et.

`Not Found` problemi üçün `/` route-u birbaşa `bot.py` içindən `index.html` qaytarır.
