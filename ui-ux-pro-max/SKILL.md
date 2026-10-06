# UI UX Pro Max

Skill desain UI/UX untuk dipakai OpenCode di semua sesi & project.

## Kapan dipakai

Otomatis aktif setiap tugas yang menyentuh tampilan: bikin/ubah halaman web,
komponen UI, review desain, atau verb seperti "bagusin", "rapihin", "presisi".

## Standar wajib

1. **Mobile-first & responsif** — layout tidak boleh overlap/broken di 360px.
2. **Kontras aman** — teks di atas background gelap minimal putih 85% (#f1f5f9),
   jangan abu di atas abu.
3. **Sentuhan presisi** — gap konsisten (0.5/0.75/1rem), radius konsisten (8/12px),
   teks tombol `white-space: nowrap` (tidak turun baris aneh).
4. **State selalu jelas** — loading (spinner/bar + %), error (pesan + aksi),
   kosong (empty state), sukses (konfirmasi). Tidak ada tombol mati tanpa feedback.
5. **Bahasa mengikuti UI** — kalau app bilingual (ID/EN), semua string baru
   wajib ada di KEDUA locale. Tidak ada string hardcoded satu bahasa.

## Gaya default (boleh dioverride user)

- Dark glassmorphism: background gelap + kartu transparan + border halus.
- Aksen gradient ungu→pink (`#a855f7` → `#ec4899`).
- Font sistem, hierarchy jelas (judul gradient, label kecil uppercase).

## Cara kerja

1. Baca file terkait dulu sebelum mengubah (jangan tebak struktur).
2. Ubah minimal, pertahankan pola existing (inline style vs CSS file ikuti file tsb).
3. Verifikasi: `tsc --noEmit` untuk TS, screenshot/tab untuk visual bila bisa.
4. Laporkan yang diubah + cara user melihat hasilnya (refresh tab / restart apa).

## TODO pemilik (isi sesuai selera)

- [ ] Palet warna final + font pilihan
- [ ] Contoh komponen favorit (button, card, modal)
- [ ] Pantangan (yang TIDAK boleh dilakukan)
