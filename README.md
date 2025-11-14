<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Kelurahan Kalipang</title>
  <style>
    /* Mobile-first simple styling */
    :root{--accent:#0ea5a4;--bg:#f8fafc;--card:#ffffff;--muted:#6b7280}
    *{box-sizing:border-box}
    body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial;background:var(--bg);color:#111}
    header{background:linear-gradient(90deg,#06b6d4 0%,#7dd3fc 100%);padding:14px 16px;color:#fff;display:flex;align-items:center;justify-content:space-between}
    .brand{font-weight:700;letter-spacing:0.3px}
    nav{display:flex;gap:12px}
    .btn{background:rgba(255,255,255,0.15);border:0;padding:8px 10px;border-radius:10px;color:#fff;font-weight:600}
    main{padding:16px}
    .hero{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(2,6,23,0.06);}
    h1{margin:0 0 8px;font-size:20px}
    p.lead{margin:0 0 12px;color:var(--muted)}
    .grid{display:grid;gap:12px;margin-top:12px}
    .card{background:var(--card);padding:12px;border-radius:10px;box-shadow:0 4px 14px rgba(2,6,23,0.04)}
    .actions{display:flex;gap:8px;flex-wrap:wrap}
    .cta{background:var(--accent);color:#fff;border:0;padding:10px 12px;border-radius:10px;font-weight:700}
    footer{padding:16px;text-align:center;color:var(--muted);font-size:13px}

    /* Responsive layout */
    @media(min-width:640px){
      h1{font-size:26px}
      .grid{grid-template-columns:repeat(2,1fr)}
    }

    /* Simple hamburger for very small screens */
    .hamburger{display:inline-block;cursor:pointer;padding:8px;border-radius:8px}
    .hamburger span{display:block;width:20px;height:2px;background:#fff;margin:4px 0;border-radius:2px}
    .mobile-nav{display:none;position:absolute;right:12px;top:60px;background:var(--card);color:#111;padding:12px;border-radius:10px;box-shadow:0 10px 30px rgba(2,6,23,0.08)}
    .mobile-nav a{display:block;padding:8px 0}
    @media(min-width:640px){.hamburger{display:none}.mobile-nav{display:none}}
  </style>
</head>
<body>
  <header>
    <div style="display:flex;align-items:center;gap:12px">
      <div class="brand">LAYANAN INFORMASI MUTASI PAJAK KALIPANG</div>
      <div style="font-size:13px;opacity:.9"></div> 
    </div>

    <div style="display:flex;align-items:center;gap:10px">
      <nav class="desktop-nav" style="display:none">
        <a class="btn" href="#">Beranda</a>
        <a class="btn" href="#fitur">Fitur</a>
        <a class="btn" href="#kontak">Kontak</a>
      </nav>
      <div class="hamburger" id="hb" aria-label="menu" role="button" tabindex="0">
        <span></span><span></span><span></span>
      </div>
    </div>

    <div class="mobile-nav" id="mobileNav" aria-hidden="true">
      <a href="#">Beranda</a>
      <a href="#fitur">Fitur</a>
      <a href="#kontak">Kontak</a>
    </div>
  </header>

  <main>
    <section class="hero">
      <p style="text-align: center; class="lead">LIMJA adalah layanan informasi mutasi pajak kelurahan kalipang. Tujaun adanya halaman ini agar wajib pajak mengerti tentang jenis mutasi pajak atau pecah pajak mulai dari pengertian dan syarat-syarat yang harus dipenuhi untuk mengajukan mutasi pajak atau  pecah pajak.</p>
      <div class="actions">
       	<button class="cta" onclick="scrollToSection('Jenis Mutasi')">Jenis Mutasi</button>
	<button class="cta" onclick="scrollToSection('Syarat Mutasi')">Syarat Mutasi</button>
        	<button class="btn" onclick="scrollToSection('kontak')">Hubungi</button>
      </div>
    </section>

    <div class="card" style="margin-top:16px">
      <div class="card" id="Jenis Mutasi">
        <h1>Jenis Mutasi</h1>
         	<h3>Mutasi Pecah Penuh</h3>
	<p>Mutasi ini terjadi apabila sebidang tanah dijual atau diwariskan atau dihibahkan secara keseluruhan tanpa ada sisa untuk penjual, pemberi waris atau pemberi hibah</p>
          	<h3>Mutasi Pecah Sisa</h3>
	<p>Mutasi ini terjadi apabila sebidang tanah dijual atau diwariskan atau dihibahkan secara sebagian dan masih ada sisa untuk penjual, pemberi waris atau pemberi hibah</p>
         	<h3>Mutasi Pecah Habis</h3>
	<p>Mutasi ini terjadi apabila sebidang tanah habis dibagi waris atau di jual atau dihibahkan kepada beberapa penerima pembeli atau penerima waris atau penerima hibah tanpa ada sisa untuk penjual, pemberi waris atau pemberi hibah</p>
      </div>

      	<div class="card" id="Syarat Mutasi">
        	<h1>Syarat Mutasi</h1>
	<h3>Mutasi Pecah Penuh</h3>
	<p>1. SPPT Tahun berjalan (Tahun 2026)</p>
	<p>2. SPPT Wajib dibayarkan di Bank Jatim</p>
	<p>3. Fotocopy KTP pemilik Baru</p>
	<p>4. Fotocopy Sertifikat Hak Milik Pemilik Baru</p>
	<p>5. Apabila surat tanah masih berupa Letter C, Wajib melampirkan Fotocopy Letter C dan Fotocopy Surat Perolehan tanah </p>
	<p style="text-indent: 12px;">(Surat Jual Beli atau Surat Waris Atau Surat Hibah) Pemilik Baru</p>
	<p>&nbsp;</p>
          	<h3>Mutasi Pecah Sisa</h3>
	<p>1. SPPT Tahun berjalan (Tahun 2026)</p>
	<p>2. SPPT Wajib dibayarkan di Bank Jatim</p>
	<p>3. Fotocopy KTP pemilik Baru</p>
	<p>4. Fotocopy KTP pemilik Lama</p>
	<p>5. Fotocopy Sertifikat Hak Milik Pemilik Baru</p>
	<p>6. Fotocopy Sertifikat Hak Milik Pemilik Lama</p>
	<p>5. Apabila surat tanah masih berupa Letter C Wajib melampirkan Fotocopy Letter C dan Fotocopy Surat Perolehan tanah</p>
	<p style="text-indent: 12px;">(Surat Jual Beli atau Surat Waris Atau Surat Hibah) Pemilik Lama dan Pemilik Baru</p>
	<p>&nbsp;</p>
         	<h3>Mutasi Pecah Habis</h3>
      	</div>

      <div class="card" id="kontak">
        <h3>Kontak</h3>
        <p class="lead">Form sederhana (menggunakan mailto) — jika mau form dinamis, perlu server atau layanan pihak ketiga.</p>
        <form onsubmit="sendMail(event)">
          <label style="display:block;margin-bottom:6px;font-size:13px">Nama</label>
          <input name="nama" type="text" placeholder="Nama Anda" style="width:100%;padding:8px;border-radius:8px;border:1px solid #e6eef2;margin-bottom:8px">
          <label style="display:block;margin-bottom:6px;font-size:13px">Pesan</label>
          <textarea name="pesan" rows="3" placeholder="Tulis pesan..." style="width:100%;padding:8px;border-radius:8px;border:1px solid #e6eef2;margin-bottom:8px"></textarea>
          <div style="display:flex;gap:8px">
            <button type="submit" class="cta">Kirim</button>
            <button type="button" class="btn" onclick="clearForm(this)">Bersihkan</button>
          </div>
        </form>
      </div>

    </div>
  </main>

  <footer>
    © " + new Date().getFullYear().toString() + " — Dibuat dengan ❤️ untuk ponsel"
  </footer>

  <script>
    // Small JS: menu, smooth scroll, form -> mailto
    const hb = document.getElementById('hb');
    const mobileNav = document.getElementById('mobileNav');
    hb.addEventListener('click', ()=>{
      const shown = mobileNav.style.display === 'block';
      mobileNav.style.display = shown ? 'none' : 'block';
      mobileNav.setAttribute('aria-hidden', shown ? 'true' : 'false');
    });

    function scrollToSection(id){
      document.getElementById(id).scrollIntoView({behavior:'smooth'});
    }

    function sendMail(e){
      e.preventDefault();
      const form = e.target;
      const nama = encodeURIComponent(form.nama.value || 'Pengguna');
      const pesan = encodeURIComponent(form.pesan.value || '');
      const subject = encodeURIComponent('Pesan dari situs: ' + nama);
      const body = encodeURIComponent('Nama: ' + nama + '\n\n' + decodeURIComponent(pesan));
      // opens user's email app
      window.location.href = `mailto:example@domain.com?subject=${subject}&body=${body}`;
    }

    function clearForm(btn){
      const form = btn.closest('form');
      form.reset();
    }
  </script>
</body>
</html>
