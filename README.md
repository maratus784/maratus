
<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portofolio ATUS</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 10px;
      padding: 10px;
      background-color: #8ca6b3;
    }
    header {
      background-color: #2e379b;
      padding: 10px;
      display: flex;
      justify-content: space-between;
      align-items:center;
      position: fixed;
      width: 100%;
      top: auto;
      top: 0;
      left: 0;
      z-index: 1000;
    }
     nav a {
      margin: 0 20px;
      text-decoration: none;
      color:black ;

    }
    .navbar a, .dropbtn {
      color: white;
      padding: 12px 16px;
      text-decoration: none;
      text-align: center;
      background: none;
      border: none;
      cursor: pointer;
    }

    .navbar a:hover, .dropdown:hover .dropbtn {
      background-color: #575757;
    }
    .dropdown {
      position: relative;
      display: inline-block;
    }

    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      min-width: 160px;
      box-shadow: 0px 8px 16px rgba(0,0,0,0.2);
      z-index: 1;
    }
    .dropdown-content a {
      color: black;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
    }

    .dropdown-content a:hover {
      background-color: #ddd;
    }

    .dropdown:hover .dropdown-content {
      display: block;
    }
    .intro {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 20px;
      flex: 1;
    }
    .intro-text {
      flex: 0 0 60%;
      text-align: left;
      padding-right: 20px;
      
    }
    .intro img {
  width: 200px;         /* bisa disesuaikan ukurannya */
  height: 200px;        /* pastikan tinggi dan lebar sama */
  object-fit: cover;    /* menjaga agar gambar tetap rapi */
  border-radius: 50%;   /* ini yang bikin jadi lingkaran */
  display: block;
  margin: 0 auto;       /* biar gambar di tengah */
}
.tentang, .portofolio, .opini, .kontak {
      padding: 10px;
      text-align: center;
    }

     .tentang img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 40%;
    }
    .tentang {
      display: flex;
      justify-content: space-between;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      border-radius: 8px;
      overflow: hidden;
    }
    th, td {
      border: 1px solid #3c16ad;
      padding: 8px;
      text-align: center;
    }
    .opini {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }
    .opini div {
      width: calc(33.333% - 10px);
      border: 1px solid #2446b4;
      text-align: center;
    }
    .opini img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }
    .kontak {
      padding: 20px;    
    }
    .kontak1 {
      display: flex;
      justify-content: space-between;
      margin-top: 20px;
    }

    form input, form textarea {
      display: block;
      margin-bottom: 10px;
      width: 100%;
      padding: 5px;
    }

    .maps{
      margin-top: 10px;
      height: 200px;
      text-align: center;
      line-height: 200px;
      background-color: red;
    }

    footer {
      text-align: center;
      padding: 10px;
      background-color: #2e379b;
    }
  </style>
</head>
<body>
  <header>
    <nav class="navbar">     
      <a href="#beranda">Beranda</a>
      <a href="#tentang">Tentang Saya</a>
      <a href="#portofolio">portofolio</a>
      <a href="#opini">opini</a>

      <div class="dropdown">
        <button class="dropbtn">Lainnya</button>
        <div class="dropdown-content">
          <a href="https://www.instagram.com/mratustiianiiiiii6_/" target="_blank">Instagram</a>
          <a href="https://www.facebook.com/share/1FSumWP1UZ/" target="_blank">Facebook</a>
          <a href="https://www.tiktok.com/@maratusetiani?_t=ZS-8vmAEqFfg2y&_r=1" target="_blank">Tiktok</a>
        </div>
      </div>
    </nav>
  </header>

  <section class="intro">
    
    <img src="![aku](https://github.com/user-attachments/assets/45946009-c848-411b-825f-c14aa02b6a97)
" alt="Foto">
    <div class="intro-text">
    <h2>Halo, saya Maratus Setiani</h2>
    <P>Saya seorang mahasiswa di universitas nahdlatul ulama sunan giri bojonegoro.</P>
  </div>
  </section> 



   <section class="tentang" id="tentang">
    <div>
      <h2>Tentang Saya</h2>
      <p>Saya adalah seorang mahasiswa di UNUGIRI , prodi Teknik Informatika. Sekarang saya menduduki semester 2.</p>
      <p>Saya adalah Gen-z dengan kelahiran pada tanggal 10 mei 2006. Saya anak kedua dari dua bersaudara.</p>
      <p> Saya adalah alumi dari pondok pesantren ATTANWIR bojonegoro.</p>
      <p>Dan kini saya melanjutkan pendidikan saya dengan kuliah di UNUGIRI di prodi Teknik Informatika.</p>
    </div>
    <img src="![atus](https://github.com/user-attachments/assets/579c18b8-58ce-4d7a-8d3a-76895d36298e)
" alt="Foto Tentang Saya">
  </section> 

  <hr class="garis-pemisah">

   <section class="portofolio" id="portofolio">
    <h2>Portofolio</h2>
    <table>
      <thead>
        <tr>
          <th>No</th>
          <th>Nama Kegiatan</th>
          <th>Waktu Kegiatan</th>
          <th>Bukti Kegiatan</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>pkkmb UNUGIRI</td>
          <td>2024</td>
          <td><a href="c:\Users\HP 14s\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\E3E725D3B7D2339C41BB28FF92E8635D\RIAU_SERTIFIKAT_MARATUS SETIANI.pdf">lihat bukti</a></td>
        </tr>
        <tr>
          <td>2</td>
          <td>Pengurus konsulat Attanwir </td>
          <td>2023/2024</td>
          <td> <a href="c:\Users\HP 14s\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\24BE833826002C7D2A8D9D5F021B7E43\WhatsApp Image 2025-04-25 at 18.40.34_a2f53c3f.jpg">lihat bukti</a></td>
        </tr>
        <tr>
          <td>3</td>
          <td>workshop TIK</td>
          <td>2024</td>
          <td><a href="c:\Users\HP 14s\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\F0FF2EAEF41DD9E6E3DCB49D53C1BF11\WhatsApp Image 2025-04-25 at 18.38.56_63d781a6.jpg">lihat bukti</a></td>
        </tr>
        <tr>
          <td>4</td>
          <td>KMD</td>
          <td>2024</td>
          <td><a href="c:\Users\HP 14s\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\TempState\AB7C5CDB20164D2D25769BDDD2FE1493\WhatsApp Image 2025-04-25 at 18.38.56_71d6fc69.jpg">lihat bukti</a></td>
        </tr>
        <!-- Tambah baris lain jika perlu -->
      </tbody>
    </table>
  </section>
  
  <hr class="garis-pemisah">

  <section>
    <h2 style="text-align: center;" id="opini">Opini</h2>
  </section>

  <section class="opini">
   
    <div><img src="![kmd](https://github.com/user-attachments/assets/6c1dbcb6-5cac-4e1f-bb74-c4e664feaa86)
" alt="Opini 1"><h4>KMD Attanwir</h4></div>
    <div><img src="![it camp](https://github.com/user-attachments/assets/5bd1f8b8-01e6-4493-96f6-863e5f708ff1)
" alt="Opini 2"><h4>IT camp</h4></div>
    <div><img src="![sosialisasi](https://github.com/user-attachments/assets/ccfbaaf3-6c6c-4716-8520-15632379a84a)
" alt="Opini 3"><h4>Sosialisasi</h4></div>
    <div><img src="![tugas1](https://github.com/user-attachments/assets/25580e16-0266-4e7e-9343-93da1e40015c)
" alt="Opini 4"><h4>Tugas Pemograman</h4></div>
    <div><img src="![tugas](https://github.com/user-attachments/assets/8b07188b-110a-4343-be66-c6b1d41fe965)
" alt="Opini 5"><h4>Tugas struktur data</h4></div>
    <div><img src="![tugas2](https://github.com/user-attachments/assets/38037663-25ed-4ad2-8821-4c4dce8be40f)
" alt="Opini 6"><h4>Tugas Bahasa inggris </h4></div>
  </section> 
   <hr class="garis garis-pemisah">
   
   <section class="kontak">
    <h2>hubungi saya</h2>
    <div class="kontak1">

    <form>
      <input type="email" placeholder="Email">
      <input type="text" placeholder="Nama">
      <input type="text" placeholder="Subject">
      <textarea placeholder="Isi Pesan"></textarea>
      <button type="submit">Kirim</button>
    </form>
 
    <div class="maps">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d31656.009256997408!2d112.04127026897488!3d-7.353764529913663!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e78256fc8b465f9%3A0x1ce5ed3ecfc34078!2sTondomulo%2C%20Kec.%20Kedungadem%2C%20Kabupaten%20Bojonegoro%2C%20Jawa%20Timur!5e0!3m2!1sid!2sid!4v1745497607406!5m2!1sid!2sid"
       width="350" 
       height="200" 
       style="border:0;" 
       allowfullscreen="" loading="lazy" 
       referrerpolicy="no-referrer-when-downgrade">
      </iframe>
    </div>
  </div>
   </section> 

   <footer>
    <p>Copyright by Maratus Setiani</p>
  </footer>
</body>
</html>
