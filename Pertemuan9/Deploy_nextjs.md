# Deploy web apps framework next.js ke aws

1. pastikan web apps berjalan di lokal
- install dependensi -> npm install
- create db dan import sql
- create file .env dan isi sesuaikan dengan db local
- jalankan web apps -> npm run dev
- akses web apps di browser http://localhost:3000
- Testing Front Pastikan tampilan muncul dan tanpa Error
- testing Back end http://localhost:3000/admin username: admin password: admin123

![alt text](image.png)

- Create static File -> npm run build
- Archive folder standalone -> zip -> klik kanan folder standalone -> send to -> compressed -(zipped) folder

2. proses deploy file ke AWS
- nyalakan instance AWS
- Connect open SSH
- Connect Filezilla
![alt text](image-1.png)