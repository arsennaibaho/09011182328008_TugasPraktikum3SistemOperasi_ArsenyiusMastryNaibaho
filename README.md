# 09011182328008_TugasPraktikum3SistemOperasi_ArsenyiusMastryNaibaho

### 1. Lihat peralatan I/O, character device, yang ada pada system komputer.
![Screenshot from 2024-09-05 09-09-26](https://github.com/user-attachments/assets/bd07b122-41c4-4b46-bed9-79d18841f3d2)

### 2. Buatlah sub direktori januari, februari dan maret sekaligus pada direktori latihan5.
![Screenshot from 2024-09-05 09-10-42](https://github.com/user-attachments/assets/459d5ee9-918e-4c27-8744-ae74428e1413)
![Screenshot from 2024-09-05 09-26-35](https://github.com/user-attachments/assets/dd0e36e0-e293-450b-ade1-39050979002b)

### 3. Buatlah file dataku yang berisi nama, nim dan alamat anda pada sub direktori januari dan copy-kan file tersebut ke sub direktori februari dan maret.
![Screenshot from 2024-09-05 09-31-44](https://github.com/user-attachments/assets/7ac9843b-74bc-4dbc-ab10-3592b36bc1fb)
![Screenshot from 2024-09-05 09-48-29](https://github.com/user-attachments/assets/48125cc5-7ad5-4af4-be8a-4d71be2f7d27)

### 4. Ubahlah ijin akses file dataku pada sub direktori januari sehingga group dan others dapat melakukan write.
![Screenshot from 2024-09-10 22-51-39](https://github.com/user-attachments/assets/242cf7de-48e6-496f-a413-9db34e437dd7)

### 5. Ubahlah ijin akses file dataku pada sub direktori pebruari sehingga user dapat melakukan baik write, read maupun execute, tetapi group dan others hanya bisa read dan execute.
![Screenshot from 2024-09-10 23-06-15](https://github.com/user-attachments/assets/05e2722d-efd3-4e49-b3e8-df1984419296)

### 6. Ubahlah ijin akses file dataku pada sub direktori maret sehingga semua dapat melakukan write, read dan execute.
![Screenshot from 2024-09-10 23-09-07](https://github.com/user-attachments/assets/d55cdee5-16e3-47e8-b1e8-7216633d3a3f)

### 7. Hapuslah direktori maret.
![Screenshot from 2024-09-10 23-16-33](https://github.com/user-attachments/assets/833ef7a6-917c-4263-b994-dd921350f555)

### 8. Ubahkan kepemilikan sub direktori februari sehingga user dan group hanya dapat melakukan read, dan cobalah untuk membuat direktori baru haha pada sub direktori februari.
![Screenshot from 2024-09-10 23-33-41](https://github.com/user-attachments/assets/bc87ce74-e0f5-4e16-97d1-8c706a611998)

### 9. Modifikasi umask dari file dataku pada sub direktori januari menjadi 027 dan berapakan nilai default-nya ?
![Screenshot from 2024-09-10 23-48-13](https://github.com/user-attachments/assets/dd8ced9b-4dd9-4354-9d46-cc2c2e9c521a)
nilai default pada umask umumnya adalah 022 pada kebanyakan sistem. Dengan umask 022, file baru yang dibuat biasanya memiliki izin 644 (baca dan tulis untuk pemilik, baca saja untuk grup dan orang lain), serta direktori baru memiliki izin 755 (baca, tulis, dan eksekusi untuk pemilik, baca dan eksekusi untuk grup dan orang lain).

### 10. Buatlah link dari file dataku ke file dataku.ini dan file dataku.juga dan dengan perintah list perhatikan berapa link yang terjadi ?
![Screenshot from 2024-09-11 00-31-04](https://github.com/user-attachments/assets/d999fdd4-b112-4e82-baeb-36fb7c81e81c)
setelah memasukkan command line ls -l terdapat 2 link yang terjadi
