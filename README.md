## Ringkasan Praktikum
Praktikum Desain Pemrograman Web (DPW) ini bertujuan mengenalkan alat kolaborasi dan kontrol versi yang penting untuk pengembangan web modern: Git dan GitHub. Materi dan tugas disusun agar peserta memahami alur kerja dasar Git serta cara berkontribusi pada repository bersama.

## Informasi Pertemuan 1
- Tanggal : 02-02-2026  
- Hari    : Senin  
- Ruangan : Laboratorium RPL  
- Materi  : Git dan GitHub

## Tujuan Pembelajaran
- Memahami konsep kontrol versi terdistribusi.
- Menguasai perintah Git dasar untuk menyimpan dan membagikan perubahan.
- Mengerti alur kerja kolaboratif menggunakan branch dan Pull Request di GitHub.

## Agenda Singkat
1. Pengenalan Git & GitHub (konsep, manfaat)
2. Instalasi dan konfigurasi awal
3. Dasar perintah Git: clone, add, commit, push, pull
4. Branching dan Pull Request
5. Praktik: membuat perubahan dan mengirimkan PR

## Materi Singkat (Inti)
- Git = alat kontrol versi lokal/terdistribusi  
- GitHub = layanan hosting repository + fitur kolaborasi (PR, Issues, Actions)  
- Alur dasar: clone → branch → commit → push → pull request → merge

## Langkah Praktikum (contoh perintah)
```bash
# clone repo
git clone <URL_REPO>
cd <NAMA_REPO>

# buat branch fitur
git checkout -b fitur/nama-fitur

# buat perubahan, lalu
git add .
git commit -m "Menambahkan fitur X"

# kirim ke remote
git push origin fitur/nama-fitur
```
Lanjutkan dengan membuat Pull Request di GitHub dan menunggu review.

## Tugas / Deliverable
- Buat atau perbarui file README.md sesuai panduan.
- Implementasikan perubahan kecil (mis. halaman profil, tugas praktikum) pada branch terpisah.
- Buat Pull Request dengan deskripsi jelas dan label jika diminta.

## Cara Kontribusi
1. Fork repository (jika diperlukan) atau clone langsung jika Anda anggota.  
2. Buat branch baru untuk setiap fitur/perbaikan.  
3. Sertakan commit ringkas dan bermakna.  
4. Push branch dan buka Pull Request.  
5. Tanggapi review dan lakukan perbaikan jika diminta.

## Catatan untuk Peserta
- Cantumkan nama lengkap pada daftar hadir dan di commit awal (git config --global user.name/email).
- Simpan hasil kerja di repository pribadi atau folder tugas sesuai instruksi asisten.
- Jika mengalami kendala, hubungi asisten praktikum pada jam lab.

## Referensi Singkat
- Dokumentasi Git: https://git-scm.com/docs  
- Panduan GitHub: https://docs.github.com/

<!-- Isi daftar peserta atau nama Anda di bawah ini -->
- Peserta: (Isi nama-nama peserta di sini)
=======
# DPW PRAKTIKUM

Asisten Praktikum Desain Pemrograman Web:
1. Ahmadi Ihsan Ananda
2. Agus Syuhada
3. Vannesa Ayuni
4. .......

# PERTEMUAN 1
Tanggal : 02-02-2026<br>
Hari    : Senin<br>
Ruangan : Laboratorium RPL<br>
Materi  : Git dan GitHub