## Penjelasan Program Praktikum 5
Buat program sederhana yang menampilkan daftar nilai mahasiswa, dengan tampikan menu pilihan: (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data)
### Langkah - Langkah:
- Pertama kita membuat dictionary kosong ```data = {}``` 
- Lalu gunakan perulangan while. dengan inptan menu(Lihat, Tambah, Ubah, Hapus, Cari, Keluar)
- Dan gunakan kondisi if, else dan elif untuk mengeksekusi perintah.
- Ketik "k" untuk keluar. Gunakan fungsi if, jika hasil true program akan berhenti.
- Ketik "l" untuk melihat hasil inputan. Gunakan looping for ```for x in data.items():``` lalu masukan printah print data.
- Ketik "t" untuk menambahkan data. inputkan data: Nama, NIM, Nilai Tugas, Nilai UTS, NIlai UAS. Nilai akhir di hitung dengan rumus ```akhir   = (0.30 * tugas) + (0.35 * uts) + (0.35 * uas)```
  ![tambah](https://user-images.githubusercontent.com/56240483/70388628-f6ae1e00-19e6-11ea-9430-58f5de77abb6.png)
- Ketik "u" untuk mengubah data. Masukan data nama yang ingin di ubah, jika data benar akan kembali ke data perubahan, jika salah akan tercetak ```print("Data {0} Tidak tersedia ".format(nama))``` dan muncul kembali menu pemilihan untuk input data.
  ![ubah](https://user-images.githubusercontent.com/56240483/70388631-fe6dc280-19e6-11ea-9e4e-0ae67e49e17a.png)
- Ketik "h" untuk menghapus data. Dengan menginputkan data nama yang ingin di hapus menggunakan kondisi if, jika hasilnya benar data akan di hapus.
  ![hapus](https://user-images.githubusercontent.com/56240483/70388624-e5fda800-19e6-11ea-91af-186ef51827be.png)
- Ketik "c" untuk mencari data. dengan menginputkan data nama yang ingin di cari, jika datanya benar otomatis data akan tercetak yang dicari.
  ![cari](https://user-images.githubusercontent.com/56240483/70388622-dbdba980-19e6-11ea-9aa6-0cf7effcbfc7.png)
- Kondisi terakhir gunakan kondisi else dan ``` print(" === Pilih Sesuai Menu Yang Tersedia === ")``` maksudnya jika menu yang anda inputkan salah anda akan dialihkan ke menu yang tersedia.

