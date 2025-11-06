Abrar Rafii Ibrahim
2315061095
Tugas Akhir Judul 2 Praktikum Jaringan Komputer

Link YouTube: https://youtu.be/Z2gNq2wvFXc

Dapat dijelaskan pada Tugas Akhir Judul 2 pada Praktikum Jaringan Komputer, bahwa apabila pengguna belum atau salah dalam melakukan konfigurasi baik pada Switch, Router, atau Default Gateway, maka yang terjadi saat ingin berkomunikasi adalah Request Timed Out (RTO) yang disebabkan karena konfigurasinya yang tidak sesuai. 

Ping Gagal:
<img width="595" height="208" alt="Screenshot 2025-11-06 234029" src="https://github.com/user-attachments/assets/4a4771b8-8d7a-4d0a-b0e5-58417bea8a3c" />

Ping gagal atau RTO dapat terjadi dikarenakan perangkat belum dikonfigurasikan dengan baik, seperti kekeliruan pada penentuan IP Address atau Default Gateway sehingga tidak dapat mengirimkan paket dari satu perangkat ke perangkat yang lain.

Pink Berhasil:
Ping Berhasil PC-A to PC-B
<img width="615" height="269" alt="Screenshot 2025-11-06 233216" src="https://github.com/user-attachments/assets/29cc92c2-6ca2-41b4-8fb9-c2480c285afd" />

Ping Berhasil S1 to PC-B
<img width="704" height="261" alt="Screenshot 2025-11-06 233847" src="https://github.com/user-attachments/assets/4f00791d-0f5d-4e1b-a048-e8ec4e0e6ce9" />

Ping berhasil dikirimkan dikarenakan IP Address dari tiap perangkat, dalam kasus ini yaitu Switch dan Router telah dikonfigurasi dengan benar, juga IP Address dan Default Gateway baik pada Switch, Router, maupun PC sudah sesuai sehingga saat perangkat ingin berkomunikasi, maka komunikasi akan berjalan dengan semestinya, namun sempat ada RTO satu kali sebagai penyesuaian bahwa paket yang dikirimkan sedang mencari dan mencocokkan ke alamat yang dituju, setelah alamat ditemukan, barulah paket-paketnya dapat terkirim.
