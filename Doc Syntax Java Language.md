# Dokumentasi Bahasa Java
```
package com.entity.program; //<- 1. Deklarasi Package
import java.io.File; //<- 2. Impor Library
class Program { //<- 3. Bagian class
    public static void main(String args[]){
            System.out.println("Hello World");
    }
}
```
## 1. Deklarasi Package
```
package com.entity.program; //example 
```
Package adalah sebuah folder yang berisi sekumpulan program Java
Package wajib dideklarasikan
## 2. Bagian Impor
```
import java.io.File;
```
Library merupakan sekumpulan *class* File dari package java.io
## 3. Bagian Class
```
class Program {
    public static void main(String args[]){
        System.out.println("Hello World");
    }
}
```
Program harus dibungkus oleh classs agar bisa dibuat menjadi objek
blok class dibuka dengan tanda kurung kurawa { kemudian ditutup dengan }
di dalam blok class, kita dapat mengisi dengan method atau fungsi-fungsi dan juga variabel 
seperti contoh yang diatas, terdapat method main()
## 4. Method
```
public static void main(String args[]){
    System.out.println("Hello World");
}
```
Method/fungsi main() merupakan blok program yang akan dieksekusi pertama kali
Method main() wajib kita buat. Method main() harus memiliki parameter args[]. Parameter ini nanti
akan menyimpan sebuah nilai dari argumen di *command line*
### fungsi String[] args
Nah, apa itu Fungsi String {} args seperti contohnya
```
public static void main(String args[])
```
parameter **String[] args** berupa array dengan tipe data *String*
parameter ini merupakan perintah yang lebih spesifik terhadap pemanggilan function


