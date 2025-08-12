# Mobile Automation - Appium DEMO App

Projek ini berisi automation testing untuk **API Demos Android App** (`io.appium.android.apis`) menggunakan **WebdriverIO** + **Appium**.

## 📱 Fitur yang Diuji
1. **Klik Elemen**  
   Menavigasi ke menu *Accessibility*.

2. **Input ke Elemen**  
   Membuka *Text Entry Dialog*, mengisi username dan password, lalu menekan tombol OK.

3. **Cek Elemen Tersedia**  
   Memastikan elemen *Accessibility* tampil di halaman utama aplikasi.

4. **Swipe Elemen**  
   Melakukan swipe pada galeri foto di menu *Views → Gallery → Photos*.

5. **Scroll Down**  
   Scroll ke elemen *Layouts* di menu *Views*.

---

## 🛠️ Teknologi yang Digunakan
- **Node.js**
- **WebdriverIO** (Test Framework)
- **Appium** (Mobile Automation)
- **Mocha** + **Chai** (Assertion)
- **Android Emulator / Real Device**

---

## 🚀 Cara Menjalankan
1. **Install Dependencies**
   '''bash
   npm install
3. **Pastikan Appium Server Berjalan**
   appium

5. **Pastikan Emulator / Device Tersambung**
   '''bash
   adb devices
8. **Jalankan Test**
   '''bash
   npx wdio run wdio.conf.js
   ```bash
   npm install
