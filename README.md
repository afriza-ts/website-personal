

[Uploading * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif}

    body{
        background-color: black;
        color: white;
    }
    nav{
        background-color: aquamarine;
    }
    img{
        width: 150px; 
        height: 200px;
        object-fit: cover;
        vertical-align: middle;
    }
    .wrapper{
        padding: 0 15px;
        display: flex; 
        flex-wrap: wrap;
        align-items: center;
        justify-content: space-around;
        gap: 5rem;
    }
    .intro{
        flex: 1;
    }

    h1{
        font-weight: bolder;
        
    }
    .container{
        position: relative;
    }
    .gambar-dasar {
            position: absolute;
            top: 0px;
            left: 0px;
            bottom: 0;
            z-index: 1;
    }
    
    .gambar-atas {
        position: absolute;
        top: 0px;
        left: 0px;
        z-index: 2;
        
    }
    



    

    
        
    
    











    button:hover{
        background-color: aqua;
    }

    footer{
        background-color: aquamarine;
        text-align: center;
        height: 30px;
        margin-bottom: 200px;
    }
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>My Profile</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-SgOJa3DmI69IUzQ2PVdRZhwQ+dy64/BUtbMJw1MZ8t5HZApcHrRKUc4W0kG879m7" crossorigin="anonymous">
    <link rel="stylesheet" href="stylee.css">
  </head>
  <body>
    <header>
      <nav>
        <div class="nav nav-tabs" id="nav-tab" role="tablist">
          <button class="nav-link active" id="nav-home-tab" data-bs-toggle="tab" data-bs-target="#nav-home" type="button" role="tab" aria-controls="nav-home" aria-selected="true">Home</button>
          <button class="nav-link" id="nav-me-tab" data-bs-toggle="tab" data-bs-target="#nav-me" type="button" role="tab" aria-controls="nav-me" aria-selected="false">Me</button>
          <button class="nav-link" id="nav-profile-tab" data-bs-toggle="tab" data-bs-target="#nav-profile" type="button" role="tab" aria-controls="nav-profile" aria-selected="false">Profile</button>
          <button class="nav-link" id="nav-contact-tab" data-bs-toggle="tab" data-bs-target="#nav-contact" type="button" role="tab" aria-controls="nav-contact" aria-selected="false">Experience</button>
          <button class="nav-link" id="nav-galery-tab" data-bs-toggle="tab" data-bs-target="#nav-galery" type="button" role="tab" aria-controls="nav-galery" aria-selected="false" >Galery</button>
        </div>
      </nav>
      <div class="tab-content" id="nav-tabContent">
        <div class="tab-pane fade show active" id="nav-home" role="tabpanel" aria-labelledby="nav-home-tab" tabindex="0">
          <div class="wrapper">
            <div class="foto">
              <img src="c:\Users\HP\Pictures\download (2).jpg" alt="">
               <img src="c:\Users\HP\Pictures\download (3).jpg" alt="">
            </div>
            <div class="intro">
              <div class="col-md-4 py-3">
                <h1> 
                  My Portofolio
                </h1>
                <p>
                  Ini adalah Portofolio diriku yang mencakup beberapa bagian about me, Riwayat pendidikan, galeri karyaku, pengalaman dan kontakku
                </p>
              </div>
            </div>
            <p>

            </p>
            <p>
              
            </p>

          </div>
        </div>
        <div class="tab-pane fade show" id="nav-me" role="tabpanel" aria-labelledby="nav-me-tab" tabindex="0">
            <div class="wrapper">
            <div class="Profile">
            <img src="c:\Users\HP\Pictures\Gambar WhatsApp 2025-04-24 pukul 08.50.00_9b0c92c7.jpg" alt="dekripsi gambar">
          </div>
            <div class="intro">
              <div class="col-md-4 py-3">
            <h1>
              About Me 
            </h1>
            <h4>
              My Vision
            </h4>
            <p>
              Visi Saya adalah ingin meraih pendidikan berkualitas tinggi dan berstandar internasional, yang dapat membuka peluang karir global dan memperluas budaya
            </p>
            <h4>
              My mision
            </h4>
            <p>
              Misi Saya adalah mempersiapkan diri secara akademik, finansial, dan bahasa, serta membangun jaringan internasional yang kuat
            </p>
          </div>
        </div>
        </div>
        </div>
        <div class="tab-pane fade" id="nav-profile" role="tabpanel" aria-labelledby="nav-profile-tab" tabindex="0">
          <div class="poit">
           <div class="col-md-4 py-3"> 
            <h1>My Profile</h1>
          <div>
            <div>
              <div>
                   <table>
                    <tbody>
                      <tr>
                        <th>
                          Nama 
                        </th>
                        <th>
                          :
                          </th>
                          <td>
                            Afriza Tsani Abdul Raziq
                          </td>
                      </tr>
                      <tr>
                        <th>
                          NIS/NISN
                        </th>
                        <th>
                          :
                        </th>
                        <td>
                          24250110/0099994944
                        </td>
                      </tr>
                      <tr>
                        <th>
                          Tempat Tinggal
                        </th>
                        <th>
                          :
                        </th>
                        <td>
                          Makassar, Rappocini, Jl. Kelapa III
                        </td>
                      </tr>
                      <tr>
                        <th>
                          Tempat Tanggal Lahir
                        </th> 
                        <th>
                          :
                        </th>
                        <td>
                          Tarakan, 09-05-2009
                        </td>
                      </tr>
                      <tr>
                        <th>
                          Agama
                        </th>
                        <th>
                           :
                        </th> 
                        <td>
                           Islam
                        </td>
                      </tr>
                      <tr>
                        <th>
                          Email
                        </th>
                        <th>
                          :
                        </th>
                        <td>
                          afrizatsani86@gmail.com
                        </td>
                      </tr>
                      <tr>
                        <th>
                          No.Hp
                        </th>
                        <th>
                          :
                        </th> 
                        <td>
                          +62 856-5480-6932
                        </td>
                      </tr>
                      <tr>
                        <th>
                          Instagram
                        </th>
                        <th>
                          :
                        </th>
                        <td>
                          <a href="https://www.instagram.com/afrnoid?igsh=Z2FlaHFpOW9zZ3d4">https://www.instagram.com/afrnoid?igsh=Z2FlaHFpOW9zZ3d4</a>
                        </td>
                      </tr>
                      
                    </tbody>
                   </table>
                  </div>
              </div>
            </div>
          </div>
          <div class="col-md-4 py-3">
          <h3>My Dream</h3>
          <p>
            <ol>
              <li>
                Kuliah di luar Negri
              </li>
              <li>
                Menjadi Penulis terkenal
              </li>
              <li>
                Mendapatkan Beasiswa Gratis
              </li>
            </ol>
          </p>
          <h3>
            My Situation Now
          </h3>
          <p>
             <ol>
              <li>
                Siswa Kelas X TKJ 1 Di SMKN3 Makassar
              </li>
              <li>
                Guru Mengaji Di Tpa Al Hilal
              </li>
             </ol>
          </p>
          </div>
        </div>
        </div>
        <div class="tab-pane fade" id="nav-contact" role="tabpanel" aria-labelledby="nav-contact-tab" tabindex="0">
          <div class="col-md-4 py-3">
          <h3>
            Riwayat Pendidikan
          </h3>
          <table>
            <tr>
              <th>
                TK Nurul Falah
              </th>
              <td>
                2015-2016
              </td>
            </tr>
            <tr>
              <th>
                SD Yaditra
              </th>
              <td>
                2016-2021
              </td>
            </tr>
            <tr>
              <th>
                MTS Sultan Hasanuddin 
              </th>
              <td>
                2021-2024
              </td>
            </tr>
            <tr>
              <th>
                SMKN3 Makassar
              </th>
              <td>
                2024-Sekarang
              </td>
            </tr>
          </table>
          </div>
           <div class="col-md-4 py-5">
            <h3>
            Pengalaman dan Prestasi Saya
          </h3>
          <ol>
            <li>
              Mengikuti OSN Tingkat Kabupaten 2019
            </li>
            <li>
              Lulus Tingkat Pertama di Tapak Suci 2023
            </li>
            <li>
              Siswa Cakap Digital Alef 2022
            </li>
            <li>
              Mengikuti Lomba Tartil Tingkat Kecamatan 2019
            </li>
            <li>
              Mengikuti Lomba Olipiade Digital Matematika Alef 2022
            </li>
            <li>
              Mengikuti Lomba Digital Matematika Tingkat Nasional 2022
            </li>
            <li>
              Juara 1 Lomba Parade Wajah 2024
            </li>
            <li>
              Mengikuti Sosialisasi Penulisan Kreatif Puisi dan Cerpen
            </li>
          </ol>
        </div>
        </div>
        <div class="tab-pane fade" id="nav-galery" role="tabpanel" aria-labelledby="nav-galery-tab" tabindex="0">
          <h3>
            Galery Of Experience
          </h3>
          <div>
            <img src="c:\Users\HP\Pictures\IMG-20250426-WA0015.jpg" alt="">
            <img src="c:\Users\HP\Pictures\IMG-20250426-WA0024.jpg" alt="">
          </div>
          <h3>
            Work Galery
          </h3>
          <h5>
            Cerpen
          </h5>
          <div>
            <img src="c:\Users\HP\Pictures\IMG-20250426-WA0022.jpg" alt="">
            <img src="c:\Users\HP\Pictures\IMG-20250426-WA0023.jpg" alt="">
            <img src="c:\Users\HP\Pictures\IMG-20250426-WA0019.jpg" alt="">
            <img src="c:\Users\HP\Pictures\IMG-20250426-WA0016.jpg" alt="">
            <img src="c:\Users\HP\Pictures\IMG-20250426-WA0018.jpg" alt="">
            <img src="c:\Users\HP\Pictures\IMG-20250426-WA0017.jpg" alt="">
            <img src="c:\Users\HP\Pictures\IMG-20250426-WA0020.jpg" alt="">
          </div>
          <h3>
            Puisi
          </h3>
          <div>
            <img src="c:\Users\HP\Pictures\IMG-20250426-WA0021.jpg" alt="">
          </div>
        </div>
      </div>
    </header>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.5/dist/js/bootstrap.bundle.min.js" integrity="sha384-k6d4wzSIapyDyv1kpU366/PK5hCdSbCRGRCMv+eplOQJWyd1fbcAu9OCUj5zNLiq" crossorigin="anonymous"></script>
  <footer>
    <p>&copy; created by Afriza Tsani</p>
  </footer>
  
  </body>

</html>stylee.css…]()

