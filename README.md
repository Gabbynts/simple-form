# simple-form

Google Apps Script adalah platform pengembangan skrip yang disediakan oleh Google untuk mengotomatiskan tugas-tugas di berbagai produk Google Workspace (sebelumnya dikenal sebagai G Suite), seperti Google Sheets, Google Docs, dan Google Drive. Google Apps Script menggunakan JavaScript sebagai bahasa pemrogramannya dan memungkinkan pengguna untuk membuat skrip yang berjalan di cloud untuk mengotomatiskan berbagai tindakan, mulai dari pengolahan data hingga membuat formulir khusus.


Untuk menghubungkan formulir HTML-CSS dengan Google Sheets menggunakan Google Apps Script, dapat mengikuti langkah-langkah berikut:

- Buat Formulir HTML-CSS:

Buat formulir HTML-CSS sederhana yang akan digunakan untuk mengumpulkan data. Pastikan formulir tersebut memiliki elemen-elemen seperti input, textarea, dan tombol kirim.

```
<body>
    <div>
      <form
        method="post"
        action="https://script.google.com/macros/s/AKfycbytjnl8L3bq1Mva38BHPlBrrDEQLNW-f5FJr1pHQoAGkV0_Bz5iaIxUPS0tZKQ-dA795A/exec"
      >
        <h2>Send Your Messages!</h2>
        <input type="text" name="Name" placeholder="Name" />
        <input type="email" name="Email" placeholder="Email" />
        <input type="text" name="Phone" placeholder="Phone" />
        <textarea name="Message" placeholder="Enter Your Message"></textarea>
        <input type="submit" value="Send" id="submit" />
      </form>
    </div>
  </body>
```

![alt](/images/2.jpg)

- Buat Spreadsheet Google Sheets:

Buat spreadsheet di Google Sheets yang akan digunakan untuk menyimpan respons dari formulir. Pastikan spreadsheet memiliki kolom-kolom yang sesuai dengan data yang ingin Anda simpan.

![alt](/images/1.jpg)

- Buat Google Apps Script

![alt](/images/3.jpg)

Hasil dari form yang diisi akan masuk otomatis ke spreadsheet yang sudah dibuat

![alt](/images/4.jpg)