# Tutorial Membuat Markdown
### 1. Membuat Header
Untuk membuat header kita dapat menggunakan tanda `#` untuk heading 1, `##` untuk heading 2, dst sampai dengan heading 6.

Cara penulisanya dengan cara menambahkan tanda didepan kata/kalimat diikuti dengan `spasi`.
### 2. Format Teks
Untuk membuat tulisan __Bold__ dan _Italic_ ada dua cara:
* Cara Pertama dengan menggunakan tanda `__` untuk tulisan __Bold__ dan `_` untuk tulisan _Italic_.
* Cara kedua dengan menggunakan tanda `**` untuk tulisan **Bold** dan `*` untuk tulisan *Italic*.

Untuk membuat tulisan ~~Strikeline~~ dapat menggunakan tanda `~~`

Cara penulisanya dengan cara menambahkan tanda tersebut dibagian depan dan belakang kata tanpa adanya spasi didekat tanda tersebut. __*Kamu juga dapat mengkombinasikanya*__

### 3. Menyisipkan Quote
__Contoh__:
>Honesty Is The Best Policy
>>Gak usah bohong

Untuk menyisipkan quote seperti contoh tersebut dapat menggunakan tanda `>` sebelum penulisan kalimat.

### 4. Menulis Inline code
__Contoh__: Perintah `apt-get` adalah perintah untuk menginstall suatu paket di ubuntu.

Untuk membuat teks seperti contoh tersebut kita dapat menggunakan tanda " ` " didepan dan belakang tanda diikuti spasi.
### 5.Menulis Source Code
Untuk menuliskan source code hampir mirip dengan cara menulis inline code, yaitu dengan menggunakan tanda " ` " tiga kali.\
__Contoh__:
```java
class HelloWorld{
    public static void main(String[] argumen){
        System.out.println("Hello World!");
    }
}
```

### 6. Menyisipkan Link
__Contoh__: klik [disini](https://www.github.com/dekakrens) untuk mengakses Github saya.

Untuk menyisipkan link, kita dapat menulisnya seperti berikut:
```
Klik [disini](https://www.github.com/dekakrens) untuk mengakses Github saya.
```
### 7. Menyisipkan Gambar
__Contoh__: Perhatikan gambar dibawah ini:\
![Gambar](/source/sample.png)

Untuk menyisipkan gambar penulisanya hampir sama seperti menyisipkan link, hanya saja ditambah tanda `!` di depan kurung siku, seperti berikut:
```
Perhatikan gambar dibawah ini: ![Gambar](/source/sample.png)
```
### 8. Membuat List
__Contoh__:
* List Pertama
* List Kedua
 * Sub List Kedua
*List Ketiga

Untuk membuat list seperti diatas berikut kita dapat menuliskan tanda `*` atau tanda `-` diikuti tanda `spasi` di depan list yang akan kita buat.
```
* List Pertama
* List Kedua
 * Sub List Kedua
*List Ketiga
```
### 9. Membuat Checklist
__Contoh__:
Tugas Hari ini:
- [x] Belajar Markdown
- [ ] Mengerjakan PR
- [x] Upload ke [Github](https://www.github.com/)

Untuk membuat checklist seperti diatas berikut cara penulisannya:
```
Tugas Hari ini:
- [x] Belajar Markdown
- [ ] Mengerjakan PR
- [x] Upload ke [Github](https://www.github.com/)
```
### 10. Membuat Tabel
__Contoh__:
| Name | Age |
|------|-----|
| Bob  |  27 |
| Alice|  24 |

Untuk membuat tabel seperti diatas berikut cara penulisannya:
```
| Name | Age |
|------|-----|
| Bob  |  27 |
| Alice|  23 |
```
### 11. Membuat Garis Horizontal
---
Garis horizontal dapat dibuat dengan mengetikan `---`.
