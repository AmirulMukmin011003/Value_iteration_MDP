# Implementasi Algoritma Value Iteration

## Deskripsi
Repository ini berisi implementasi algoritma **Value Iteration** untuk menyelesaikan permasalahan *Markov Decision Process* (MDP) menggunakan Python. Algoritma ini memperbarui nilai setiap state berdasarkan persamaan Bellman optimalitas hingga mencapai kondisi konvergensi, kemudian menentukan kebijakan (*policy*) optimal.

## Daftar File
- `VI.ipynb`: Implementasi algoritma Value Iteration pada studi kasus pemilihan jalur dari Rumah menuju Kampus.
- `VI_5_SHAPE.ipynb`: Implementasi Value Iteration pada studi kasus tambahan dengan lima atau lebih state, sesuai isi notebook.

## Pustaka yang Digunakan
- Python 3
- NumPy (jika digunakan dalam notebook)
- Matplotlib (jika digunakan untuk membuat grafik)

## Cara Menjalankan
1. Pastikan Python dan Jupyter Notebook atau JupyterLab telah terpasang.
2. Instal pustaka yang diperlukan sesuai impor pada notebook.
3. Unduh atau *clone* repository ini.
4. Buka file `VI.ipynb` atau `VI_5_SHAPE.ipynb` menggunakan Jupyter Notebook, JupyterLab, atau Visual Studio Code.
5. Jalankan setiap sel kode secara berurutan.

## Contoh Keluaran
Untuk studi kasus ini, saya menerapkan studi kasus paling sederhana yaitu dengan tiga state dengan faktor diskonto 0,9, nilai optimal yang diharapkan adalah:

| State | Nilai optimal |
|---|---:|
| Rumah | 9 |
| Simpang | 10 |
| Kampus | 0 |

Kebijakan optimal:
- Rumah: Jalan alternatif
- Simpang: Lanjut menuju Kampus

Algoritma mencapai konvergensi setelah tiga iterasi pembaruan nilai.

## Konsep yang Dipelajari
- Markov Decision Process (MDP)
- Persamaan Bellman optimalitas
- Pembaruan nilai state
- Konvergensi Value Iteration
- Penentuan kebijakan optimal
