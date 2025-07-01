# ♟️ Catur Online Real-Time

![Screenshot Catur Online](https://i.imgur.com/GzB9kbl.png)

Sebuah aplikasi catur online berbasis web yang memungkinkan dua pemain untuk bertanding secara real-time melalui sistem *room*. Proyek ini dibangun menggunakan Next.js dan Socket.IO.

---

## ✨ Fitur Utama

-   **Gameplay Real-Time:** Gerakan bidak langsung disinkronkan antara dua pemain menggunakan WebSockets.
-   **Sistem Room:** Pemain dapat membuat room baru atau bergabung ke room yang sudah ada menggunakan kode unik.
-   **Validasi Aturan Catur:** Menggunakan `chess.js` untuk memastikan semua gerakan sesuai dengan aturan catur resmi (termasuk skak, skakmat, dan promosi).
-   **Orientasi Papan Otomatis:** Papan catur akan otomatis dibalik untuk pemain yang memegang bidak Hitam.

---

## 💻 Teknologi yang Digunakan

-   **Framework:** [Next.js](https://nextjs.org/)
-   **Komunikasi Real-Time:** [Socket.IO](https://socket.io/)
-   **Logika Catur:** [chess.js](https://github.com/jhlywa/chess.js)
-   **UI Papan Catur:** [react-chessboard](https://github.com/Clariity/react-chessboard)
-   **Styling:** [Tailwind CSS](https://tailwindcss.com/)
-   **Deployment:** [Vercel](https://vercel.com/)

---

## 🚀 Cara Menjalankan Secara Lokal

Untuk menjalankan proyek ini di komputer Anda, ikuti langkah-langkah berikut:

1.  **Clone repository ini:**
    ```bash
    git clone [https://github.com/NAMA_USER_ANDA/NAMA_REPO_ANDA.git](https://github.com/NAMA_USER_ANDA/NAMA_REPO_ANDA.git)
    ```

2.  **Masuk ke direktori proyek:**
    ```bash
    cd nama-repo-anda
    ```

3.  **Install semua dependensi:**
    ```bash
    npm install
    ```

4.  **Jalankan server pengembangan:**
    ```bash
    npm run dev
    ```

5.  **Buka browser** dan akses `http://localhost:3000`. Untuk mencoba mode multiplayer, buka di dua tab browser.

---

## 🚧 Rencana Pengembangan (To-Do)

-   [ ] Implementasi AI (Kecerdasan Buatan) sebagai lawan menggunakan Stockfish.js.
-   [ ] Menambahkan mode penonton (spectator).
-   [ ] Penanganan jika pemain terputus dari permainan.
-   [ ] Menambahkan sistem akun pengguna dan riwayat permainan.
