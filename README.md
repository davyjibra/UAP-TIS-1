## UAP v0.1
#### Endpoint Tanpa Otentikasi
- regis
POST /uap/register
- login
POST /uap/login

#### Endpoint yang Memerlukan Otentikasi (JWT)
- liat prodi
GET /uap/prodi
- liat mahasiswa
GET /uap/mahasiswa
- cek mahasiswa dari prodi id
GET /uap/mahasiswa/prodi/{id}
- liat matkul
GET /uap/matkul
- tambah matkul di akunmu
POST /uap/matkul/tambah
- liat matkul tambah
GET /uap/matkul/saya

#### Gambar ERD
![ERD](https://github.com/user-attachments/assets/77f07650-f005-47fa-9e6b-f32224cb189d)
