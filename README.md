  C. Misi 1: Memahami Merge Conflict
1. Apa yang dimaksud dengan Merge Confict dalam Git?

  I. Simulasi Masalah (Studi Kasus)

Kasus 1: Saat terjadi confict, Budi panik. Ia ingin membatalkan proses merge yang sedang
bermasalah agar kembali ke posisi aman sebelum merge. Perintah Git apa yang harus ia gunakan?

Jawaban: Budi perlu mengetik perintah git merge --abort, ini untuk perintah membatalkan atau menghentikan conflict yang sedang terjadi dan 
mengembalikan keadaan ke posisi awal sebelum di merge

Kasus 2: Apakah merge confict selalu berarti ada anggota tim yang melakukan kesalahan (error)?
Jelaskan alasannya berdasarkan simulasi yang baru saja kalian lakukan!

Jawaban: tidak selalu, merge conflict terjadi ketika dua developer melakukan perubahan pada file projek di baris yang sama, 
sehingga adanya pemberitahun conflict dan menghentikan proses merge sebagai pengaman agar sistem tidak sembarangan menimpa 
kode buatan developer A maupun B, sehingga setelah itu kedua developer dapart berdiskusi untuk menentukan bagian siapa yang akan di gunakan dan di merge
