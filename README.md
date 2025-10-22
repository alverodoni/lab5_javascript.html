# lab5_javascript.html
Nama: Doni Alvero <p>
Nim: 312410663 <P>
Kelas: TI.24.A.5 <P>
Jurusan: Teknik Informatika <p>
Mata Kuliah: Pemograman Web 1 <p>

### Membuat Halaman Html
***Deskripsi:**
Halaman tersebut menampilkan judul "Pengenalan JavaScript" dan output "Hello World", yang kemungkinan dihasilkan oleh kode JavaScript yang menggunakan fungsi `$document.write()$`, sebagai contoh dari sub-judul yang disebutkan: "Contoh document.write dan console.log".
<img width="1918" height="1021" alt="Html" src="https://github.com/user-attachments/assets/214b5a06-246f-4bef-99b3-1f31fb538858" />

### Membuat Halaman JavaScrip Dasar (Pemakaian Alert sebagai property window & Pemakaian method dalam objek)
***Deskripsi:**
Tujuannya untuk menunjukkan cara menggunakan fitur bawaan browser seperti kotak tanya jawab `(prompt())` agar pengguna bisa berinteraksi (memasukkan nama atau data lain). Latihan ini juga mengenalkan dua bagian penting dalam JavaScript: `window` (yang mengatur tampilan jendela browser) dan `document` (yang mengatur isi halaman web)
<img width="1918" height="1017" alt="Pemakaian Alert sebagai property window   Pemakaian method dalam objek" src="https://github.com/user-attachments/assets/d88b4e54-74c7-4da2-bc88-4d519fbe13d7" />

### Membuat Halaman JavaScrip (Pemakaian Prompt & Pembuatan fungsi dan cara pemanggilannya)
***Deskripsi:**
Halaman web ini adalah contoh latihan berinteraksi. Kita bisa masukkan data atau nama pakai kotak tanya jawab `(prompt)`, lalu kita bisa klik tombol `(arithmetic)` untuk menjalankan kode JavaScript dan melihat hasilnya. Jadi, ini menggabungkan cara menerima masukan dari pengguna dan cara menjalankan perintah (seperti hitung-hitungan) hanya dengan menekan tombol."
<img width="1918" height="1018" alt="Pemakaian Prompt" src="https://github.com/user-attachments/assets/57764f92-0af0-4e2e-b11a-dcc94a12d57f" />
<img width="1918" height="1020" alt="Pemakaian Prompt2" src="https://github.com/user-attachments/assets/9f14cc01-d8c6-4d78-a0a1-d30036c86717" />
<img width="1916" height="1017" alt="Pemakaian Prompt   Pembuatan fungsi dan cara pemanggilannya" src="https://github.com/user-attachments/assets/ffbd6feb-549b-459c-ac07-42e628ee1182" />

### Membuat Halaman JavaScrip (dasar aritmatika & kondisi (if..else))
***Deskripsi:**
halaman ini menggabungkan input pengguna, logika keputusan (if...else), dan persiapan eksekusi fungsi hitungan (aritmatika) dalam satu latihan JavaScript.
<img width="1918" height="1018" alt="Kondisi If-Else1" src="https://github.com/user-attachments/assets/fe598080-f146-4503-aaf3-dc63fa136fd2" />
<img width="1918" height="1017" alt="Kondisi If-Else" src="https://github.com/user-attachments/assets/68c3e8b6-d0e0-44e4-83fe-54e9c2e4304a" />

### Membuat Halaman JavaScrip (Penggunaan operator switch untuk seleksi kondisi)
***Deskripsi:**
Halaman ini mengajarkan dua metode utama bagi program untuk memilih tindakan yang harus dilakukan, dan kita bisa mencoba menjalankan kedua metode itu hanya dengan mengklik tombol, (Pakai if...else Ini seperti bertanya, 'Jika ini benar, lakukan A. Kalau tidak, lakukan B.' (Hasilnya sudah terlihat: 'tidak lulus')) & (Pakai switch case Ini seperti mencari kecocokan: 'Lihat nilainya. Kalau nilainya 1, lakukan X. Kalau nilainya 2, lakukan Y)
<img width="1918" height="1017" alt="Switch" src="https://github.com/user-attachments/assets/ce120329-46f5-4ea3-a05c-2ca0bd0e012f" />

### Membuat Halaman JavaScrip (Form Input & Form Button)
***Deskripsi:**
halaman ini adalah latihan JavaScript yang fokus pada pengambilan input dari form `(<input type="text">)` dan penggunaan button `(<input type="button">)` untuk mengontrol logika program (seperti cek genap/ganjil) dan mengubah tampilan halaman web (seperti ubah warna).
<img width="1918" height="1018" alt="Form Input   Form Button" src="https://github.com/user-attachments/assets/c1305a42-cb8d-4a0b-b1f8-c24f28cf9992" />

### Membuat Halaman JavaScrip (HTML DOM)
***Deskripsi:**
Konsep DOM memungkinkan halaman web menjadi dinamis dan interaktif, seperti contoh kasir sederhana yang menghitung total belanjaan Anda secara langsung saat Anda mencentang item, setiap kali mencentang (memilih) menu makanan yang Anda inginkan.
<img width="1918" height="1016" alt="Html Dom" src="https://github.com/user-attachments/assets/82aa72cf-a801-44ff-ad51-969a3fdad041" />

### codingan hmtl, css, & javascrip yang telah dimodifikasi
```html
<!DOCTYPE html>
<html lang="en">
<head>
<title>JavaScript Showcase: Form, DOM, dan Fungsi Dasar</title>
<style>
    /* Styling Dasar untuk tampilan yang lebih menarik */
    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        padding: 20px;
        margin: 0;
        transition: background-color 0.5s, color 0.5s; /* Animasi transisi warna */
    }
    h1 {
        text-align: center; /* JUDUL DI TENGAH */
        border-bottom: 2px solid #ccc;
        padding-bottom: 5px;
        color: #333;
    }
    h2 {
        border-bottom: 2px solid #ccc;
        padding-bottom: 5px;
        color: #333;
    }
    .card {
        border: 1px solid #ddd;
        border-radius: 8px;
        padding: 15px;
        margin-bottom: 20px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        background-color: #f9f9f9;
    }
    .menu-item, .input-group, .button-group {
        margin-bottom: 10px;
    }
    input[type="text"], input[type="number"], input[type="button"] {
        padding: 8px;
        border-radius: 4px;
        border: 1px solid #ccc;
    }
    input[type="button"] {
        cursor: pointer;
        background-color: #007bff;
        color: white;
        border: none;
        margin-right: 5px;
    }
    input[type="button"]:hover {
        opacity: 0.9;
    }
    .arithmetic-btn, .switch-btn {
        background-color: #dc3545; /* Merah */
        font-weight: bold;
    }
</style>

<script language="javascript">
// FUNGSI 1: ARITMATIKA
function hitungAritmatika() {
    var val1 = parseInt(document.getElementById('arithmeticVal1').value);
    var val2 = parseInt(document.getElementById('arithmeticVal2').value);

    if (isNaN(val1) || isNaN(val2)) {
        alert("Masukkan angka yang valid untuk operasi aritmatika.");
        return;
    }
    
    // Menampilkan hasil di window baru
    var output = "<b>--- Hasil Operasi Aritmatika (" + val1 + ", " + val2 + ") ---</b>";
    output += "<br><br>+ perkalian : val1*val2 = " + (val1 * val2);
    output += "<br>+ pembagian : val1/val2 = " + (val1 / val2);
    output += "<br>+ penjumlahan : val1+val2 = " + (val1 + val2); 
    output += "<br>+ pengurangan : val1-val2 = " + (val1 - val2);
    output += "<br>+ modulus : val1%val2 = " + (val1 % val2);
    
    var newWindow = window.open("", "Aritmatika", "width=400,height=300");
    newWindow.document.write(output);
    newWindow.document.close();
}
</script>

<script>
    function pesan() {
        alert("Selamat datang! Anda akan melihat berbagai contoh JavaScript.");
    }
</script>

<script language="javascript">
// FUNGSI 2: SWITCH CASE (Diperbaiki untuk mencakup 50-100 dengan benar)
function seleksiSwitch() { 
    var val1 = window.prompt("Input nilai (1-100) untuk diklasifikasi:");
    var angka = parseInt(val1);
    var hasil = "<b>--- Hasil Seleksi Switch ---</b><br>";

    // Memastikan input adalah angka valid 1-100
    if (isNaN(angka) || angka < 1 || angka > 100) {
        hasil += "Masukkan angka yang valid antara 1 hingga 100. Input Anda: " + val1;
    } else {
        switch (true) {
            case (angka >= 1 && angka <= 10):
                hasil += "Angka **" + angka + "** termasuk kategori: **SANGAT RENDAH (1-10)**";
                break;
            case (angka >= 11 && angka <= 50):
                hasil += "Angka **" + angka + "** termasuk kategori: **RENDAH (11-50)**";
                break;
            case (angka >= 51 && angka <= 80):
                hasil += "Angka **" + angka + "** termasuk kategori: **SEDANG (51-80)**";
                break;
            case (angka >= 81 && angka <= 100):
                hasil += "Angka **" + angka + "** termasuk kategori: **TINGGI (81-100)**";
                break;
            default:
                // Fallback, seharusnya tidak tercapai
                hasil += "Klasifikasi tidak ditemukan."; 
        }
    }
    
    // Menampilkan hasil di window baru
    var newWindow = window.open("", "SwitchCase", "width=450,height=150");
    newWindow.document.write(hasil);
    newWindow.document.close();
}
</script>

<script language="javascript">
// FUNGSI 3: FORM INPUT (Genap/Ganjil)
function test() {
    var val1 = parseInt(document.getElementById('inputT1').value);
    var resultElement = document.getElementById('inputT2');
    
    if (isNaN(val1)) {
        resultElement.value = "Input bukan angka";
        resultElement.style.backgroundColor = 'pink';
        return;
    }
    
    resultElement.style.backgroundColor = 'lightgreen';
    if ((val1 % 2) === 0) {
        resultElement.value = "BILANGAN GENAP";
    } else {
        resultElement.value = "BILANGAN GANJIL";
    }
}
</script>

<script language="javascript">
// FUNGSI 4 & 5: UBAH WARNA
function ubahWarnaLB(warna) {
    document.body.style.backgroundColor = warna;
}

function ubahWarnaLD(warna) {
    document.body.style.color = warna;
}
</script>

<script>
// FUNGSI 6: PERHITUNGAN CHECKBOX
function hitung(ele) {
    var totalElement = document.getElementById('total');
    var total = totalElement.value.replace(/[^0-9]/g, ''); // Hapus semua non-angka
    total = (total ? parseInt(total) : 0);
    
    var harga = parseInt(ele.value);
    
    if (ele.checked) {
        total += harga;
    } else {
        total -= harga;
    }
    
    totalElement.value = total.toLocaleString('id-ID'); // Format mata uang Indonesia
}
</script>

</head>
<body onload="pesan()">
<h1>Pengenalan JavaScript dan Penerapan Fungsi</h1>

---

<div class="card">
    <h2>💰 Sistem Kasir Sederhana (DOM Checkbox)</h2>
    <div class="menu-item">
        <label>
            <input type="checkbox" value="5000" onclick="hitung(this)"> **Ayam Goreng** (Rp. 5.000)
        </label>
    </div>
    <div class="menu-item">
        <label>
            <input type="checkbox" value="500" onclick="hitung(this)"> **Tahu Goreng** (Rp. 500)
        </label>
    </div>
    <div class="menu-item">
        <label>
            <input type="checkbox" value="2500" onclick="hitung(this)"> **Telur Dadar** (Rp. 2.500)
        </label>
    </div>

    <strong style="display: block; margin-top: 15px; padding: 10px; background-color: #e0f7fa; border-radius: 5px;">
        TOTAL BAYAR: Rp. <input id="total" type="text" size="10" value="0" readonly style="border: none; background-color: transparent; font-weight: bold; color: #00796b;">
    </strong>
</div>

---

<div class="card">
    <h2>🔢 Pengecek Bilangan Genap/Ganjil</h2>
    <div class="input-group">
        Masukkan Angka: <input type="text" id="inputT1" size="10">
    </div>
    <div class="input-group">
        Hasil: <input type="text" id="inputT2" size="20" readonly style="font-weight: bold;">
    </div>
    <input type="button" value="TEBAK" onclick="test()" style="background-color: #28a745;">
</div>

---

<div class="card">
    <h2>🎨 Pengubah Tampilan Halaman (Document Color)</h2>
    <div class="button-group">
        <strong>Warna Latar:</strong>
        <input type="button" value="Hijau" onclick="ubahWarnaLB('GREEN')" style="background-color: green;">
        <input type="button" value="Putih" onclick="ubahWarnaLB('WHITE')" style="background-color: white; color: black; border: 1px solid #ccc;">
        <input type="button" value="Hitam" onclick="ubahWarnaLB('BLACK')" style="background-color: black;">
    </div>
    <div class="button-group">
        <strong>Warna Teks:</strong>
        <input type="button" value="Abu-abu" onclick="ubahWarnaLD('GRAY')" style="background-color: gray; color: white;">
        <input type="button" value="Biru" onclick="ubahWarnaLD('BLUE')" style="background-color: blue;">
        <input type="button" value="Hitam" onclick="ubahWarnaLD('BLACK')" style="background-color: black;">
    </div>
</div>

---

<div class="card">
    <h2>🛠️ Pengujian Fungsi Lanjutan</h2>

    <h3>1. Operasi Aritmatika Interaktif</h3>
    <div class="input-group">
        Angka 1: <input type="number" id="arithmeticVal1" value="10" size="5">
        Angka 2: <input type="number" id="arithmeticVal2" value="5" size="5">
    </div>
    <input type="button" class="arithmetic-btn" value="RUN ARITMATIKA" onclick="hitungAritmatika()">
    <p class="small" style="color: #666; font-size: 0.9em;">(Input bilangan di atas, hasil operasi hitungan akan muncul di jendela baru)</p>

    <h3>2. Switch Case (Klasifikasi Angka 1-100)</h3>
    <input type="button" class="switch-btn" value="RUN SWITCH TEST" onclick="seleksiSwitch()">
    <p class="small" style="color: #666; font-size: 0.9em;">(Masukkan angka 1-100 melalui prompt, hasil klasifikasi akan muncul di jendela baru)</p>
    
    </div>

<footer style="margin-top: 30px; padding-top: 10px; border-top: 1px dashed #ccc; font-size: 0.8em; color: #666;">
    <script language="javascript">
    document.write("<b>Info Dokumen:</b> Dimodifikasi terakhir pada: " + document.lastModified);
    </script>
</footer>

</body>
</html>
```








