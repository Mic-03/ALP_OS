# Reimplementasi Basic CLI pada Sistem Linux Menggunakan Python
## Deskripsi Proyek
Proyek ini adalah implementasi sederhana dari Command Line Interface (CLI) yang dapat menjalankan perintah dasar seperti pada terminal Linux. Proyek ini dikembangkan menggunakan Python dan menyediakan fungsi-fungsi untuk manipulasi file dan direktori.
## Cara Menjalankan Program
- Pastikan Python 3 sudah terinstal di sistem Anda.

- Git clone atau salin file ALP Operating System.py ke direktori lokal Anda.

- Buka terminal/command prompt dan navigasikan ke direktori tempat file ALP Operating System.py berada.

- Jalankan program dengan perintah:

  ```python ALP Operating System.py```

- Anda akan masuk ke antarmuka CLI sederhana dan dapat mengetikkan perintah.
## Daftar Perintah yang Diimplementasikan
### Perintah Dasar (Wajib)

- ls: Menampilkan daftar file dan folder di direktori saat ini.

  Contoh: ```ls```

- pwd: Menampilkan direktori kerja saat ini.

  Contoh: ```pwd```

- cd: Mengubah direktori kerja.

  Contoh: ```cd /path/to/directory```

- mkdir: Membuat direktori baru.

  Contoh: ```mkdir new_folder```

- rmdir: Menghapus direktori (hanya jika kosong).

  Contoh: ```rmdir empty_folder```

- touch: Membuat file kosong baru.

  Contoh: ```touch new_file.txt```

- rm: Menghapus file.

  Contoh: ```rm file_to_delete.txt```

- cp: Menyalin file dari satu lokasi ke lokasi lain.

  Contoh: ```cp source_file.txt destination_file.txt```

- mv: Memindahkan atau mengganti nama file/direktori.

  Contoh: ```mv old_name.txt new_name.txt```

- help: Menampilkan daftar perintah yang tersedia.

  Contoh: ```help```

- clear: Membersihkan layar terminal.

  Contoh: ```clear```

- exit: Keluar dari aplikasi CLI.

  Contoh: ```exit```

### Perintah Tambahan (Unik)

- search : Mencari file atau direktori berdasarkan nama.

  Contoh: ```search report```

- tree: Menampilkan struktur direktori dalam bentuk pohon.

  Contoh: ```tree```

- log : Menyimpan riwayat penggunaan perintah ke file log (command_log.txt).

  Contoh: ```log ls```
## Contoh Penggunaan

Berikut adalah contoh sesi interaksi dengan aplikasi CLI:
```
CLI > pwd
/home/user/projects

CLI > mkdir test_folder
Directory 'test_folder' created successfully.

CLI > cd test_folder
Changed directory to /home/user/projects/test_folder

CLI > touch file.txt
File 'file.txt' created successfully.

CLI > ls
file.txt

CLI > search file
/home/user/projects/test_folder/file.txt

CLI > tree
|- file.txt

CLI > log "Created test_folder and file.txt"
Command 'Created test_folder and file.txt' logged successfully.

CLI > exit
Exiting CLI. Goodbye!
```
## Struktur Direktori dan File

- ALP Operating System.py: File Python utama berisi kode CLI.

- command_log.txt: File log untuk mencatat perintah yang dijalankan (dibuat secara otomatis saat program berjalan).

## Penjelasan Singkat Tentang Perintah Tambahan

- search: Membantu pengguna mencari file atau direktori berdasarkan pola tertentu, sangat berguna untuk navigasi dalam struktur direktori yang besar.

- tree: Menyediakan representasi visual dari struktur direktori, mempermudah pengguna untuk memahami hierarki file.

- log: Menyimpan riwayat penggunaan perintah ke file log, berguna untuk dokumentasi atau referensi.


