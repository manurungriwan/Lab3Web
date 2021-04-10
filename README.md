# Lab3Web

Instruksi Praktikum 
1.	Persiapkan text editor misalnya VSCode. 
2.	Buat folder baru dengan nama Lab3Web 
3.	Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya. 
4.	Lakukan validasi dokumen html dengan mengakses http://validator.w3.org  
Langkah-langkah Praktikum 	
Persiapan membuat dokumen HTML dengan nama file lab3_list.html seperti berikut. 
(<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>HTML Lanjutan</title> 
</head> 
<body> 
    <header> 
        <h1>Membuat List</h1> 
    </header> 
</body> 
</html> 
)

![1](https://user-images.githubusercontent.com/56192368/114275022-2477fc80-9a4b-11eb-927c-00e682f80e5b.JPG)

Membuat Unorderd List:

Kemudian tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada section unordered-list, seperti berikut. 

(<section id="unorder-list"> 
    <h2>Unordered List</h2> 
    <ul type="square"> 
        <li>Jaringan Komputer</li> 
        <li>Struktur Data</li> 
        <li>Algoritma &amp; Pemrograman</li> 
    </ul> 	
</section>) 

![2](https://user-images.githubusercontent.com/56192368/114275142-95b7af80-9a4b-11eb-9567-16c3c981fb61.JPG)


 
Membuat Description List:

Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list. 

{<section id="unorder-list"> 
    <h2>Description List</h2> 
    <dl> 
        <dt>Fakultas Teknik</dt> 
        <dd>Teknik Industri</dd> 
        <dd>Teknik Informatika</dd> 
        <dd>Teknik Lingkungan</dd> 
        <dt>Fakultas Ekonomi dan Bisnis</dt> 
        <dd>Akuntansi</dd> 
        <dd>Manajemen</dd> 
        <dd>Bisnis Digital</dd> 
    </dl> 
</section>}

![3](https://user-images.githubusercontent.com/56192368/114275191-c697e480-9a4b-11eb-9b7d-5137aec82bfe.JPG)

Selanjutnya lakukan eksperimen lain terkait list dan penggunaan atribut type pada list. 

Membuat Tabel: 

Buat file baru dengan nama lab3_tabel.html seperti berikut. 
{<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>HTML Lanjutan</title> 
</head> 
<body> 
    <header> 
        <h1>Membuat Table</h1> 
    </header> 
</body> 	
</html>}

Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut: 

{<table border="1" cellpadding="4" cellspacing="0"> 
    <thead> 	
        <tr> 
            <th>No.</th> 
            <th>Fakultas</th> 
            <th>Program Studi</th> 
        </tr> 
    </thead>     <tbody> 
        <tr> 
            <td>1.</td> 
            <td>Teknik</td> 
            <td>Teknik Informatika</td> 
        </tr> 
        <tr> 
            <td>2.</td> 
            <td>Teknik</td> 
            <td>Teknik Industri</td> 
        </tr> 
        <tr> 
            <td>3.</td> 
            <td>Teknik</td> 
            <td>Teknik Lingkungan</td> 
        </tr> 
    </tbody> 
</table>}

KEMUDIAN MASUK KEMBALI KE FIREFOX:

![4](https://user-images.githubusercontent.com/56192368/114275264-11b1f780-9a4c-11eb-9398-5440d6bfddf3.JPG)

Mengatur Margin dan Padding:

Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan cellspacing pada tag table. 

{<table border="1" cellpadding="4" cellspacing="0">}
  
  ![4](https://user-images.githubusercontent.com/56192368/114275339-681f3600-9a4c-11eb-8389-722afcfb42f2.JPG)
  
  
 Menggabungkan Sel Data:
 
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara horizontal).  

{<table border="1" cellpadding="6" cellspacing="0"> 
    <thead> 
        <tr> 
            <th>No.</th> 
            <th>Fakultas</th> 
            <th>Program Studi</th> 
        </tr> 
    </thead>     <tbody> 
        <tr> 
            <td>1.</td> 
            <td rowspan="3">Teknik</td> 
            <td>Teknik Informatika</td> 
        </tr> 
        <tr> 
            <td>2.</td> 
            <td>Teknik Industri</td> 
        </tr> 
        <tr> 
            <td>3.</td> 
            <td>Teknik Lingkungan</td> 
        </tr> 
    </tbody> 
</table>}

REFRESH KEMBALI PADA FIREFOXNYA HASILNYA SEPERTI BERIKUT:


![5](https://user-images.githubusercontent.com/56192368/114275383-9ef54c00-9a4c-11eb-9b05-01501e0f01cf.JPG)

Membuat Form :

Buat file baru dengan nama lab3_form.html seperti berikut. 	

{<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>HTML Lanjutan</title> 
</head> 
<body> 
    <header> 
        <h1>Membuat Form</h1> 
    </header> 
</body> 
</html>}
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut: 

{<form action="proses.php" method="post"> 
    <fieldset> 
        <legend>Data Pelanggan</legend> 
        <p> 
            <label for="nama">Nama</label> 
            <input type="text" id="nama" name="nama"> 
        </p> 
        <p> 	
            <label for="alamat">Alamat</label> 
            <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>         </p> 
        <p> 
            <label>Jenis Kelamin</label> 
            <input id="jk_l" type="radio" name="kelamin" value="L" /><label for="jk_l">Laki-laki</label>  
            <input id="jk_p" type="radio" name="kelamin" value="P" /><label for="jk_p">Perempuan</label> 
        </p> 
        <p><input type="submit" value="Login"></p> 
    </fieldset> 
</form>}

MASUK Lagi pada firefoxnya:

![6](https://user-images.githubusercontent.com/56192368/114275489-dc59d980-9a4c-11eb-9875-5c8afcb8ae20.JPG)


Menabahkan Style pada Form :

Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut. 

{<style> 
    form p > label {         display: inline-block;         width: 100px; 
    
    form input[type="text"], form textarea {         border: 1px solid #197a43; 
    } 
    form input[type="submit"] {         border: 1px solid #197a43;         background-color: #197a43;         color: #ffffff;         font-weight: bold;         padding: 5px 15px; 
    } 
</style>}

UNTUK HASIlnya mari kita refresh kembali pada firefox:

![7](https://user-images.githubusercontent.com/56192368/114275557-365a9f00-9a4d-11eb-9905-1cddfd90d4b8.JPG)


Pertanyaan dan Tugas 
1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection. 

JAWABANYA:

![10](https://user-images.githubusercontent.com/56192368/114275581-51c5aa00-9a4d-11eb-86f0-70db79d010e5.JPG)











  





