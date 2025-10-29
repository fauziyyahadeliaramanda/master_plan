# Hasil Screenshot

Berikut adalah hasil tampilan aplikasi Flutter setelah Implementasi Dasar State dengan Model-View
1. [Hasil Screenshot](images/01.jpeg)
2. Langkah ini bertujuan untuk membuat tampilan yang bisa berubah secara dinamis sesuai interaksi pengguna (misalnya menambah task, mencentang checklist, atau mengedit teks).
Kalau kita menggunakan StatelessWidget, tampilan tidak akan bisa diperbarui secara otomatis karena tidak memiliki state.
3. Variabel plan digunakan untuk menyimpan dan memperbarui daftar rencana.
Dibuat konstanta karena pada saat pertama kali dibuat, nilainya masih tetap (belum ada task) — dan membantu efisiensi memori.
4. [Hasil Screenshot](images/02.jpeg) Langkah 9 menampilkan daftar tugas secara dinamis, di mana pengguna bisa mengedit teks dan menandai tugas selesai.
5. Langkah 11 (initState) → digunakan untuk inisialisasi awal ketika widget pertama kali dibuat, seperti membuat ScrollController dan menambahkan listener.
Langkah 13 (dispose) → digunakan untuk membersihkan resource seperti controller saat widget dihapus, agar tidak terjadi kebocoran memori.


