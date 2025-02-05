## Soal 1 (bobot 40)
Anda diberikan sebuah program java bernama FileGenerator. Program tersebut akan menghasilkan 3 buah file dengan format nama file {NIM}-{urutan}. Anda perlu memberikan sebuah argumen saat melakukan eksekusi program tersebut yang berupa NIM anda. Contoh eksekusi : “java FileGenerator 71111111”. Program ini akan digunakan untuk melakukan skenario penggunaan Git sebagai berikut:
1. Jalankan program FileGenerator disertai argumen sesuai NIM anda masing – masing. 
2. Lakukan commit untuk file yang dihasilkan dengan pesan "menambahkan file : {Nama File Yang Dihasilkan}".
3. Jalankan kembali program FileGenerator seperti langkah 1 sebanyak 4 kali. Setiap program setelah dijalankan, lakukan commit dengan pesan "perubahan file {urutan perubahan}". Misal program dijalankan kedua kalinya, maka pesan commit akan sebagai berikut "perubahan file pertama".
4. Setelah commit terakhir, lakukan revisi pada setiap filenya dengan aturan sebagai berikut:
	- File {NIM}-1 dikembalikan ke commit saat file pertama kali diciptakan.*
	- File {NIM}-2 dikembalikan ke commit saat file pertama kali diupdate.*
	- File {NIM}-3 dikembalikan ke commit saat file kedua kali diupdate.*
* pesan commit “Perubahan file final”
5. Lakukan push ke github anda.

### Poin Penilaian
- Membuat branch untuk mengerjakan soal	: 50
- Melakukan pull request dan merge branch kerja ke branch main : 25
- Perubahan file sesuai 		: 25

## soal 2 (bobot 60)
Anda akan diberikan sebuah program java bernama FileGeneratorV2. Program tersebut akan menghasilkan 500 file berukuran kecil dan 1 buah folder bernama temp yang berada satu folder dimana program anda dieksekusi. File yang dihasilkan memiliki 3 jenis file yaitu py, js, dan php. Anda dapat mengekseskusi program ini dengan menggunakan perintah "java FileGeneratorV2". Program ini akan digunakan untuk melakukan skenario penggunaan Git sebagai berikut:
1. Jalankan program FileGeneratorV2 dan masukan input sesuai perintah dari program.
2. Setelah menjalankan program, anda akan mendapatkan sebuah kode.
3. Kerjakan perintah berikut sesuai kode yang didapatkan:
	- Abaikan seluruh file dengan jenis py selain yang ada di folder temp.*
	- Abaikan seluruh file dengan jenis php yang hanya ada di folder temp.*
	- Abaikan seluruh file yang memiliki awalan nama test selain yang ada di folder temp.*
	- Abaikan seluruh file yang memiliki awalan nama hello yang hanya ada di folder temp.*
	* Pengabaian file juga harus berhasil saat diuji oleh asdos.
4. Lakukan commit semua file sesuai dengan jenis file masing – masing. Pesan dari commit juga harus menyesuaikan jenis file. Misal anda ingin melakukan commit terhadap file py maka pesan dari commit tersebut "menambahkan file py".
5. Lakukan push ke github anda.
6. Keluar dari program.

### Poin Penilaian
- Membuat branch untuk mengerjakan soal	: 50
- Melakukan pull request dan merge branch kerja ke branch main : 20
- Log dari git sesuai dengan skenario	: 10
- Perubahan file sesuai 		: 10
- Pengujian pengabaian file		: 10
