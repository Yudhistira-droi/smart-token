# SMART TOKEN — IoT Electricity Monitoring

Website demo untuk tugas Manajemen Inovasi. Dibangun dengan React, TypeScript, Vite, Tailwind CSS, Recharts, dan Lucide.

## Menjalankan secara lokal
1. Pasang Node.js versi LTS dari https://nodejs.org
2. Ekstrak ZIP ini.
3. Buka folder `smart-token` di terminal.
4. Jalankan `npm install`
5. Jalankan `npm run dev`
6. Buka URL lokal yang ditampilkan Vite.

## Deploy ke Vercel tanpa VS Code
1. Upload folder proyek ke GitHub (semua file dan folder di dalam `smart-token`).
2. Di Vercel pilih **Add New → Project**, lalu impor repository GitHub.
3. Framework Preset: Vite. Build Command: `npm run build`. Output Directory: `dist`.
4. Klik **Deploy**.

## Catatan penting
Aplikasi ini masih DEMO. Nilai pemakaian dan status perangkat disimulasikan di browser; belum membaca meter PLN, ESP32, sensor LDR, atau Firebase sungguhan. Jangan menganggap estimasi kWh sebagai pembacaan resmi meter.
