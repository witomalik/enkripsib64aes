# enkripsib64aes
gambar medis

## Instalasi
1. Install anaconda dan jupyter notebook
2. Tempatkan ketiga file .ipynb pada folder yang sama
3. Sertakan dataset kedalam folder

## Struktur Dataset
Gambar yang akan dienkripsi ditempatkan pada satu folder dengan nama yang nanti nya akan digunakan saat tahap mengubah path
- Key_Generator.ipynb
- AES_Encrypt_new.ipynb
- AES_Decrypt_new.ipynb
- gambar
 - enc
  - IMG1.JPG
  - ...JPG
 - dec
  - - IMG1.JPG
  - ...JPG

## Tahapan Penggunaan Program
Terdapat tiga tahapan dalam menggunakan program
1. Pembentukan key 
2. Proses enkripsi
3. Proses dekripsi

### Proses pembentukan key (key_generator.ipynb)
Pada tahap ini akan menghasilkan file key yang akan digunakan
1. Jalankan cell-1
2. Ubah path pada cell-2, sesuaikan dengan folder yang digunakan
3. Jalankan cell-2 untuk menghasilkan file key

### Proses enkripsi (AES_Encrypt_new.ipynb)
1. Jalan kan cell-1 sampai cell-3
2. Pada cell-4 sesuaikan path dengan folder yang digunakan
3. Jalankan cell-4 untuk menghasilkan gambar yang terenkripsi
4. Gambar hasil akan ditempatkan pada folder "enc"

### Proses dekripsi (AES_Decrypt_new.ipynb)
1. Jalan kan cell-1 sampai cell-2
2. Pada cell-3 sesuaikan path dengan folder hasil enkripsi dan key_path dengan folder awal
3. Jalankan cell-3 untuk menghasilkan gambar yang dekripsi
