# Praktikum 3 - Pemrograman Web
```
Luro Lumbantoruan 
311910210
TI.19.b.1
```
## LANGKAH 1
### Membuat dokumen HTML dengan nama file lab3_list.html. Setelah itu buat struktur dasar HTML
```
<!DOCTYPE html>
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
```
![1](https://user-images.githubusercontent.com/82386899/114399114-c540f600-9bca-11eb-93c1-14d3318dd031.png)
## LANGKAH 2
### Membuat Ordered List
```
<section id="order-list">
    <h2>Ordered List</h2>
    <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Informasi</li>
    <li>Basis Data 2</li>
    </ol>
  </section>
  ```
  ![2](https://user-images.githubusercontent.com/82386899/114399505-2e286e00-9bcb-11eb-8f05-a05af0a0c99b.png)
  ## LANGKAH 3
  ### Membuat Unordered List
  ```
  <section id="unorder-list">
    <h2>Unordered List</h2>
    <ul type="square">
    <li>Jaringan Komputer</li>
    <li>Struktur Data</li>
    <li>Algoritma &amp; Pemrograman</li>
    </ul>
   </section>
```
![3](https://user-images.githubusercontent.com/82386899/114399914-a42cd500-9bcb-11eb-8d95-40060df679dd.png)
## LANGKAH 4
### Membuat Description List
```
<section id="unorder-list">
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
</section>
```
![4](https://user-images.githubusercontent.com/82386899/114400419-23baa400-9bcc-11eb-8b31-c3aa589b5807.png)
## LANGKAH 5
### Membuat dokumen HTML baru dengan nama file lab3_tabel.html. Setelah itu buat struktur dasar HTML
```
<!DOCTYPE html>
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
</html>
```
![5](https://user-images.githubusercontent.com/82386899/114400969-b0fdf880-9bcc-11eb-9b7b-7dde60923473.png)
## LANGKAH 6
### Membuat tabel dan mengatur margin tabel
```
<table border="1" cellpadding="4" cellspacing="0">
    <thead>
        <tr>
          <th>No.</th>
          <th>Fakultas</th>
          <th>Program Studi</th>
        </tr>
   </thead>
   <tbody>
      <tr>
         <td>1.</td>
         <td>Teknik</td>
         <td>Teknik Informatika</td>
      </tr>
      <tr>
         <td>2.</td>
         <td>Tekni![6](https://user-images.githubusercontent.com/82386899/114401501-2cf84080-9bcd-11eb-9fec-d1ed8add99ee.png)
k</td>
         <td>Teknik Industri</td>
      </tr>
      <tr>
         <td>3.</td>
         <td>Teknik</td>
         <td>Teknik Lingkungan</td>
      </tr>
   </tbody>
  </table>
```
![6](https://user-images.githubusercontent.com/82386899/114401528-34b7e500-9bcd-11eb-8db4-2a4b6678a7a5.png)
## LANGKAH 7
### Menggabungkan Sel Data
```
<table border="1" cellpadding="6" cellspacing="0">
    <thead>
      <tr>
        <th>No.</th>
        <th>Fakultas</th>
        <th>Program Studi</th>
      </tr>
    </thead>
    <tbody>
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
   </table>
```
![7](https://user-images.githubusercontent.com/82386899/114402315-e525e900-9bcd-11eb-9c94-49be73ead80a.png)
## LANGKAH 8
### Membuat dokumen HTML baru dengan nama file lab3_form.html dan Buat Tabel
```
<!DOCTYPE html>
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
<form action="proses.php" method="post">
    <fieldset>
    <legend>Data Pelanggan</legend>
    <p>
    <label for="nama">Nama</label>
    <input type="text" id="nama" name="nama">
    </p>
    <p>
    <label for="alamat">Alamat</label>
   <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
    </p>
   <p>
   <label>Jenis Kelamin</label>
   <input id="jk_l" type="radio" name="kelamin" value="L" /><label
   for="jk_l">Laki-laki</label>
    <input id="jk_p" type="radio" name="kelamin" value="P" /><label
    for="jk_p">Perempuan</label>
   </p>
   <p><input type="submit" value="Login"></p>
   </fieldset>
</form>
</body>
</html>
```
![8](https://user-images.githubusercontent.com/82386899/114403047-a2b0dc00-9bce-11eb-990b-1d4bfccdf3a9.png)
## LANGKAH 9
### Menambahkan style pada form agar tampilan lebih menarik menggunakan CSS
```
<style>
        form p > label {
        display: inline-block;
        width: 100px;
        }
        form input[type="text"], form textarea {
        border: 1px solid #197a43;
        }
        form input[type="submit"] {
        border: 1px solid #197a43;
        background-color: #197a43;
        color: #ffffff;
        font-weight: bold;
        padding: 5px 15px;
        }
    </style>
```
![9](https://user-images.githubusercontent.com/82386899/114403906-6631b000-9bcf-11eb-8472-92fb8af055c4.png)
# TUGAS
## Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
### Membuat Dropdown Menu dan Listbox dengan multiple selection
```
<!DOCTYPE html>
<html>
<head>
	<title>HTML Lanjutan</title>
</head>
<body>
 
	<style type="text/css">
	html,body{
		padding: 0;
		margin:0;
		font-family: sans-serif;
	}
 
	.menu{
		background-color: #ff002b;
	}
 
	.menu ul {
		list-style-type: none;
		margin: 0;
		padding: 0;
		overflow: hidden;
	}
 
	.menu > ul > li {
		float: left;
	}
 
	
	.menu li a {
		display: inline-block;
		color: white;
		text-align: center;
		padding: 14px 16px;
		text-decoration: none;
	}
 
	.menu li a:hover{
		background-color: #ff002b;
	}
 
	li.dropdown {
		display: inline-block;
	}
 
	.dropdown:hover .isi-dropdown {
		display: block;
	}
 
	.isi-dropdown a:hover {
		color: #fff !important;
	}
 
	.isi-dropdown {
		position: absolute;
		display: none;
		box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
		z-index: 1;
		background-color: #f9f9f9;
	}
 
	.isi-dropdown a {
		color: #3c3c3c !important;
	}
 
	.isi-dropdown a:hover {
		color: #232323 !important;
		background: #f3f3f3 !important;
	}
</style>
 
 
<header class="header">
	<div class="menu">
 
		<ul>
			<li><a href="lab3_tugas.html">Home</a></li>
			<li class="dropdown"><a href="#">DROPDOWN MENU LAB 3 WEB</a>
				<ul class="isi-dropdown">
					<li><a href="lab3_list.html">LAB 3 LIST</a></li>
					<li><a href="lab3_tabel.html">LAB 3 TABEL</a></li>
					<li><a href="lab3_form.html">LAB 3 FORM</a></li>
				</ul>
			</li>
		</ul>
 
	</div>
</header>
 
<br/>
 
<center>
	<h1>Membuat Menu Dropdown dan Listbox</h1>
</center>

<h4>CONTOH LISTBOX</h4>
<form action="proses.php" method="get">
    <p>Suku-Suku Terbesar Di indonesia
    <select name='Suku-suku terbesar di indonesia' multiple='multiple'>
      <option value='jawa'>jawa</option>
      <option value='batak' selected='selected'>batak</option>
      <option value='sunda'>sunda</option>
    </select>
    </p>
    <input type='submit' name='tombol' value='kirim' />
</form>
</body>
</html>
```
![10](https://user-images.githubusercontent.com/82386899/114405856-44392d00-9bd1-11eb-8d1f-ecadb5a55ade.png)
![11](https://user-images.githubusercontent.com/82386899/114405833-3daab580-9bd1-11eb-8cec-accadaf3a18e.png)
