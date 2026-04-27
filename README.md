# Vue 3 State Management Mastery 🚀

Proyek ini mendemonstrasikan berbagai cara mengelola data (state) di Vue 3 agar komponen yang bersarang (nested) dapat saling berkomunikasi dengan efisien.

## 🧠 Materi yang Dipelajari
- **Ref vs Reactive**: Penggunaan reaktivitas data yang tepat.
- **Prop Drilling Analysis**: Memahami batasan pengiriman data manual antar komponen.
- **Provide & Inject**: Solusi bawaan Vue untuk menghindari Prop Drilling sederhana.
- **Pinia (Global State)**: Standar industri untuk state management skala besar.

## 🛠 Tech Stack & Tools
- **Framework**: Vue 3 (Composition API)
- **State Management**: Pinia
- **Build Tool**: Vite
- **API**: MockAPI / JSON Server
- **IDE**: VS Code + Vue - Official (Volar)

## 🚀 Memulai Project (Project Setup)

Pastikan Anda sudah menginstal [Node.js](https://nodejs.org/).

1. **Instalasi Dependency:**
   ```sh
   npm install
Menjalankan Server Development:
code
Sh
npm run dev
Menjalankan Mock Server (Jika ada):
code
Sh
npx json-server db.json
📂 Struktur Komponen Demo
Parent Component
Child Component
Grand Child Component
Great Grand Child Component (Penerima State)