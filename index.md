<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<style>
  :root {
    --primary: #2563eb;
    --primary-hover: #1d4ed8;
    --bg-color: #f8fafc;
    --card-bg: #ffffff;
    --text-main: #0f172a;
    --text-muted: #64748b;
    --border: #e2e8f0;
  }

  body {
    font-family: 'Plus Jakarta Sans', sans-serif;
    background-color: var(--bg-color);
    color: var(--text-main);
  }

  .hero-header {
    background: linear-gradient(135deg, #0f172a, #1e293b);
    color: white;
    padding: 36px 24px;
    border-radius: 16px;
    text-align: center;
    margin-bottom: 32px;
    box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1);
  }

  .hero-header h1 {
    font-size: 1.8rem;
    font-weight: 700;
    margin-bottom: 8px;
    color: #ffffff;
  }

  .hero-header p {
    color: #94a3b8;
    font-size: 0.95rem;
    margin: 0;
  }

  .section-title {
    font-size: 1.25rem;
    font-weight: 700;
    margin: 32px 0 16px 0;
    display: flex;
    align-items: center;
    gap: 10px;
    color: var(--text-main);
  }

  .desc-text {
    color: var(--text-muted);
    font-size: 0.95rem;
    margin-bottom: 20px;
  }

  /* List Container Styling to match user's order */
  .list-wrapper {
    background: var(--card-bg);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 8px 20px;
    box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.02);
    margin-bottom: 32px;
  }

  .item-row {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 14px 0;
    border-bottom: 1px solid var(--border);
    gap: 16px;
    flex-wrap: wrap;
  }

  .item-row:last-child {
    border-bottom: none;
  }

  .item-info {
    display: flex;
    align-items: center;
    gap: 14px;
  }

  .item-number {
    font-weight: 700;
    color: var(--primary);
    background: #eff6ff;
    padding: 4px 10px;
    border-radius: 6px;
    font-size: 0.85rem;
    min-width: 32px;
    text-align: center;
  }

  .item-name {
    font-weight: 600;
    font-size: 1rem;
    color: var(--text-main);
    text-decoration: none;
  }

  .item-name:hover {
    color: var(--primary);
    text-decoration: underline;
  }

  .item-meta {
    color: var(--text-muted);
    font-size: 0.85rem;
  }

  .btn-link {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    background-color: #eff6ff;
    color: var(--primary);
    text-decoration: none;
    padding: 6px 12px;
    border-radius: 6px;
    font-weight: 600;
    font-size: 0.85rem;
    transition: all 0.2s;
  }

  .btn-link:hover {
    background-color: var(--primary);
    color: white;
  }

  /* Special style for Rangkuman UGC at the bottom */
  .ugc-box {
    background: linear-gradient(135deg, #eff6ff, #dbeafe);
    border: 1px solid #bfdbfe;
    border-radius: 12px;
    padding: 20px 24px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 16px;
    margin-top: 10px;
  }

  .ugc-info h3 {
    font-size: 1.05rem;
    color: #1e3a8a;
    margin: 0 0 4px 0;
    font-weight: 700;
  }

  .ugc-info p {
    color: #3b82f6;
    font-size: 0.85rem;
    margin: 0;
  }

  .btn-ugc {
    background-color: var(--primary);
    color: white !important;
    padding: 8px 16px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: 600;
    font-size: 0.9rem;
    display: inline-flex;
    align-items: center;
    gap: 8px;
  }

  .btn-ugc:hover {
    background-color: var(--primary-hover);
  }

  footer {
    text-align: center;
    margin-top: 40px;
    color: var(--text-muted);
    font-size: 0.85rem;
  }
</style>

<div class="hero-header">
  <h1><i class="fa-solid fa-book-bookmark"></i> Digital Library</h1>
  <p>Selamat Datang di Perpustakaan Digital — Koleksi Tugas GitHub Pages</p>
</div>

<div class="section-title">
  <i class="fa-solid fa-layer-group" style="color: var(--primary);"></i>
  <span>Koleksi E-Book & File Praktikum (Tugas 1)</span>
</div>
<p class="desc-text">Berikut ini adalah daftar koleksi lengkap dari nomor 1 sampai dengan 10:</p>

<div class="list-wrapper">
  <!-- 1 -->
  <div class="item-row">
    <div class="item-info">
      <span class="item-number">1</span>
      <div>
        <a href="ebook/file_praktek.pdf" target="_blank" class="item-name">file_praktek</a>
        <div class="item-meta">Alyssa Evangelia, dkk (2026)</div>
      </div>
    </div>
    <a href="ebook/file_praktek.pdf" target="_blank" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Buka Ebook</a>
  </div>

  <!-- 2 -->
  <div class="item-row">
    <div class="item-info">
      <span class="item-number">2</span>
      <div>
        <a href="ebook/bulan.pdf" target="_blank" class="item-name">Bulan</a>
        <div class="item-meta">Tere Liye (2015)</div>
      </div>
    </div>
    <a href="ebook/bulan.pdf" target="_blank" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Buka Ebook</a>
  </div>

  <!-- 3 -->
  <div class="item-row">
    <div class="item-info">
      <span class="item-number">3</span>
      <div>
        <a href="ebook/emma.pdf" target="_blank" class="item-name">Emma</a>
        <div class="item-meta">Jane Austen (1815)</div>
      </div>
    </div>
    <a href="ebook/emma.pdf" target="_blank" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Buka Ebook</a>
  </div>

  <!-- 4 -->
  <div class="item-row">
    <div class="item-info">
      <span class="item-number">4</span>
      <div>
        <a href="ebook/frankenstein.pdf" target="_blank" class="item-name">Frankenstein</a>
        <div class="item-meta">Mary Shelley (1818)</div>
      </div>
    </div>
    <a href="ebook/frankenstein.pdf" target="_blank" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Buka Ebook</a>
  </div>

  <!-- 5 -->
  <div class="item-row">
    <div class="item-info">
      <span class="item-number">5</span>
      <div>
        <a href="ebook/matahari.pdf" target="_blank" class="item-name">Matahari</a>
        <div class="item-meta">Tere Liye (2016)</div>
      </div>
    </div>
    <a href="ebook/matahari.pdf" target="_blank" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Buka Ebook</a>
  </div>

  <!-- 6 -->
  <div class="item-row">
    <div class="item-info">
      <span class="item-number">6</span>
      <div>
        <a href="ebook/negeridiujungtanduk.pdf" target="_blank" class="item-name">Negeri Di Ujung Tanduk</a>
        <div class="item-meta">Tere Liye (2013)</div>
      </div>
    </div>
    <a href="ebook/negeridiujungtanduk.pdf" target="_blank" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Buka Ebook</a>
  </div>

  <!-- 7 -->
  <div class="item-row">
    <div class="item-info">
      <span class="item-number">7</span>
      <div>
        <a href="ebook/persuasion.pdf" target="_blank" class="item-name">Persuasion</a>
        <div class="item-meta">Jane Austen (1817)</div>
      </div>
    </div>
    <a href="ebook/persuasion.pdf" target="_blank" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Buka Ebook</a>
  </div>

  <!-- 8 -->
  <div class="item-row">
    <div class="item-info">
      <span class="item-number">8</span>
      <div>
        <a href="ebook/prideandprejudice.pdf" target="_blank" class="item-name">Pride and Prejudice</a>
        <div class="item-meta">Jane Austen (1813)</div>
      </div>
    </div>
    <a href="ebook/prideandprejudice.pdf" target="_blank" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Buka Ebook</a>
  </div>

  <!-- 9 -->
  <div class="item-row">
    <div class="item-info">
      <span class="item-number">9</span>
      <div>
        <a href="ebook/senseandsensibility.pdf" target="_blank" class="item-name">Sense and Sensibility</a>
        <div class="item-meta">Jane Austen (1811)</div>
      </div>
    </div>
    <a href="ebook/senseandsensibility.pdf" target="_blank" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Buka Ebook</a>
  </div>

  <!-- 10 -->
  <div class="item-row">
    <div class="item-info">
      <span class="item-number">10</span>
      <div>
        <a href="ebook/thebrotherskaramazov.pdf" target="_blank" class="item-name">The Brothers Karamazov</a>
        <div class="item-meta">Fyodor Dostoevsky (1880)</div>
      </div>
    </div>
    <a href="ebook/thebrotherskaramazov.pdf" target="_blank" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Buka Ebook</a>
  </div>
</div>

<!-- TUGAS 2: Rangkuman UGC di paling bawah sesuai instruksi -->
<div class="section-title">
  <i class="fa-solid fa-file-lines" style="color: var(--primary);"></i>
  <span>Rangkuman UGC (Tugas 2)</span>
</div>

<div class="ugc-box">
  <div class="ugc-info">
<h3><i class="fa-solid fa-circle-check"></i> Rangkuman Pemaparan & Wawasan Baru UGC</h3>
    <p>File ringkasan kegiatan User-Generated Content (Format .pdf)</p>
  </div>
  <a href="ebook/RangkumanUGC.pdf" target="_blank" class="btn-ugc"><i class="fa-solid fa-file-arrow-down"></i> Buka Rangkuman UGC</a>
</div>

<footer>
  <p>Powered by GitHub Pages</p>
</footer>
