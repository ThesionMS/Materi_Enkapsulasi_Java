# 1. Sejarah Singkat Pemrograman Berorientasi Objek:

Konsep pemrograman berorientasi objek sudah ada sekitar tahun 1960-an. Pertama kali diperkenalkan oleh **Ole Johan Dahl** dan **Kristen Nygaard** dari Universitas Oslo-Norwegia pada tahun 1966 dalam sebuah jurnal yang berjudul “_SIMULA An Algol Based Simulation Language_”.

# 2. **Pemrograman Berorientasi Objek**

Pemrograman Berorientasi Objek (PBO) adalah paradigma pemrograman yang berfokus pada objek-objek sebagai dasar pengembangan perangkat lunak. Setiap objek merepresentasikan entitas di dunia nyata yang memiliki atribut (properti atau data) dan perilaku (metode atau fungsi). PBO memfasilitasi pengorganisasian kode dengan membagi program menjadi objek-objek yang saling berinteraksi.
# 3. **Empat Pilar Pemrograman Berorientasi Objek**

Empat pilar konsep berorientasi objek, yaitu:  
- Abstraksi (_Abstraction_).  
- Pewarisan (_Inheritance_).  
- Pembungkusan (_Encapsulation_).  
- Banyak bentuk (_Polymorphism_).

![Gambar 1](https://github.com/ThesionMS/Materi_Enkapsulasi_Java/raw/main/Gambar/Pasted%20image%2020241018111630.png)



Empat pilar inilah yang menjadi inti dari konsep pemrograman berorientasi objek, empat pilar tersebut harus didukung secara penuh oleh bahasa pemrograman. Hampir semua bahasa pemrograman yang ada saat ini mendukung secara penuh konsep pemrograman berorientasi objek.


# 4. OOP : Memahami Object Class Properti dan Method
OOP merupakan cara yang paling efisien untuk menulis program komputer yang sangat mudah untuk dikombinasikan dan untuk dipergunakan kembali. OOP lebih memfokuskan kepada manipulasi object. Kenapa seorang programmer harus mempelajari OOP, karena suatu saat nanti semua bahasa pemograman akan menambahkan kemampuan OOP pada bahasanya.

Selanjutnya kita akan membahas beberapa konsep dasar yang biasanya terdapat pada bahasa pemograman yang mendukung OOP :

![Gambar 2](https://github.com/ThesionMS/Materi_Enkapsulasi_Java/blob/main/Gambar/Pasted%20image%2020241020130829.png)

**Object**

Object merupakan segala sesuatu yang dapat dibedakan satu sama lain. Contohnya : manusia, mobil, hewan, tumbuhan, tempat atau bahkan tidak bersifat fisik seperti kejadian atau konsep. Dalam OOP Object berfungsi untuk membungkus data dan fungsi bersama menjadi satu unit dalam sebuah program komputer. Object merupakan dasar dari modularitas dan struktur yang berorientasi object. Object memiliki 2 ciri yaitu Atribut dan Method.

Ilustrasi : Object -> Manusia  
Atribut : tinggi, umur, berat.  
Method : jalan, lari lompat.

**Class**

Class merupakan tempalate untuk membuat object berupa kumpulan atas definisi data dan fungsi dalam suatu unit untuk suatu tujuan tertentu. Contohnya class of cat mendefinisikan suatu unit yang terdiri atas definisi-definisi data dan fungsi-fungsi yang menunjuk pada beberapa macam prilaku/turunan dari kucing.

**Properti**

Properti atau Atribut adalah data yang membedakan antara object satu dengan yang lainnya. Contohnya Object Manusia yang memiliki Atribut : tinggi, umur, dan berat.

Dalam class Atribut sering disebut dengan variabel. Atribut dibagi menjadi 2 yaitu : Instance variabel dan Class variabel.

**Method**

Method atau disebut juga tingkah laku adalah hal-hal yang bisa dilakukan object dari suatu Class. Method dapat digunakan untuk mengubah nilai atribut suatu object, menerima informasi dari object lain, dan mengirim informasi dari object lain. Cara object berkomunikasi dengan object lain adalah dengan menggunakan method.

![OOP-Memahami-Object-Class-Properti-dan-Method](http://www.dumetschool.com/images/fck/class.png)

# 5. Enkapsulasi

**Enkapsulasi** adalah salah satu pilar utama dalam pemrograman berorientasi objek (OOP) yang berfungsi untuk membungkus data (variabel) dan metode (fungsi) dalam satu unit atau objek. Tujuan dari enkapsulasi adalah untuk menyembunyikan detail implementasi suatu objek dari objek lainnya dan hanya memperlihatkan informasi yang diperlukan melalui antarmuka publik (public interface). Dengan demikian, akses ke data sensitif atau kritis dapat dibatasi melalui mekanisme pembatasan akses, seperti penggunaan modifier _private_, _public_, atau _protected_.Berikut adalah manfaat utama dari enkapsulasi:

1. **Keamanan**: Data sensitif disembunyikan, mencegah akses dan manipulasi yang tidak diinginkan.
2. **Modularitas**: Kode dapat diorganisir menjadi unit yang lebih kecil, memudahkan pemeliharaan dan pengembangan.
3. **Penggunaan Kembali**: Kelas yang dienkapsulasi dapat digunakan kembali tanpa khawatir mengubah basis kode lainnya.
4. **Kemudahan Pengujian**: Kode yang dienkapsulasi lebih mudah diuji karena metode dapat diuji secara independen.
5. **Kontrol Akses**: Mengontrol akses ke atribut dan metode, menjadikannya _read-only_ atau _write-only_ sesuai kebutuhan.  

**Enkapsulasi** (encapsulation) merupakan cara untuk melindungi property (atribut) / method
tertentu dari sebuah kelas agar tidak sembarangan diakses dan dimodifikasi oleh suatu bagian
program. Cara untuk melindungi data yaitu dengan menggunakan access modifiers (hak akses).
Ada 4 hak akses yang tersedia, yaitu default, public, protected, private.

Untuk lebih jelasnya, silahkan lihat kedua table berikut ini :
![[Pasted image 20241018113049.png]]

### Proses encapsulation terdiri dari langkah-langkah berikut :

- Identifikasi data dan fungsi yang perlu dienkapsulasi. Pada langkah ini, programmer perlu memahami masalah yang ingin diselesaikan, data yang perlu disimpan, dan fungsi yang perlu dilakukan.
- Buat kelas untuk mengkapsulasi data dan fungsi. Kelas harus memiliki bagian privat untuk menyimpan data dan bagian publik untuk menampilkan fungsi.
- Deklarasikan data anggota sebagai pribadi . Hal ini akan mencegah kode lain mengakses data anggota secara langsung.
- Buat metode publik untuk mengakses dan memodifikasi data anggota. Metode ini harus digunakan untuk melindungi data dari akses dan modifikasi yang tidak sah.


![[Pasted image 20241019212213.png]]

Enkapsulasi 1 Perhatikan kode program berikut:
![[Pasted image 20241020132623.png]]

Yang di garis bawahi pada kode di atas adalah modifier. Modifier ini nanti akan menentukan batasan akses member dan class.

## **5.1 Modifier di dalam Java**

Secara umum ada 3 macam modifier yang digunakan dalam Java, yaitu public, private dan protected. Apabila kita tidak menggunakan tiga kata kunci tersebut, maka member atau class itu tidak menggunakan modifier (no modifier). Masing-masing modifier akan menentukan di mana saja member bisa diakses.

Berikut ini tabel jangkauan untuk masing-masing modifier:

![[Pasted image 20241020133105.png]]

Pada tabel di atas apabila kita tidak menggunakan modifier (no modifier), maka class dan member hanya akan bisa diakses dari Class itu sendiri dan package (class yang berada satu package dengannya). Agar bisa diakses dari mana saja, maka kita harus memberikan modifier public.

Berikut adalah penjelasan dari 3 modifier di dalam enkapsulasi :

### 1. Public
Modifier public akan membuat member dan class bisa di akses dari mana saja, contoh:
```java
package belajarjava;

class Person {
    public String name;

    public void changeName(String newName) {
        this.name = newName;
    }
}
```

```java

```
Pada class Person terdapat dua member, yaitu:
- atribut name
- method changeName()
Kedua member tersebut kita berikan modifier public, artinya mereka akan bisa diakses dari mana saja. Namun, class Person tidak kita berikan modifier. Maka yang akan terjadi adalah class tersebut tidak akan bisa diimpor (diakses) dari luar package.
![[Pasted image 20241020133643.png]]
Class Person berada di dalam package belajarjava, lalu kita coba akses dari Author.java yang berada dalam package latihan, maka yang akan terjadi adalah error seperti gambar di atas. Solusinya supaya bisa diakses dari luar package, kita harus menambahkan modifier public ke dalam class Person.

Maka error akan menghilang dan class Person bisa diimpor dari package manapun. Pada class diagram, modifier public digambarkan dengan simbol plus (+), contoh:

```java
package belajarjava;

public class Person {
    public String name;

    public void changeName(String newName) {
        this.name = newName;
    }
}
```
Semua member dalam class Player memiliki modifier public, perhatikan simbol + yang ada di depannya
![[Pasted image 20241020133835.png]]

### 2. Private

Modifier private akan membuat member hanya bisa diakses dari dalam class itu sendiri. Yang perlu diingat modifier private tidak bisa diberikan kepada class, enum dan interface. Contoh:

```java
package belajarjava;

public class Person {
    private String name;

    public void setName(String name) {
        this.name = name;
    }

    public String getName() {
        return this.name;
    }
}

```

Pada contoh di atas, kita memberikan modifier private pada atribut name dan modifier public pada method setName() dan getName(). Apabila kita coba mengakses langsung atribut name seperti ini:
```java
Person mPerson = new Person();
mPerson.name = "Agus Suratna"; // Akan menghasilkan error
```
Maka Hasilnya akan error seperti berikut:
![[Pasted image 20241020134254.png]]

Supaya bisa mengakses member private dari luar class, kita bisa memanfaatkan method setter dan getter. Karena method ini akan selalu diberikan modifier public.
![[Pasted image 20241020134313.png]]

Contoh untuk mengakses method setter dan getter dari modifier Private :
```java
package belajarjava;

public class BelajarJava {

    public static void main(String[] args) {
        Person mPerson = new Person();
        mPerson.setName("Agus Suratna");
        
        System.out.println("Nama Orang : " + mPerson.getName());
    }
}
```

Pada class diagram, modifier private digambarkan dengan simbol minus(-)
![[Pasted image 20241020134443.png]]

### 3. Protected

Modifier protected akan membuat member dan class hanya bisa diakses dari:
• Class itu sendiri;
• Sub class atau class anak;
• Package (class yang berada satu package dengannya).

Modifier protected juga hanya boleh digunakan pada member saja.
Contoh:
```java
package belajarjava;

public class Person {
    protected String name; 
    
    public void setName(String name){ 
        this.name = name; 
    }
    
    public String getName(){
        return this.name;
    }
}
```

Pada contoh di atas, kita memberikan modifier protected pada atribut name. Apabila kita coba mengakses dari class yang satu package dengannya, maka tidak akan terjadi error. Namun, apabila kita mencoba mengakses dari luar package (package yang berbeda) seperti ini:
```java
import belajarjava.Person;

package latihan;

public class Author {
    
    Person p = new Person();
    
    public Author(){       
        p.name="Agus Suratna";
    }
}
```

Maka akan terjadi error
![[Pasted image 20241020134710.png]]

Pada class diagram (di StarUML), modifier protected digambarkan dengan tanda pagar(#)
![[Pasted image 20241020134816.png]]

## **5.2 Setter dan Getter**

### **1. Pengertian**

- **Setter** dan **Getter** adalah metode yang digunakan untuk **mengatur (set)** dan **mengambil (get)** nilai dari atribut privat dalam sebuah kelas di pemrograman berorientasi objek (OOP).
- **Getter** digunakan untuk **mengambil** nilai dari variabel privat.
- **Setter** digunakan untuk **mengatur** atau mengubah nilai dari variabel privat.

Dengan menggunakan **setter** dan **getter**, data di dalam suatu objek dapat terlindungi dan dikendalikan, sehingga hanya bisa diakses atau diubah dengan cara yang benar melalui metode tertentu.

### **2. Tujuan Setter dan Getter**

1. **Enkapsulasi Data**: Melindungi data agar tidak bisa diakses atau dimodifikasi secara langsung dari luar kelas. Ini memastikan bahwa perubahan atau akses ke data dilakukan dengan aturan yang benar.
    
2. **Validasi**: Pada metode **setter**, dapat dilakukan validasi sebelum mengubah nilai variabel. Hal ini memungkinkan pengaturan nilai sesuai dengan aturan tertentu.
    
3. **Kontrol Akses**: Dengan **getter** dan **setter**, kita bisa membatasi variabel mana yang dapat diakses (baca) dan mana yang dapat diubah (tulis).
    
4. **Pemeliharaan Kode**: Meningkatkan fleksibilitas dan pemeliharaan kode karena implementasi internal dapat berubah tanpa harus mengubah bagian kode yang memanggil metode tersebut.

### **3. Contoh Kode Setter dan Getter dalam Java**

```java
class Person {
    // Atribut privat
    private String name;
    private int age;

    // Setter untuk mengatur nilai 'name'
    public void setName(String name) {
        this.name = name;  // Mengatur nilai atribut name
    }

    // Getter untuk mengambil nilai 'name'
    public String getName() {
        return name;  // Mengembalikan nilai atribut name
    }

    // Setter untuk mengatur nilai 'age'
    public void setAge(int age) {
        if (age > 0) {  // Validasi, hanya usia positif yang diterima
            this.age = age;
        }
    }

    // Getter untuk mengambil nilai 'age'
    public int getAge() {
        return age;  // Mengembalikan nilai atribut age
    }
}

public class Main {
    public static void main(String[] args) {
        // Membuat objek dari kelas Person
        Person person = new Person();

        // Menggunakan setter untuk mengatur nilai
        person.setName("John");
        person.setAge(30);

        // Menggunakan getter untuk mendapatkan dan mencetak nilai
        System.out.println("Name: " + person.getName());
        System.out.println("Age: " + person.getAge());
    }
}

```

### **4. Penjelasan Kode**

- **Atribut privat**: `name` dan `age` adalah variabel dalam kelas `Person` yang bersifat privat, artinya variabel ini tidak bisa diakses secara langsung dari luar kelas.
    
- **Setter (`setName` dan `setAge`)**:
    
    - `setName(String name)`: Metode ini digunakan untuk mengatur atau memberi nilai pada variabel `name` dari luar kelas.
    - `setAge(int age)`: Metode ini digunakan untuk mengatur nilai `age`, dengan pengecekan (validasi) agar hanya menerima nilai yang lebih besar dari 0. Jika nilai tidak valid, usia tidak diubah.
- **Getter (`getName` dan `getAge`)**:
    
    - `getName()`: Metode ini digunakan untuk mengembalikan atau mendapatkan nilai `name`.
    - `getAge()`: Metode ini digunakan untuk mengambil nilai `age`.
- **Objek `Person` dalam `Main`**:
    
    - Kita membuat objek `Person` dengan nama `person`, lalu menggunakan metode setter untuk mengatur nama dan usia.
    - Metode getter digunakan untuk mengambil nilai `name` dan `age` yang kemudian dicetak di konsol.

# Referensi

https://github.com/Monashr/PBO-2024-main/blob/master/W03_Enkapsulasi/Materi.md
https://medium.com/@harafsan22/enkapsulasi-pengertian-contoh-dan-manfaatnya-292287d8f406
https://agussuratna.net/2023/02/tutorial-java-enkapsulasi-encapsulation-pada-pemrograman-berorientasi-objek/
https://medium.com/@thoyibatulmaulidaaa/mengenal-materi-oop-encapsulation-d31df670e4aa
https://medium.com/@ignsuryantara/pengantar-pemrograman-berorientasi-objek-dengan-java-85535865faa9
https://drive.google.com/file/d/1JTYkRY_neYQh2kXkgvSYvux7RUDVU6Mu/view
[OOP : Memahami Object Class Properti dan Method](https://www.dumetschool.com/blog/OOP-Memahami-Object-Class-Properti-dan-Method)
