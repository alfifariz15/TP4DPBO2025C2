# TP4DPBO2025C2
Saya Muhammad Alfi Fariz dengan NIM 2311174 mengerjakan TP 4 dalam mata kuliah Desain Pemrograman Berorientasi Objek
untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

# Desain Program
Program ini adalah aplikasi berbasis GUI yang digunakan untuk mengelola data mahasiswa. Fitur utama dari program ini meliputi:
- Menambahkan mahasiswa baru dengan input: NIM, Nama, Jenis Kelamin, dan Nilai.
- Mengupdate data mahasiswa yang sudah ada.
- Menghapus data mahasiswa dengan konfirmasi sebelum penghapusan.
- Menampilkan daftar mahasiswa dalam bentuk tabel yang dapat diklik untuk mengedit data.
Program terdiri dari dua kelas utama:
1. Mahasiswa → Merepresentasikan data mahasiswa.
2. Menu → GUI utama untuk mengelola data mahasiswa.

# Alur Program
- Ketika program dijalankan:
1. GUI Dibuka → Membuat tampilan dengan JPanel, JTable, JComboBox, dan JButton.
2. Menampilkan Data Awal → populateList() mengisi daftar mahasiswa dengan data awal.
3. Menampilkan Tabel → setTable() menampilkan data dalam tabel GUI.

- Ketika pengguna menambahkan mahasiswa:
1. Pengguna mengisi NIM, Nama, Jenis Kelamin, dan Nilai di formulir input.
2. Klik tombol "Tambah" → Program mengambil data input, membuat objek Mahasiswa, lalu menambahkannya ke listMahasiswa.
3. Tabel diperbarui dengan data yang baru.

- Ketika pengguna mengedit mahasiswa:
1. Klik salah satu baris dalam tabel, data akan muncul di formulir input.
2. Pengguna mengubah data lalu klik "Update".
3. Data mahasiswa di listMahasiswa diperbarui, lalu tabel diperbarui.

- Ketika pengguna menghapus mahasiswa:
1. Klik baris yang ingin dihapus, lalu klik "Hapus".
2. Konfirmasi akan muncul sebelum data benar-benar dihapus.
3. Jika memilih "Yes", data dihapus dari listMahasiswa dan tabel diperbarui.

# Dokumentasi Output Program

https://github.com/user-attachments/assets/fdbb1fbb-5893-4bbb-bcdf-c841cec5018d

