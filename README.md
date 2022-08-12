# Pre-Test Bootcamp fullstack developer

## Task 1

- Buatlah 2 project terkait frontend dan backend
- Buatlah 1 database dengan ketentuan user db: 
  - user: `<user_github>`
  - pass: `<di isi bebas>`
  - database: `<user_github>`
  - platform: boleh pilih `postgresql`, `mysql`, `oracle` dll

## Task 2

- Untuk backend:
  - Teknologi silahkan pilih contohnya `spring-boot`, `laravel`, `nodejs`, dll 
  - Gunakan Rest API
  - Gunakan feature authentication & Authorization (protocolnya silahkan bebas) 
  - deploy aplikasi tersebut ke platform as a service contoh heroku, aws, gcp dan lain-lain

## Task 3

- Untuk frontend:
  - Teknologinya silahkan pilih contohnya `angular`, `vue`, `react` dan lain-lain
  - Gunakan API yang telah di buat dari backend berserta halama login 
  - deploy aplikasi tersebut ke platform as a service contoh heroku, aws, gcp dan lain-lain

## Appendix

Buatlah aplikasi Pelayanan Pembayaran Listrik (PLN)

- Setiap pelanggan bisa memiliki produk (Token) yang lebih dari satu, artinya satu pelanggan mungkin memiliki lebih dari 1 rumah.
- Token listrik terdiri dari

| kode 	| nama produk   | harga    	|
| :---  	| :---		    | :---      	|
| 20   	| Rp. 20.000	| 21.000   	|
| 50	| Rp. 50.000	| 51.000	|
| 100	| Rp. 100.000	| 101.500	|
| 200	| Rp. 200.000	| 201.500	|
| 500	| Rp. 500.000	| 502.000	|
| 1000	| Rp. 1.000.000	| 1.005.000	|

- Transaksi pembelian token harus dicatat
- Transaksi sisa saldo harus terdeteksi, artinya contohnya sisa saldo `Rp.10.000` ketika membeli token sebesar `Rp.100.000` maka saldonya sekarang harus bertambah menjadi `Rp.110.000`.
- Pelanggan bisa melihat detail transaksi pembelian token sesuai nomor-pelanggan
- Harga token sewaktu-waktu dapat berubah
