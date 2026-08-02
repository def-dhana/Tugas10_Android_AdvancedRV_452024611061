# Tugas 10: Advanced RecyclerView (Android Development)

---

## 👤 Informasi Mahasiswa

* **Nama**: Suryatama Widyadhana
* **NIM**: 452024611061
* **Repository**: [Tugas10_Android_AdvancedRV_452024611023] https://github.com/def-dhana/Tugas10_Android_AdvancedRV_452024611061

---

## 📌 Deskripsi Proyek

Aplikasi ini mendemonstrasikan implementasi **Advanced RecyclerView** pada platform Android menggunakan bahasa pemograman **Kotlin**. Proyek ini berfokus pada pengolahan tampilan daftar data yang lebih efisien, dinamis, serta responsif dengan memanfaatkan arsitektur komponen Android modern.

### ✨ Fitur Utama
1. **Penerapan Advanced RecyclerView**: Menampilkan daftar item menggunakan layout kustom (CardView/Material Design) yang rapi.
2. **Efisiensi Memori & Render (`ListAdapter` & `DiffUtil`)**: Penggunaan `DiffUtil` untuk menghitung perbandingan item secara asinkron sehingga pembaruan UI berlangsung mulus tanpa *lag*.
3. **Penaangan Event Klik (Item Click Handling)**: Interaksi ketika item diklik untuk membuka tampilan detail atau melakukan aksi tertentu.
4. **Penggunaan ViewBinding**: Mengabaikan penggunaan `findViewById` tradisional demi keamanan tipe (*type-safety*) dan kode yang lebih bersih.
5. **Layout Manager Dinamis**: Fleksibilitas penggunaan `LinearLayoutManager` / `GridLayoutManager`.

---

## 🛠️ Teknologi & Library

* **Bahasa Pemrograman**: Kotlin
* **IDE**: Android Studio (Ladybug / Jellyfish / Hedgehog)
* **UI Components**: 
  * `RecyclerView`
  * `CardView` & `MaterialCardView`
  * `ConstraintLayout`
* **Architecture / Tools**:
  * ViewBinding
  * `ListAdapter` & `DiffUtil`
* **Image Loading** *(opsional)*: Glide / Coil

---

## 📂 Struktur Direktori Proyek

```text
Tugas10_Android_AdvancedRV_452024611023/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/com/example/advancedrv/
│   │       │   ├── adapter/
│   │       │   │   ├── ItemAdapter.kt          # Custom Adapter / ListAdapter
│   │       │   │   └── ItemDiffCallback.kt      # DiffUtil Implementation
│   │       │   ├── model/
│   │       │   │   └── ItemModel.kt             # Data Class
│   │       │   └── ui/
│   │       │       ├── MainActivity.kt          # Main List View
│   │       │       └── DetailActivity.kt        # Detail View
│   │       └── res/
│   │           ├── layout/
│   │           │   ├── activity_main.xml
│   │           │   ├── activity_detail.xml
│   │           │   └── item_row.xml             # Custom Item Design
│   │           └── values/
│   └── build.gradle.kts
└── README.md
```

---

## 🚀 Cara Menjalankan Proyek

1. **Clone Repository**
   ```bash
   git clone https://github.com/NaufalAhnafussidqi/Tugas10_Android_AdvancedRV_452024611023.git
   ```

2. **Buka di Android Studio**
   * Buka aplikasi **Android Studio**.
   * Pilih **Open** dan arahkan ke direktori hasil clone proyek ini.

3. **Sync Gradle Project**
   * Pastikan koneksi internet stabil saat Android Studio melakukan pemuatan (*Sync Project with Gradle Files*).

4. **Jalankan Aplikasi**
   * Sambungkan perangkat Android fisik (via USB Debugging) atau gunakan **Android Emulator**.
   * Klik tombol **Run (Shift + F10)** pada Android Studio.

---
