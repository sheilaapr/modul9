# 📱 Flutter Modul IX – StatefulWidget

Repo ini berisi hasil praktikum **Modul IX – StatefulWidget** pada mata kuliah Pemrograman Mobile.  
Terdapat dua percobaan utama yaitu **Counter App**, **Like Button**, serta tugas tambahan berupa **Tasbih Digital** dengan Circular Progress.

---

## 🎯 Tujuan
1. Memahami konsep **StatefulWidget** dalam Flutter.
2. Membedakan **StatelessWidget** dan **StatefulWidget**.
3. Menggunakan fungsi **setState()** untuk mengubah tampilan secara dinamis.
4. Mengimplementasikan perubahan state sederhana (counter, tombol like/unlike).
5. Membuat aplikasi **Tasbih Digital** dengan **circular progress bar**.

---

## 📚 Dasar Teori
- **StatefulWidget** adalah widget yang dapat berubah selama aplikasi berjalan (dinamis).
- **State** dikelola di dalam kelas turunan `State<T>` yang memuat data & logika perubahan.
- Fungsi **setState()** dipakai untuk memberi tahu Flutter bahwa terjadi perubahan data sehingga UI dirender ulang.
- Struktur dasar:
  - `StatefulWidget` → kerangka & penghubung dengan kelas `State`.
  - `State` → menyimpan data dinamis, method `setState()`, serta membangun UI.

---

## ⚙️ Alat & Bahan
- Flutter SDK
- VS Code / Android Studio
- Emulator / Smartphone untuk uji coba
- Paket tambahan:  
  ```yaml
  dependencies:
    flutter:
      sdk: flutter
    simple_circular_progress_bar: ^1.0.2
