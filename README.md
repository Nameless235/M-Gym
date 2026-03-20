# 🏋️ M GYM Cilebut - Website Booking

Website booking untuk M GYM Cilebut dengan sistem booking sesi gym, personal trainer, dan membership.

## 🚀 Cara Upload ke GitHub dan Aktifkan Website

### 1️⃣ Buat Repository Baru di GitHub

1. Buka [GitHub](https://github.com) dan login
2. Klik tombol **"+"** di kanan atas → pilih **"New repository"**
3. Isi nama repository, misalnya: `mgym-booking`
4. **PENTING:** Centang **"Add a README file"** agar repo langsung punya branch main
5. Klik **"Create repository"**

### 2️⃣ Upload File ke GitHub

**Cara 1: Via Web (Paling Mudah)**

1. Di repository yang baru dibuat, klik **"Add file"** → **"Upload files"**
2. Drag & drop semua file ini:
   - `index.html`
   - `manifest.json`
3. Scroll ke bawah, tulis commit message: "Initial commit - M GYM website"
4. Klik **"Commit changes"**

**Cara 2: Via Git CLI (Jika sudah familiar dengan Git)**

```bash
git clone https://github.com/USERNAME/mgym-booking.git
cd mgym-booking
# Copy semua file ke folder ini
git add .
git commit -m "Initial commit - M GYM website"
git push origin main
```

### 3️⃣ Aktifkan GitHub Pages

1. Di repository, klik tab **"Settings"**
2. Scroll ke bawah, cari menu **"Pages"** di sidebar kiri
3. Di bagian **"Source"**, pilih:
   - Branch: **main**
   - Folder: **/ (root)**
4. Klik **"Save"**
5. Tunggu 1-2 menit, GitHub akan otomatis deploy website kamu

### 4️⃣ Akses Website

Setelah deploy selesai, website kamu akan bisa diakses di:

```
https://USERNAME.github.io/mgym-booking/
```

Ganti `USERNAME` dengan username GitHub kamu.

**Contoh:**
- Username GitHub: `adamgym123`
- URL website: `https://adamgym123.github.io/mgym-booking/`

## 📱 Fitur Website

✅ Booking sesi gym reguler  
✅ Booking personal trainer  
✅ Membership/langganan bulanan  
✅ Sistem slot waktu otomatis  
✅ Konfirmasi via WhatsApp  
✅ Responsive untuk mobile & desktop  
✅ PWA-ready (bisa di-install seperti app)  

## 🔧 Custom Domain (Opsional)

Kalau kamu punya domain sendiri (misalnya `mgym-cilebut.com`), kamu bisa:

1. Di Settings → Pages, masukkan domain kamu di bagian **"Custom domain"**
2. Di provider domain kamu, tambahkan DNS records:
   - Type: `CNAME`
   - Name: `www` (atau `@` untuk root domain)
   - Value: `USERNAME.github.io`

## 💡 Tips

- Setiap kali ada perubahan, upload file yang diupdate ke GitHub
- GitHub Pages akan otomatis update dalam 1-2 menit
- Website ini fully client-side, data disimpan di localStorage browser
- Untuk production, pertimbangkan pakai backend untuk booking real-time

## 📞 Kontak Gym

Nomor WhatsApp untuk konfirmasi booking: **+62 858-1480-0499**

---

**Dibuat untuk M GYM Cilebut** 💪
