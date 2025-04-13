# 📱 Flutter: Stateless vs Stateful + Curved Navigation Bar

Proyek ini adalah contoh sederhana dari perbedaan antara **StatelessWidget** dan **StatefulWidget** dalam Flutter, ditambah dengan implementasi UI modern menggunakan **Curved Navigation Bar**. Stylish dan fungsional! 😉

---

## 🧠 Apa itu Stateless vs Stateful?

|                        | StatelessWidget                     | StatefulWidget                     |
|------------------------|--------------------------------------|------------------------------------|
| Bisa berubah?          | ❌ Tidak                            | ✅ Bisa                            |
| Menyimpan state?       | ❌ Tidak                            | ✅ Iya                             |
| Contoh penggunaan      | Header, ikon, teks statis           | Counter, tab, animasi interaktif  |
| Rebuild otomatis?      | ❌ Tidak                            | ✅ Ya, via `setState()`             |

---

## 🧊 StatelessWidget = Widget Kalem

> Kayak poster di dinding. Selalu sama, gak berubah, gak ribet.

Contohnya: `MyApp` di `main.dart`, dia cuma setup awal doang, gak berubah seiring waktu.

---

## 🔥 StatefulWidget = Widget Aktif

> Kayak dashboard interaktif. Bisa berubah sesuai aksi user.

Contohnya: `Homepage` kamu, yang pakai **CurvedNavigationBar** dan bisa berubah saat user tap ikon.

---

## 📸 Tampilan UI
![image](https://github.com/user-attachments/assets/8818a078-be49-4d75-9f0c-ec8c5e4f5089)
Aplikasi ini menampilkan:
- ✅ UI dengan tema ungu modern
- ✅ Bottom navigation bar melengkung dengan animasi
- ✅ Navigasi interaktif dengan icon `home`, `favorite`, dan `settings`

---

## 🚀 Jalankan Proyek

```bash
flutter pub get
flutter run
