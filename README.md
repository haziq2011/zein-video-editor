# Zein Video Editor v2

Editor video berasaskan Next.js + React.

## Fungsi yang sudah tersedia

- Import video dari peranti
- Preview video dalam browser
- Play / pause
- Seek timeline
- Trim In / Out
- Teks overlay + item timeline
- Import audio (nama track disimpan pada sesi)
- Kawalan volume
- Playback speed
- Filter: Mono, Warm, Cool, Contrast
- Reset projek
- Export klip melalui `MediaRecorder` sebagai WebM

## Penting tentang MP4

Versi ini sengaja menggunakan export WebM native supaya boleh berjalan terus dalam browser tanpa server video. Untuk export MP4 sebenar seperti CapCut, projek boleh dikembangkan dengan FFmpeg/WASM atau backend rendering. Dependency FFmpeg sudah disediakan dalam `package.json` untuk pembangunan seterusnya.

## Jalankan

```bash
npm install
npm run dev
```

Buka `http://localhost:3000`.

## Deploy Vercel

Import folder ini sebagai projek Next.js. Vercel mempunyai sokongan terbina dalam untuk Next.js dan biasanya mengesan build settings secara automatik.
