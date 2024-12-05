## Cara Menjalankan
1. **Backend**
   ```bash
   cd backend
   # Install dependencies
   npm install
   # Jalankan server
   npm start

2. **Frontend**
   ```bash
     cd frontend
     # Install dependencies
     npm install
     # Jalankan server
     npm start

  
### **3. Sinkronisasi dengan GitHub**
Repository `backend` dan `frontend` tetap terpisah di GitHub, sehingga setiap folder (`backend` dan `frontend`) dikelola secara independen. Anda akan bekerja di masing-masing folder untuk commit dan push ke repository terkait.

---

### **4. Pengelolaan Profesional**
- **CI/CD:** Tambahkan file konfigurasi CI/CD (`.github/workflows/`) di masing-masing repository jika Anda menggunakan GitHub Actions.
- **Linting dan Testing:** Tambahkan konfigurasi linting (`eslint`, `prettier`) dan pengujian otomatis di masing-masing repository.
- **Issue dan PR Management:** Gunakan *issues* dan *pull requests* di masing-masing repository untuk melacak perubahan secara modular.

---
