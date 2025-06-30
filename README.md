# Tugas K-Means Clustering

Repository ini berisi tugas clustering dengan metode K-Means menggunakan dataset interaksi postingan media sosial.

## 📁 Isi File:
- `main.ipynb`: Notebook Python untuk proses clustering.
- `Live.csv`: Dataset berupa data postingan (jumlah reaksi, komentar, share).
- `hasil.png`: Screenshot hasil visualisasi klastering.

## 🔍 Tujuan:
Mengelompokkan postingan menjadi beberapa klaster berdasarkan tingkat interaksinya, menggunakan algoritma K-Means.

## 📊 Tools:
- Python
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
  
## 📊 Hasil Clustering

Dataset dikelompokkan menjadi 3 klaster berdasarkan jumlah:
- Reaksi (`num_reactions`)
- Komentar (`num_comments`)
- Share (`num_shares`)

### Karakteristik Klaster:
- **Klaster 0**: Postingan viral (reaksi dan share tinggi)
- **Klaster 1**: Postingan biasa (interaksi sedang)
- **Klaster 2**: Postingan kurang interaksi

Visualisasi hasil clustering ada di folder `images/hasil.png`.
