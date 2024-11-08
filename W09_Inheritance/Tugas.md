# Tugas Java: Inheritance dan Enkapsulasi

Buatlah sebuah program Java dengan tema bebas yang mengimplementasikan konsep **inheritance** dan **enkapsulasi**. Program ini harus memiliki setidaknya satu kelas *superclass* dan satu kelas *subclass*, dengan persyaratan sebagai berikut:

## Superclass

- Memiliki minimal **4 atribut**, dua di antaranya harus memiliki tingkat akses `private`.
- Dua atribut yang memiliki tingkat akses `private` harus diakses melalui metode **getter** dan **setter** (implementasi enkapsulasi).
- Memiliki setidaknya **dua metode**, termasuk satu metode yang menampilkan informasi umum tentang objek dari *superclass*.

## Subclass

- Mewarisi properti dan metode dari *superclass*.
- Menambahkan minimal **dua atribut** dan **satu metode unik**.
- Menyertakan implementasi metode untuk menampilkan informasi lengkap tentang objek dari *subclass* (termasuk informasi dari *superclass*).

## Penggunaan dalam Main Class

- Buatlah **kelas utama** untuk menjalankan program.
- Di dalam kelas utama, buatlah minimal **tiga objek** dari *subclass*.
- Set dan ubah nilai atribut-atribut objek tersebut menggunakan metode **getter** dan **setter**.
- Tampilkan informasi lengkap dari setiap objek menggunakan metode yang ada.

## Batasan Tambahan

- Pastikan setiap atribut `private` hanya dapat diakses melalui metode **getter** dan **setter** untuk menjaga enkapsulasi.
- Gunakan **komentar pada kode** untuk menjelaskan konsep *inheritance* dan *encapsulation* yang Anda terapkan.

## Contoh Tema: Kendaraan

### Superclass `Kendaraan`
- Berisi atribut seperti `merk`, `tahunPembuatan`, `kecepatanMaks`, dan `harga`.
- Atribut `kecepatanMaks` dan `harga` harus bersifat `private` dan diakses melalui **getter** dan **setter**.

### Subclass `Mobil`
- Mewarisi atribut dan metode dari `Kendaraan`.
- Menambahkan atribut khusus seperti `jenisBahanBakar` dan `jumlahKursi`.
- Memiliki metode unik `tampilkanDetailMobil()`.

## Output yang Diharapkan

Program menampilkan informasi lengkap setiap objek yang telah dibuat dari *subclass*, misalnya:


Ingatlah untuk berkreasi! Anda bebas memilih tema program Anda, selama memenuhi semua batasan di atas. Misalnya, Anda bisa membuat program tentang hewan di kebun binatang, buku di perpustakaan, atau apapun yang Anda suka. Selamat mencoba!

Format penulisan nama file adalah **PPBO_08_09_NIM**, dengan isi file sebagai berikut:

```java
// Nama : ...
// NIM  : ...

// import ...

public class PPBO_08_09_NIM {
    public static void main(String[] args) {
        // ...
    }
}

// class ...
```
