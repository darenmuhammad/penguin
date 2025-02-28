# 🐧 **Penguin**

Selamat datang di dokumentasi **Penguin**!
Proyek ini adalah ilustrasi penguin menggunakan **HTML & CSS** dengan pendekatan **pure CSS** dan teknik **CSS animation** untuk efek interaktif.

## 📌 **Overview**

| 🔧 Properti | 📖 Deskripsi |
|------------|--------------|
| `linear-gradient()` | Digunakan untuk memberikan efek gradasi warna pada elemen. |
| `position: absolute;` | Mengatur posisi elemen berdasarkan parent-nya. |
| `border-radius` | Memberikan efek bulat pada elemen, cocok untuk bentuk penguin. |
| `animation` | Digunakan untuk membuat efek animasi seperti penguin melambaikan tangan. |
| `transform: scaleX(-1);` | Membalik elemen secara horizontal untuk efek simetri. |
| `@keyframes` | Mengatur gerakan animasi seperti melambaikan tangan secara berulang. |

## 🎨 **Struktur & Gaya**

### 🌄 **Background & Environment**
- **`left-mountain` & `back-mountain`**: Dibuat menggunakan `linear-gradient()` untuk memberikan efek pegunungan.
- **`sun`**: Bentuk bulat dengan `border-radius: 50%`.
- **`ground`**: Dibuat dengan `linear-gradient()` untuk menciptakan efek lanskap.

### 🐧 **Penguin Anatomy**
- **`penguin-head`**: Kepala penguin dengan efek gradasi untuk bayangan.
- **`eye` & `eye-lid`**: Mata penguin dengan menggunakan `background-color` dan `positioning`.
- **`beak`**: Dibuat dengan `border-radius` dan `background-color: orange`.
- **`penguin-body`**: Bagian tubuh dengan **gradasi tiga warna** untuk efek volume.
- **`arm.left`**: Dilengkapi animasi `@keyframes wave` agar penguin melambaikan tangan.
- **`foot`**: Dibentuk dengan `border-radius` agar terlihat seperti kaki penguin.

### 👕 **Shirt & Text**
- **`shirt`**: Dibuat menggunakan `font-size`, `font-family`, dan `color` untuk menampilkan teks "I CSS 💜".

## 🎬 **Interaktivitas**

### 🖱️ **Hover & Click Effects**
- **Penguin membesar saat diklik** → Menggunakan `:active` dengan `transform: scale(1.5);`.
- **Lambaian tangan otomatis** → Menggunakan `@keyframes wave` untuk efek bergerak berulang.

---
© 2025 | **Penguin CSS Project**

