<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Website Pembelajaran Islam</title>
  <style>
    /* Gaya Dasar */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #808080;
      color: #fff;
      line-height: 1.6;
    }
    /* Navigasi */
    nav {
      background: rgba(0, 0, 0, 0.9);
      padding: 15px 0;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      z-index: 1000;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.5);
    }
    nav a {
      color: #f8d16e;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #fff;
    }
    /* Section Umum */
    .section {
      padding: 120px 20px 60px;
      margin-top: 60px;
    }
    /* Content Wrapper */
    .content-wrapper {
      background: rgba(0, 0, 0, 0.85);
      padding: 40px;
      border-radius: 10px;
      margin: 0 auto;
      max-width: 800px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
    }
    /* Tabel No Matriks */
    .matrix-table {
      margin: 20px auto;
      border-collapse: collapse;
      width: 90%;
      max-width: 600px;
    }
    .matrix-table th,
    .matrix-table td {
      border: 1px solid #ddd;
      padding: 12px;
      text-align: left;
      font-size: 16px;
    }
    .matrix-table th {
      background-color: #f8d16e;
      color: #000;
    }
    /* Video Container */
    .video-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
    }
    .video {
      width: 300px;
      background: #000;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    }
    .video h3 {
      background: #f8d16e;
      color: #000;
      margin: 0;
      padding: 10px;
      font-size: 18px;
    }
    iframe {
      width: 100%;
      height: 200px;
      border: none;
    }
    /* Kuiz */
    #quiz {
      margin: 20px auto;
      max-width: 500px;
    }
    .question-container {
      background: #333;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 20px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    }
    .question-container .question {
      font-weight: bold;
      margin-bottom: 10px;
      font-size: 18px;
    }
    .options {
      padding: 0;
    }
    .options li {
      list-style: none;
      padding: 12px;
      background: #555;
      margin: 8px 0;
      cursor: pointer;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .options li:hover {
      background: #666;
    }
    /* Tombol */
    button {
      background: #f8d16e;
      color: #000;
      padding: 12px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
      transition: background 0.3s;
      margin: 10px;
    }
    button:hover {
      background: #e0b85a;
    }
    /* Responsif */
    @media (max-width: 600px) {
      nav a { margin: 0 8px; font-size: 14px; }
      .content-wrapper { padding: 20px; }
      .video { width: 90%; }
      .matrix-table { font-size: 14px; }
    }
  </style>
</head>
<body>

  <!-- Navigasi -->
  <nav>
    <a href="#pengenalan">Pengenalan</a>
    <a href="#definisi">Definisi</a>
    <a href="#objektif">Objektif</a>
    <a href="#video">Video</a>
    <a href="#kerangka">Kerangka Projek</a>
    <a href="#laporan">Laporan Projek</a>
    <a href="#soalan">Soalan Kuiz</a>
  </nav>

  <!-- Pengenalan -->
  <section id="pengenalan" class="section">
    <div class="content-wrapper">
      <h2>Pengenalan</h2>
      <p>Website ini dibuat untuk menyediakan video pembelajaran Ahli Sunnah Wal Jamaah untuk Projek Pendidikan Islam (WI001).</p>
      
      <!-- Informasi Kumpulan -->
      <h3>Kami dari Kumpulan 4</h3>
      <p>Anggota yang terlibat:</p>
      
      <table class="matrix-table">
        <tr>
          <th>No</th>
          <th>Nama</th>
          <th>No. Matriks</th>
        </tr>
        <tr>
          <td>1</td>
          <td>MUHAMMAD ALIF NAQIUDDIN BIN KHAIRUL RAZI</td>
          <td>MA2411400037</td>
        </tr>
        <tr>
          <td>2</td>
          <td>MUHAMMAD IFWAT BIN HILMY</td>
          <td>MA2411100258</td>
        </tr>
        <tr>
          <td>3</td>
          <td>AHMAD MIQDAD BIN ZAHARI</td>
          <td>MA2411100282</td>
        </tr>
        <tr>
          <td>4</td>
          <td>MUHAMMAD NUR JURAIDI BIN ZAINAL</td>
          <td>MA2411100375</td>
        </tr>
      </table>
    </div>
  </section>

  <!-- Definisi Ahli Sunnah Wal Jamaah -->
  <section id="definisi" class="section">
    <div class="content-wrapper">
      <h2>Definisi Ahli Sunnah Wal Jamaah</h2>
      <p>Istilah Ahli Sunnah Wal Jamaah berasal daripada dua patah perkataan iaitu “ahl al-Sunnah” dan “al-Jamaah” yang merujuk kepada golongan yang mengikuti pegangan Nabi Muhammad s.a.w. serta jalan hidup Baginda dan para sahabat.</p>
    </div>
  </section>

  <!-- Objektif -->
  <section id="objektif" class="section">
    <div class="content-wrapper">
      <h2>Objektif</h2>
      <p>1. Menerangkan tentang akidah dan ajaran Islam.</p>
      <p>2. Menerangkan tentang kepelbagaian mazhab.</p>
      <p>3. Menerangkan tentang kesatuan dan keharmonian.</p>
    </div>
  </section>

  <!-- Video -->
  <section id="video" class="section">
    <div class="content-wrapper">
      <h2>Video Pembelajaran Islam</h2>
      <div class="video-container">
        <div class="video">
          <h3>Akidah dan Ajaran Islam</h3>
          <!-- Ganti VIDEO_ID1 dengan ID video YouTube yang sesuai -->
          <iframe src="https://www.youtube.com/embed/VIDEO_ID1" allowfullscreen></iframe>
        </div>
        <div class="video">
          <h3>Kepelbagaian Mazhab</h3>
          <!-- Ganti VIDEO_ID2 dengan ID video YouTube yang sesuai -->
          <iframe src="https://www.youtube.com/embed/VIDEO_ID2" allowfullscreen></iframe>
        </div>
        <div class="video">
          <h3>Kesatuan dan Keharmonian</h3>
          <!-- Ganti VIDEO_ID3 dengan ID video YouTube yang sesuai -->
          <iframe src="https://www.youtube.com/embed/VIDEO_ID3" allowfullscreen></iframe>
        </div>
      </div>
    </div>
  </section>

  <!-- Kerangka Projek -->
  <section id="kerangka" class="section">
    <div class="content-wrapper">
      <h2>Kerangka Projek</h2>
      <p>Kerangka projek ini merupakan hasil projek pendidikan Islam yang dikembangkan secara bertahap.</p>
      <a href="https://drive.google.com/file/d/12NQIYu8fPARDE6FINUsJZmXy9w0nCima/view?usp=sharing" target="_blank" style="color:#f8d16e;">
        Buka Kerangka Projek (PDF)
      </a>
    </div>
  </section>

  <!-- Laporan Projek -->
  <section id="laporan" class="section">
    <div class="content-wrapper">
      <h2>Laporan Projek</h2>
      <p>Laporan ini memaparkan hasil projek pembelajaran Islam yang telah kami kerjakan.</p>
      <a href="https://drive.google.com/file/d/YourLaporanFileID/view?usp=sharing" target="_blank" style="color:#f8d16e;">
        Buka Laporan Projek (PDF)
      </a>
    </div>
  </section>

  <!-- Soalan Kuiz -->
  <section id="soalan" class="section">
    <div class="content-wrapper">
      <h2>Soalan Kuiz: Ahli Sunnah Wal Jamaah</h2>
      <p>Uji pengetahuan anda mengenai aspek-aspek yang telah disampaikan pada objektif:</p>
      <div id="quiz">
        <div class="question-container" id="question-container">
          <div class="question" id="question">Pertanyaan akan muncul di sini</div>
          <ul class="options" id="options"></ul>
        </div>
        <button onclick="nextQuestion()" id="next-btn">Berikutnya</button>
        <button onclick="restartQuiz()" id="restart-btn" style="display:none;">Coba Lagi</button>
        <div class="result" id="result"></div>
      </div>
    </div>
  </section>

  <script>
    // Array pertanyaan dengan total 15 soal
    const questions = [
      {
        question: "Apa yang dimaksud dengan akidah dalam Islam?",
        options: [
          "Sistem kepercayaan dasar dalam Islam",
          "Tradisi budaya",
          "Seni dan arsitektur",
          "Cerita rakyat"
        ],
        answer: "Sistem kepercayaan dasar dalam Islam"
      },
      {
        question: "Manakah yang merupakan contoh kepelbagaian mazhab dalam Islam?",
        options: [
          "Mazhab Syafi'i, Maliki, Hanafi, dan Hanbali",
          "Mazhab Barat dan Timur",
          "Mazhab modern dan tradisional",
          "Mazhab A, B, dan C"
        ],
        answer: "Mazhab Syafi'i, Maliki, Hanafi, dan Hanbali"
      },
      {
        question: "Mengapa kesatuan dan keharmonian penting dalam Islam?",
        options: [
          "Agar umat Islam bisa saling mendukung dan bersatu",
          "Agar semua negara menggunakan satu bahasa",
          "Agar ekonomi berkembang",
          "Agar tradisi berubah"
        ],
        answer: "Agar umat Islam bisa saling mendukung dan bersatu"
      },
      {
        question: "Bagaimana ajaran Islam menekankan nilai-nilai kesatuan?",
        options: [
          "Dengan mengutamakan persatuan umat",
          "Dengan mengutamakan perbedaan budaya",
          "Dengan memisahkan masyarakat berdasarkan warna",
          "Dengan menolak perbedaan pendapat"
        ],
        answer: "Dengan mengutamakan persatuan umat"
      },
      {
        question: "Apa peran utama Al-Qur'an dalam akidah umat Islam?",
        options: [
          "Sebagai sumber hukum dan pedoman hidup",
          "Hanya sebagai karya sastra",
          "Sebagai buku sejarah",
          "Sebagai koleksi cerita rakyat"
        ],
        answer: "Sebagai sumber hukum dan pedoman hidup"
      },
      {
        question: "Mazhab manakah yang dikenal dengan pendekatan yang lebih fleksibel dalam interpretasi hukum?",
        options: [
          "Mazhab Hanafi",
          "Mazhab Maliki",
          "Mazhab Syafi'i",
          "Mazhab Hanbali"
        ],
        answer: "Mazhab Hanafi"
      },
      {
        question: "Apa makna utama dari istilah 'Ummah' dalam konteks kesatuan Islam?",
        options: [
          "Komunitas umat Islam di seluruh dunia",
          "Sebuah kelompok politik",
          "Sebuah organisasi amal",
          "Sebuah sekolah agama"
        ],
        answer: "Komunitas umat Islam di seluruh dunia"
      },
      {
        question: "Salah satu dasar ajaran akidah adalah tauhid. Apa arti tauhid?",
        options: [
          "Mengesakan Allah",
          "Menyembah berhala",
          "Memperbanyak ibadah",
          "Menghormati nabi-nabi"
        ],
        answer: "Mengesakan Allah"
      },
      {
        question: "Dalam konteks mazhab, apa yang dimaksud dengan ijtihad?",
        options: [
          "Proses penalaran dalam hukum Islam",
          "Sebuah ibadah ritual",
          "Perayaan hari besar",
          "Kegiatan sosial"
        ],
        answer: "Proses penalaran dalam hukum Islam"
      },
      {
        question: "Apa tujuan utama dari penerapan mazhab dalam kehidupan umat Islam?",
        options: [
          "Untuk mengatur dan memudahkan penerapan syariat",
          "Untuk membagi umat Islam menjadi kelompok-kelompok kecil",
          "Untuk menimbulkan perpecahan",
          "Untuk menghancurkan tradisi lama"
        ],
        answer: "Untuk mengatur dan memudahkan penerapan syariat"
      },
      {
        question: "Salah satu nilai penting dalam kesatuan Islam adalah ukhuwah. Apa artinya?",
        options: [
          "Persaudaraan",
          "Pertentangan",
          "Kepemimpinan",
          "Kemewahan"
        ],
        answer: "Persaudaraan"
      },
      {
        question: "Bagaimana cara ajaran Islam mendorong keharmonian di antara umat?",
        options: [
          "Dengan menekankan toleransi dan saling menghargai",
          "Dengan mengutamakan perbedaan",
          "Dengan membatasi interaksi",
          "Dengan menetapkan aturan yang kaku"
        ],
        answer: "Dengan menekankan toleransi dan saling menghargai"
      },
      {
        question: "Mengapa penting untuk memahami perbedaan di antara mazhab dalam Islam?",
        options: [
          "Untuk saling menghormati perbedaan dan mencari titik temu",
          "Untuk memperkuat perbedaan dan memecah belah",
          "Untuk menghilangkan seluruh perbedaan",
          "Untuk meningkatkan persaingan antarmazhab"
        ],
        answer: "Untuk saling menghormati perbedaan dan mencari titik temu"
      },
      {
        question: "Apa salah satu cara untuk mengaplikasikan akidah dalam kehidupan sehari-hari?",
        options: [
          "Dengan selalu mengingat dan mengamalkan ajaran Islam",
          "Dengan mengabaikan perintah agama",
          "Dengan mengikuti trend modern semata",
          "Dengan menolak segala bentuk tradisi"
        ],
        answer: "Dengan selalu mengingat dan mengamalkan ajaran Islam"
      },
      {
        question: "Dalam ajaran Islam, bagaimana peran ilmu pengetahuan terkait dengan akidah?",
        options: [
          "Ilmu pengetahuan mendukung pemahaman yang lebih dalam tentang ajaran Islam",
          "Ilmu pengetahuan tidak ada hubungannya dengan agama",
          "Ilmu pengetahuan menggantikan peran agama",
          "Ilmu pengetahuan hanya untuk kepentingan duniawi"
        ],
        answer: "Ilmu pengetahuan mendukung pemahaman yang lebih dalam tentang ajaran Islam"
      }
    ];

    let currentQuestionIndex = 0;
    let score = 0;

    // Fungsi untuk memuat pertanyaan
    function loadQuestion() {
      const questionObj = questions[currentQuestionIndex];
      document.getElementById('question').textContent = questionObj.question;
      const optionsList = document.getElementById('options');
      optionsList.innerHTML = ''; // Reset opsi

      questionObj.options.forEach(option => {
        const li = document.createElement('li');
        li.textContent = option;
        li.onclick = () => checkAnswer(option);
        optionsList.appendChild(li);
      });
    }

    // Fungsi untuk mengecek jawaban
    function checkAnswer(selectedAnswer) {
      const correctAnswer = questions[currentQuestionIndex].answer;
      if (selectedAnswer === correctAnswer) {
        score++;
      }
      // Nonaktifkan semua opsi setelah dijawab
      const options = document.querySelectorAll('.options li');
      options.forEach(option => {
        option.style.pointerEvents = 'none';
      });
      // Aktifkan tombol berikutnya
      document.getElementById('next-btn').disabled = false;
    }

    // Fungsi untuk pertanyaan selanjutnya
    function nextQuestion() {
      currentQuestionIndex++;
      if (currentQuestionIndex < questions.length) {
        loadQuestion();
        document.getElementById('next-btn').disabled = true;
      } else {
        document.getElementById('result').textContent = 
          `Kuiz Selesai! Skor Kamu: ${score} / ${questions.length}`;
        document.getElementById('next-btn').style.display = 'none';
        document.getElementById('restart-btn').style.display = 'block';
      }
    }

    // Fungsi untuk mengulang kuiz
    function restartQuiz() {
      currentQuestionIndex = 0;
      score = 0;
      document.getElementById('result').textContent = '';
      document.getElementById('next-btn').style.display = 'block';
      document.getElementById('restart-btn').style.display = 'none';
      loadQuestion();
      document.getElementById('next-btn').disabled = true;
    }

    // Muat pertanyaan pertama saat halaman dibuka
    loadQuestion();
    document.getElementById('next-btn').disabled = true;
  </script>
</body>
</html>
