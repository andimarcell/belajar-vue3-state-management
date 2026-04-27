# Vue 3 State Management Mastery 🚀

Proyek ini mendemonstrasikan berbagai cara mengelola data (state) di Vue 3 agar komponen yang bersarang (nested) dapat saling berkomunikasi dengan efisien.

## Materi yang Dipelajari:
- **Ref vs Reactive**: Kapan menggunakan keduanya untuk reaktivitas data.
- **Prop Drilling Analysis**: Memahami kenapa mengirim data lewat banyak level komponen itu merepotkan.
- **Provide & Inject**: Solusi bawaan Vue untuk mengirim data ke komponen jauh tanpa Prop Drilling.
- **Composables Pattern**: Memisahkan logika state ke file tersendiri agar bisa digunakan ulang.
- **Pinia (Global State)**: Standar industri saat ini untuk mengelola state aplikasi skala besar secara terpusat.

## Struktur Komponen Demo:
- Parent
  - Child
    - Grand Child
      - Great Grand Child
