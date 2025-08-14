<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Revolusi Industri 4.0 — Presentasi</title>
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --accent:#0ea5ff; --muted:#9aa8bd; --glass: rgba(255,255,255,0.04);
      --radius:16px; --pad:18px;
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{background:linear-gradient(180deg,#071027 0%, #081129 60%); color:#e6eef8; margin:0; padding:40px;}
    .wrap{max-width:1000px; margin:0 auto}
    header{display:flex;gap:20px;align-items:center;margin-bottom:18px}
    .logo{width:64px;height:64px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;box-shadow:0 6px 20px rgba(14,165,255,0.12)}
    .logo strong{font-size:20px;color:#021024}
    h1{font-size:28px;margin:0}
    p.lead{margin:6px 0 0;color:var(--muted)}

    .card{background:linear-gradient(180deg,var(--card), rgba(11,18,32,0.6)); padding:var(--pad); border-radius:var(--radius); box-shadow:0 8px 30px rgba(2,6,23,0.6);}
    .meta{display:flex;justify-content:space-between;align-items:center;gap:12px;margin-top:12px}
    .group{font-size:14px;color:var(--muted)}

    .accordion{margin-top:18px;border-radius:12px;overflow:hidden}
    .item{border-top:1px solid rgba(255,255,255,0.03)}
    .item button{width:100%;text-align:left;padding:16px;background:transparent;border:0;color:inherit;font-size:16px;display:flex;justify-content:space-between;align-items:center;cursor:pointer}
    .item button:focus{outline:2px solid rgba(14,165,255,0.15);}
    .chev{transition:transform .25s ease}
    .content{max-height:0;overflow:hidden;padding:0 16px 0 16px;transition:max-height .35s ease,padding .25s}
    .content-inner{padding:12px 0;color:#cfe7ff;line-height:1.6}

    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:14px;margin-top:16px}
    .smallcard{background:var(--glass);padding:12px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
    .muted{color:var(--muted);font-size:14px}

    footer{margin-top:18px;color:var(--muted);font-size:13px}
    a.ref{color:var(--accent);text-decoration:none}

    @media (max-width:600px){body{padding:18px} h1{font-size:20px}}
  </style>
</head>
<body>
  <div class="wrap card">
    <header>
      <div class="logo"><strong>4.0</strong></div>
      <div>
        <h1>Revolusi Industri 4.0</h1>
        <p class="lead">Ringkasan materi & contoh penerapan — tema teknologi</p>
      </div>
    </header>

    <div class="meta">
      <div class="group">Kelompok: Alpha M.A (04), Avelino N.V (06), Dhyna R. (10), Wibie N. (36)</div>
      <div class="muted">Mata pelajaran: Informatika — Kelas 12 (Kurikulum Merdeka)</div>
    </div>

    <section class="accordion" id="accordion">

      <div class="item">
        <button data-target="one">
          <span>1. Gambaran Umum</span>
          <span class="chev">▸</span>
        </button>
        <div class="content" id="one">
          <div class="content-inner">
            <strong>Apa itu Industri 4.0?</strong>
            <p>Industri 4.0 adalah era integrasi sistem siber-fisik di mana otomatisasi, data besar, internet-of-things, dan kecerdasan buatan bekerja bersama untuk membuat proses lebih cepat, fleksibel, dan cerdas. Fokusnya pada konektivitas real-time, analitik, dan keputusan otomatis yang meningkatkan efisiensi di sektor industri dan layanan.</p>
            <p><em>Inti pelajaran:</em> konsep dasar, dampak sosial-ekonomi, dan contoh penerapan nyata.</p>
          </div>
        </div>
      </div>

      <div class="item">
        <button data-target="two">
          <span>2. Teknologi Inti (Ringkasan)</span>
          <span class="chev">▸</span>
        </button>
        <div class="content" id="two">
          <div class="content-inner">
            <div class="grid">
              <div class="smallcard">
                <strong>IoT (Internet of Things)</strong>
                <div class="muted">Sensor, aktuator, konektivitas</div>
                <p>Perangkat terhubung yang mengumpulkan data untuk monitoring dan kendali jarak jauh.</p>
              </div>

              <div class="smallcard">
                <strong>Cyber-Physical Systems</strong>
                <div class="muted">Integrasi dunia fisik & digital</div>
                <p>Penggabungan sistem fisik dengan perangkat lunak yang memungkinkan respons otomatis terhadap kondisi nyata.</p>
              </div>

              <div class="smallcard">
                <strong>Big Data & Analytics</strong>
                <div class="muted">Pengolahan data besar</div>
                <p>Menganalisis data untuk menemukan pola, prediksi, dan optimasi proses produksi atau layanan.</p>
              </div>

              <div class="smallcard">
                <strong>Kecerdasan Buatan (AI) & Machine Learning</strong>
                <div class="muted">Otomatisasi keputusan</div>
                <p>Model yang mampu mengambil keputusan atau rekomendasi berdasarkan data.</p>
              </div>

              <div class="smallcard">
                <strong>Cloud Computing</strong>
                <div class="muted">Sumber daya komputasi on-demand</div>
                <p>Menyediakan penyimpanan dan pemrosesan data yang skalabel tanpa infrastruktur lokal besar.</p>
              </div>

              <div class="smallcard">
                <strong>Robotika & Otomasi</strong>
                <div class="muted">Mesin yang menjalankan tugas berulang</div>
                <p>Peningkatan efisiensi produksi dengan robot kolaboratif dan otomatisasi lini produksi.</p>
              </div>

              <div class="smallcard">
                <strong>Keamanan Siber</strong>
                <div class="muted">Perlindungan data & sistem</div>
                <p>Langkah teknis dan kebijakan untuk menjaga integritas, kerahasiaan, dan ketersediaan sistem terhubung.</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="item">
        <button data-target="three">
          <span>3. Dampak & Kompetensi yang Diperlukan</span>
          <span class="chev">▸</span>
        </button>
        <div class="content" id="three">
          <div class="content-inner">
            <p>Industri 4.0 mengubah jenis pekerjaan dan keterampilan yang dibutuhkan. Kompetensi utama yang relevan untuk siswa:
            <ul>
              <li>Literasi digital dan data</li>
              <li>Keterampilan komputasi dasar</li>
              <li>Pemikiran kritis dan pemecahan masalah</li>
              <li>Kolaborasi dan komunikasi lintas disiplin</li>
              <li>Pemahaman dasar keamanan siber</li>
            </ul></p>
            <p class="muted">Hubungkan kompetensi ini dengan capaian pembelajaran di Kurikulum Merdeka.</p>
          </div>
        </div>
      </div>

      <div class="item">
        <button data-target="four">
          <span>4. Contoh Penerapan & Studi Kasus Singkat</span>
          <span class="chev">▸</span>
        </button>
        <div class="content" id="four">
          <div class="content-inner">
            <strong>Contoh 1 — Smart Factory</strong>
            <p>Sensor memantau kondisi mesin; data dianalisis untuk prediksi perawatan.</p>

            <strong>Contoh 2 — Smart Agriculture</strong>
            <p>IoT dan analitik membantu pengairan dan pemupukan otomatis berdasarkan kondisi tanah.</p>

            <strong>Contoh 3 — Layanan Publik</strong>
            <p>Manajemen lalu lintas yang menyesuaikan aliran kendaraan untuk mengurangi kemacetan.</p>
          </div>
        </div>
      </div>

      <div class="item">
        <button data-target="six">
          <span>5. Sumber, Referensi & Video</span>
          <span class="chev">▸</span>
        </button>
        <div class="content" id="six">
          <div class="content-inner">
            <ul>
              <li><a class="ref" href="https://buku.kemdikbud.go.id/content/pdf/bukuteks/kurikulum21/Informatika_BG_KLS_XII.pdf" target="_blank">Buku Siswa Informatika — Kemdikbud</a></li>
              <li><a class="ref" href="https://kurikulum.kemdikbud.go.id/file/1711503412_manage_file.pdf" target="_blank">Panduan Kurikulum Merdeka</a></li>
              <li><a class="ref" href="https://www.ibm.com/think/topics/industry-4-0" target="_blank">IBM — What is Industry 4.0?</a></li>
              <li><a class="ref" href="https://www.sciencedirect.com/science/article/abs/pii/S0160791X20312574" target="_blank">Studi ilmiah — teknologi Industry 4.0</a></li>
            </ul>
            <h4>Video Edukasi: Revolusi Industri 4.0</h4>
            <div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;max-width:100%;border-radius:12px;">
              <iframe width="560" height="315" src="https://www.youtube.com/embed/YenRtYggPdM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;"></iframe>
            </div>
          </div>
        </div>
      </div>

      <div class="item">
        <button data-target="seven">
          <span>6. Latihan Soal</span>
          <span class="chev">▸</span>
        </button>
        <div class="content" id="seven">
          <div class="content-inner">
            <ol>
              <li>Apa yang dimaksud dengan Revolusi Industri 4.0?</li>
              <li>Sebutkan minimal 3 teknologi utama dalam Industri 4.0.</li>
              <li>Jelaskan peran IoT dalam industri modern.</li>
              <li>Contoh penerapan AI di bidang manufaktur adalah...</li>
              <li>Mengapa keamanan siber penting dalam era Industri 4.0?</li>
              <li>Big Data digunakan untuk...</li>
              <li>Robot kolaboratif (cobot) berfungsi untuk...</li>
              <li>Cloud computing memudahkan perusahaan dalam...</li>
              <li>Contoh penerapan Industri 4.0 di sektor pertanian adalah...</li>
              <li>Cyber-Physical Systems mengacu pada...</li>
              <li>Industri 4.0 mendorong perusahaan untuk...</li>
              <li>Teknologi yang memanfaatkan analisis data besar disebut...</li>
              <li>Manfaat utama otomatisasi dalam industri adalah...</li>
              <li>Pemikiran kritis menjadi penting karena...</li>
              <li>Contoh penerapan di sektor transportasi adalah...</li>
              <li>Kecerdasan buatan dapat membantu dalam...</li>
              <li>Penggunaan sensor pada mesin bertujuan untuk...</li>
              <li>Apa hubungan antara IoT dan Big Data?</li>
              <li>Cloud computing membantu UMKM dengan cara...</li>
              <li>Sebutkan satu tantangan utama dari penerapan Industri 4.0.</li>
            </ol>
          </div>
        </div>
      </div>

      <div class="item">
        <button data-target="eight">
          <span>7. Kunci Jawaban</span>
          <span class="chev">▸</span>
        </button>
        <div class="content" id="eight">
          <div class="content-inner">
            <ol>
              <li>Integrasi teknologi digital, fisik, dan biologis untuk otomatisasi dan efisiensi.</li>
              <li>IoT, AI, Big Data, Cloud Computing, Robotika, Keamanan Siber.</li>
              <li>Menghubungkan perangkat untuk memantau dan mengontrol secara real-time.</li>
              <li>Pengendalian kualitas otomatis menggunakan visi komputer.</li>
              <li>Untuk melindungi data dan sistem dari ancaman siber.</li>
              <li>Mengolah data dalam jumlah besar untuk analisis dan prediksi.</li>
              <li>Membantu pekerja melakukan tugas berat atau repetitif.</li>
              <li>Menyediakan penyimpanan dan pemrosesan data secara fleksibel.</li>
              <li>Pemupukan dan pengairan otomatis berbasis sensor tanah.</li>
              <li>Integrasi sistem fisik dengan komputasi dan komunikasi.</li>
              <li>Meningkatkan efisiensi dan daya saing.</li>
              <li>Big Data & Analytics.</li>
              <li>Meningkatkan produktivitas dan mengurangi kesalahan.</li>
              <li>Memecahkan masalah kompleks dan mengambil keputusan tepat.</li>
              <li>Manajemen lalu lintas cerdas.</li>
              <li>Memberikan rekomendasi atau keputusan otomatis.</li>
              <li>Mendeteksi kerusakan atau kebutuhan perawatan.</li>
              <li>IoT mengumpulkan data, Big Data menganalisisnya.</li>
              <li>Mengurangi biaya infrastruktur IT.</li>
              <li>Kurangnya SDM dengan keterampilan digital.</li>
            </ol>
          </div>
        </div>
      </div>

    </section>

    <footer>
      Disiapkan untuk presentasi kelas — tampilan bertema teknologi.
    </footer>
  </div>

  <script>
    document.querySelectorAll('.item button').forEach(btn => {
      btn.addEventListener('click', () => {
        const id = btn.getAttribute('data-target');
        const content = document.getElementById(id);
        const chev = btn.querySelector('.chev');
        const isOpen = content.style.maxHeight && content.style.maxHeight !== '0px';

        document.querySelectorAll('.content').forEach(c=>{c.style.maxHeight = null; c.style.paddingBottom='0'});
        document.querySelectorAll('.chev').forEach(c=>c.style.transform='rotate(0deg)');

        if(!isOpen){
          content.style.paddingBottom='12px';
          content.style.maxHeight = content.scrollHeight + 'px';
          chev.style.transform='rotate(90deg)';
        }
      });
    });

    window.addEventListener('load', ()=>{
      const first = document.querySelector('.item button');
      if(first) first.click();
    });
  </script>
</body>
</html>
