<div align="center">

<img src="src-tauri/icons/128x128.png" alt="AutoClip" width="72" height="72">

# AutoClip

### Satu tautan. Sekali klik.

Open source, pemotongan dan rendering jalan di komputer kamu. Tempel tautan, pilih platform, dan dapatkan <b>video, sampul, dan teks postingan</b>,<br>
untuk Douyin, Xiaohongshu, TikTok, Reels, YouTube Shorts, Bilibili, atau YouTube.<br>
Aplikasinya gratis; model cloud ditagih sesuai pemakaian. Buka editor kapan pun kamu mau menyesuaikan.

<p>
  <a href="https://github.com/zhouxiaoka/autoclip/releases/latest"><img src="https://img.shields.io/github/v/release/zhouxiaoka/autoclip?style=flat-square" alt="GitHub release"></a>
  <a href="https://github.com/zhouxiaoka/autoclip/stargazers"><img src="https://img.shields.io/github/stars/zhouxiaoka/autoclip?style=flat-square" alt="GitHub stars"></a>
  <a href="https://github.com/zhouxiaoka/autoclip/releases"><img src="https://img.shields.io/github/downloads/zhouxiaoka/autoclip/total?style=flat-square" alt="Downloads"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square" alt="License: MIT"></a>
</p>

<a href="https://trendshift.io/repositories/25801"><img src="https://trendshift.io/api/badge/repositories/25801" alt="AutoClip — GitHub Trending" width="250" height="55"></a>

**[Situs web](https://zhouxiaoka.github.io/autoclip_intro/)** · **[Unduh desktop](https://github.com/zhouxiaoka/autoclip/releases/latest)** · [Perpustakaan studi kasus](https://zhouxiaoka.github.io/autoclip_intro/cases/) · [Riset](docs/research/2026-10-what-drives-views/article-en.md) · [Mulai cepat](#quick-start) · [Dokumentasi](#documentation) · [Laporkan masalah](https://github.com/zhouxiaoka/autoclip/issues/new/choose)

[简体中文](README.md) · [English](README-EN.md) · [日本語](README-JA.md) · [한국어](README-KO.md) · [Español](README-ES.md) · [Português](README-PT.md) · [Русский](README-RU.md) · [Français](README-FR.md) · **Bahasa Indonesia**

</div>

> **Fork ini:** `isanovski/autoclip` — salinan `zhouxiaoka/autoclip` dengan antarmuka berbahasa Indonesia lengkap (2.120 teks UI) dan README ini. Kode asli oleh `zhouxiaoka`, lisensi MIT. Rilis, installer, dan dokumentasi di bawah tetap mengacu ke repo upstream karena fork ini tidak menerbitkan build sendiri.

**[Rilis terbaru](https://github.com/zhouxiaoka/autoclip/releases/latest)** adalah versi yang dilaporkan `autoclip --version`, dengan desktop, CLI, dan MCP diperbarui bersamaan. Lihat [changelog](CHANGELOG.md) untuk perbaikan keluaran cepat, penomoran halaman caption, framing pembicara, dan antrean video panjang. Silakan perbarui instalasi lama.

## Contoh klip nyata

Klik tangkapan layar atau “Play” untuk menonton klip penuhnya. Label bahasa mengacu pada subtitle hasil. Enam pilihan ditampilkan di bawah; buka untuk sepuluh lainnya.

### Potret · wawancara dan podcast layar penuh

<table width="100%">
<tr>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/gates-ezra/01.mp4?v=2026-10-01g"><img src="docs/images/demos/gates-ezra-01.jpg" width="180" alt="Bill Gates — AI测试时竟会装傻？"></a><br>
<strong>Bill Gates</strong><br>
Wawancara · Douyin · Mandarin<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/gates-ezra/01.mp4?v=2026-10-01g">▶ Play 1:01</a> · <a href="https://www.youtube.com/watch?v=A_156w0aYtU">Sumber</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/ai-labs-debate/01.mp4?v=2026-10-01g"><img src="docs/images/demos/ai-labs-debate-01.jpg" width="180" alt="AI Experts Debate — We&#x27;re Driving Toward a Cliff in the Fog"></a><br>
<strong>AI Experts Debate</strong><br>
Wawancara · Shorts · Inggris<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/ai-labs-debate/01.mp4?v=2026-10-01g">▶ Play 1:25</a> · <a href="https://www.youtube.com/watch?v=OhOmLqR5nN4">Sumber</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/robbins-36months/01.mp4?v=2026-10-01g"><img src="docs/images/demos/robbins-36months-01.jpg" width="180" alt="Tony Robbins — 风险极小，回报极大？"></a><br>
<strong>Tony Robbins</strong><br>
Podcast layar penuh · Douyin · Mandarin<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/robbins-36months/01.mp4?v=2026-10-01g">▶ Play 1:45</a> · <a href="https://www.youtube.com/watch?v=DuRcrbP3kag">Sumber</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/garfield-poehler/01.mp4?v=2026-10-01g"><img src="docs/images/demos/garfield-poehler-01.jpg" width="180" alt="Andrew Garfield × Amy Poehler — I Love Competition—but Hate Fake Casualness"></a><br>
<strong>Andrew Garfield × Amy Poehler</strong><br>
Podcast layar penuh · Shorts · Inggris<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/garfield-poehler/01.mp4?v=2026-10-01g">▶ Play 1:01</a> · <a href="https://www.youtube.com/watch?v=OJV8AaWCxQQ">Sumber</a>
</td>
</tr>
</table>

### Lanskap · framing asli

<table width="100%">
<tr>
<td align="center" valign="top" width="50%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/luyu-tongliya/01.mp4?v=2026-10-01g"><img src="docs/images/demos/luyu-tongliya-01.jpg" width="360" alt="佟丽娅 × 鲁豫 — 舞蹈是我骨子里的东西"></a><br>
<strong>佟丽娅 × 鲁豫</strong><br>
Framing asli · Bilibili · Mandarin<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/luyu-tongliya/01.mp4?v=2026-10-01g">▶ Play 1:41</a> · <a href="https://www.bilibili.com/video/BV1qheu6kEFV/">Sumber</a>
</td>
<td align="center" valign="top" width="50%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/altman-uses-ai/01.mp4?v=2026-10-01g"><img src="docs/images/demos/altman-uses-ai-01.jpg" width="360" alt="Sam Altman — AI是文艺复兴，还是工业革命？"></a><br>
<strong>Sam Altman</strong><br>
Framing asli · Bilibili · Mandarin<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/altman-uses-ai/01.mp4?v=2026-10-01g">▶ Play 2:02</a> · <a href="https://www.youtube.com/watch?v=jZh55CQwSh8">Sumber</a>
</td>
</tr>
</table>

<details>
<summary>Lihat 10 klip nyata lainnya</summary>

<table width="100%">
<tr>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/neumann-doac/01.mp4?v=2026-10-01g"><img src="docs/images/demos/neumann-doac-01.jpg" width="180" alt="Adam Neumann — Success is how you feel one minute before death—full of love, no regret"></a><br>
<strong>Adam Neumann</strong><br>
Podcast layar penuh · TikTok · Inggris<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/neumann-doac/01.mp4?v=2026-10-01g">▶ Play 0:59</a> · <a href="https://www.youtube.com/watch?v=IQ4JVWdj4Q0">Sumber</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/luyu-xiaoqi/02.mp4?v=2026-10-01g"><img src="docs/images/demos/luyu-xiaoqi-02.jpg" width="180" alt="小奇 × 鲁豫 — 想证明自己，又怕被注视"></a><br>
<strong>小奇 × 鲁豫</strong><br>
Wawancara · Douyin · Mandarin<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/luyu-xiaoqi/02.mp4?v=2026-10-01g">▶ Play 0:50</a> · <a href="https://www.bilibili.com/video/BV1ighy6AEPz/">Sumber</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/luyu-guokeyu/01.mp4?v=2026-10-01g"><img src="docs/images/demos/luyu-guokeyu-01.jpg" width="180" alt="郭柯宇 × 鲁豫 — 演员的快感在创作过程 不在结果"></a><br>
<strong>郭柯宇 × 鲁豫</strong><br>
Wawancara · Douyin · Mandarin<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/luyu-guokeyu/01.mp4?v=2026-10-01g">▶ Play 1:11</a> · <a href="https://www.bilibili.com/video/BV1LDYV6HEXR/">Sumber</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/dafoe-hot-ones/01.mp4?v=2026-10-01g"><img src="docs/images/demos/dafoe-hot-ones-01.jpg" width="180" alt="Willem Dafoe — Fake teeth made him feel lascivious and instantly became the character"></a><br>
<strong>Willem Dafoe</strong><br>
Podcast layar penuh · TikTok · Inggris<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/dafoe-hot-ones/01.mp4?v=2026-10-01g">▶ Play 1:07</a> · <a href="https://www.youtube.com/watch?v=YqugY2zTIoI">Sumber</a>
</td>
</tr>
<tr>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/tim-luoyonghao/01.mp4?v=2026-10-01g"><img src="docs/images/demos/tim-luoyonghao-01.jpg" width="180" alt="TIM × 罗永浩 — 红得快的网红 糊得更快"></a><br>
<strong>TIM × 罗永浩</strong><br>
Wawancara · Douyin · Mandarin<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/tim-luoyonghao/01.mp4?v=2026-10-01g">▶ Play 1:05</a> · <a href="https://www.bilibili.com/video/BV1B5xkzPEhx/">Sumber</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/jensen-dwarkesh/01.mp4?v=2026-10-01g"><img src="docs/images/demos/jensen-dwarkesh-01.jpg" width="180" alt="Jensen Huang — AI是五层蛋糕 能源才是底层"></a><br>
<strong>Jensen Huang</strong><br>
Wawancara · Xiaohongshu · Mandarin<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/jensen-dwarkesh/01.mp4?v=2026-10-01g">▶ Play 1:17</a> · <a href="https://www.youtube.com/watch?v=Hrbq66XqtCo">Sumber</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/karpathy-dwarkesh/01.mp4?v=2026-10-01g"><img src="docs/images/demos/karpathy-dwarkesh-01.jpg" width="180" alt="Andrej Karpathy — AI还不能当实习生用 因认知能力严重不足"></a><br>
<strong>Andrej Karpathy</strong><br>
Wawancara · Douyin · Mandarin<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/karpathy-dwarkesh/01.mp4?v=2026-10-01g">▶ Play 0:43</a> · <a href="https://www.youtube.com/watch?v=lXUZvyajciY">Sumber</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/apple-a20/01.mp4?v=2026-10-01g"><img src="docs/images/demos/apple-a20-01.jpg" width="180" alt="A20 Pro — 苹果芯片不是拼乐高"></a><br>
<strong>A20 Pro</strong><br>
Wawancara · Xiaohongshu · Mandarin<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/apple-a20/01.mp4?v=2026-10-01g">▶ Play 2:00</a> · <a href="https://www.bilibili.com/video/BV1e4Y96FEaJ/">Sumber</a>
</td>
</tr>
<tr>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/stallone-nyt/01.mp4?v=2026-10-01g"><img src="docs/images/demos/stallone-nyt-01.jpg" width="180" alt="Sylvester Stallone — 60岁写《洛奇》 是向衰老宣战"></a><br>
<strong>Sylvester Stallone</strong><br>
Wawancara · Douyin · Mandarin<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/stallone-nyt/01.mp4?v=2026-10-01g">▶ Play 1:39</a> · <a href="https://www.youtube.com/watch?v=ccs-B_nTfZs">Sumber</a>
</td>
<td align="center" valign="top" width="25%">
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/mrbeast-colin-samir/01.mp4?v=2026-10-01g"><img src="docs/images/demos/mrbeast-colin-samir-01.jpg" width="180" alt="MrBeast — YouTube&#x27;s first 5 seconds matter more than thumbnails"></a><br>
<strong>MrBeast</strong><br>
Podcast layar penuh · TikTok · Inggris<br>
<a href="https://pub-3fb92949b9c2480b89feec5ec03f3540.r2.dev/cases/mrbeast-colin-samir/01.mp4?v=2026-10-01g">▶ Play 1:42</a> · <a href="https://www.youtube.com/watch?v=9IQ_ldV9z_A">Sumber</a>
</td>
<td></td>
<td></td>
</tr>
</table>

</details>

Temukan video, sampul, dan teks postingan di **[perpustakaan studi kasus →](https://zhouxiaoka.github.io/autoclip_intro/cases/?lang=en)**, dan [bagikan klipmu](https://github.com/zhouxiaoka/autoclip/discussions/new?category=show-and-tell). Video sumber milik pembuatnya masing-masing; klip ini hanya untuk demonstrasi.

## Apa yang dilakukannya

### Tempel tautan, dapat klip

Pilih platform agar hasilnya mengikuti aturan frame dan durasinya. Tiap platform otomatis merender sampai 10 klip layak dengan skor tertinggi; sisanya tersedia sesuai permintaan. Setiap klip membawa sampul, judul, deskripsi, tagar, dan paket publikasi ZIP.

### Pengemasan sudah bawaan

Douyin / Xiaohongshu default ke gaya wawancara; TikTok / Reels / Shorts default ke gaya podcast layar penuh. Kamu bisa memilih salah satu tata letak vertikal tanpa mengubah bahasa caption/teks platformnya. Bilibili / YouTube memakai lanskap. Framing mengikuti pembicara dan mempertahankan frame utuh kalau tidak ada orang terdeteksi. Outro merek aktif secara default dan bisa dimatikan di Pengaturan; teks postingan yang disalin tidak memuat kredit AutoClip.

### Tetap di komputer kamu

Pemotongan, framing, dan rendering jalan lokal. Pilih model analisis dan gunakan caption dari pembuat, Whisper / SenseVoice lokal, atau transkripsi cloud yang dikonfigurasi. CLI / MCP memakai pipeline keluaran cepat yang sama dengan desktop.

## Waktu dan biaya pada sumber nyata

Ini pengukuran dari tiga sumber berbeda selama pengembangan, bukan perbandingan terkontrol dengan input yang sama. Biaya adalah perkiraan pemakaian model teks qwen-plus saat itu dan tidak termasuk ASR cloud, gambar AI, serta layanan publikasi. Tagihan penyedia kamu yang berlaku.

| Versi | Sumber | Keluaran | Perkiraan biaya model teks (CNY) |
| --- | --- | ---: | ---: |
| **Baru · dengan caption** | Jensen · 1j43m (EN → Xiaohongshu) | **7,5 mnt / 10 klip** | **¥0,09** |
| Baru · tanpa caption | TIM × Luo Yonghao · 2j52m (ZH → Douyin) | 29,5 mnt / 10 klip | ¥0,20 |
| Sebelumnya | MrBeast · 2j06m (EN → TikTok) | 65 mnt | ¥0,64 |

<details>
<summary>Kondisi dan catatan</summary>

1 Oktober 2026, Mac Apple Silicon yang sama. Dua jalan pertama memakai pipeline baru dan merender 10 klip; pipeline lama merender 33, dengan jumlah input dan output berbeda. Jensen memakai caption dari pembuat; TIM memakai Whisper lokal `base`.

Caption dari pembuat melewati transkripsi; kalau tidak ada, pilih ASR lokal atau cloud. Platform tambahan dan klip sesuai permintaan menambah waktu dan pemakaian. Lihat [pengukuran dan penghitungan biaya](docs/COST_PER_VIDEO.md) (Mandarin) untuk catatan tiap tahap dan asumsinya.

</details>

## Pilih model dan alur data

Pemotongan dan rendering jalan di komputer kamu. Analisis cloud mengirim caption dan teks postingan yang relevan; pemahaman visual atau pembuatan gambar referensi mengirim frame sampel yang diperlukan, dan ASR cloud mengirim audio. Analisis dan transkripsi lokal tidak memerlukan API cloud terkait. Klip jadi diunggah ke platform terhubung saat kamu memilih mempublikasikan. Analitik dan laporan galat bisa dimatikan di Pengaturan. Lihat [privasi](docs/PRIVACY.en.md).

<a id="quick-start"></a>

## Mulai cepat

| Kamu mau | Pakai | Kamu butuh |
| --- | --- | --- |
| Membuat klip di komputer ini | **Desktop** | macOS Apple Silicon atau Windows x64 |
| Self-host / Linux | **Docker** | Docker dan Compose v2 |
| Batch / agen | **CLI / MCP** | Python 3.10+ (disarankan 3.11) dan FFmpeg |

### Desktop

1. **Pasang.** Unduh dari [Releases](https://github.com/zhouxiaoka/autoclip/releases/latest). macOS Apple Silicon: `.dmg`. Windows 10 / 11 x64: `-setup.exe`. Python dan FFmpeg sudah dibundel. Di macOS 15 ke atas, klik dua kali sekali; kalau diblokir, buka System Settings → Privacy & Security → Open Anyway ([catatan Apple](https://developer.apple.com/news/?id=saqachfa)). Di macOS lama, klik kanan aplikasi lalu pilih Open. Kalau Windows SmartScreen muncul, pilih More info → Run anyway.
2. **Konfigurasi model.** Pilih penyedia dan masukkan kunci API-nya, pilih model analisis yang tersedia, tes koneksi, lalu simpan. Untuk model lokal, jalankan Ollama / LM Studio dan muat model dulu.
3. **Lihat contohnya, lalu pakai videomu sendiri.** Saat layar utama belum punya proyek, klik “Buka proyek contoh”. Tidak perlu kunci API; contohnya ada di dalam installer. Lalu pakai wawancara atau podcastmu sendiri dan pilih tata letak vertikal. Kalau sumbernya tidak punya subtitle, atau Whisper lokal gagal dipasang atau terlalu lambat, buka Pengaturan → Model default → “Suara ke subtitle” lalu beralih ke transkripsi cloud Bailian (`qwen-audio-3.1-asr-flash`, sekitar 0,1 yuan per jam audio; tagihan Alibaba Cloud yang berlaku). Audio diunggah ke cloud. Kalau impor terhalang, klik “Pakai transkripsi cloud saja”. Instalasi lokal pertama mengunduh sekitar 220 MB, sekitar 15 menit di jaringan lambat.
4. **Tinjau dan unduh.** Periksa caption, framing, dan keutuhan konten, lalu simpan paket publikasi atau hubungkan akun untuk mempublikasikan. Buat alternatif sesuai permintaan kalau butuh klip lebih banyak.

Tidak ada build desktop untuk Intel Mac. Intel Mac dan Linux memakai Docker atau CLI. Lihat [panduan instalasi](docs/USER_INSTALLATION_GUIDE.en.md) dan [Release terbaru](https://github.com/zhouxiaoka/autoclip/releases/latest).

[Panduan instalasi lengkap](docs/USER_INSTALLATION_GUIDE.en.md) · [Pemecahan masalah](docs/FAQ.en.md)

**Docker / Web**

```bash
git clone https://github.com/zhouxiaoka/autoclip.git
cd autoclip
cp env.example .env
mkdir -p data logs uploads
docker compose up -d --build
```

Buka [web UI](http://localhost:3000). [Dokumentasi API](http://localhost:8000/docs) tersedia setelah backend jalan. Lihat [panduan Docker](docs/DOCKER.en.md).

Di Linux, kalau bind mount gagal karena izin, perbaiki kepemilikan dulu:

```bash
docker compose run --rm --no-deps --user root --entrypoint sh autoclip -c 'chown -R autoclip:autoclip /app/data /app/logs /app/uploads'
docker compose up -d
```

Untuk IP LAN atau domain khusus, tambahkan alamat frontend ke `AUTOCLIP_ALLOWED_ORIGINS` di `.env` (dipisah koma).

**CLI / MCP**

Butuh Python 3.10+ (disarankan 3.11), dengan FFmpeg dan FFprobe di PATH; CLI lokal tidak perlu Redis. Unduh [ZIP CLI / MCP resmi](https://github.com/zhouxiaoka/autoclip/releases/latest), ekstrak, lalu jalankan di direktori itu:

```bash
python3 -m venv venv
source venv/bin/activate
python -m pip install -r requirements.txt
python -m pip install --force-reinstall --no-deps autoclip_mcp-*-py3-none-any.whl
```

Tanpa ZIP, pasang dengan satu perintah. Instalasi dari checkout sumber yang sudah di-clone tetap tersedia:

```bash
# 一行安装
uvx autoclip-mcp
npx skills add zhouxiaoka/autoclip
```

```bash
# 备选：在已克隆的仓库根目录从源码安装
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m pip install --no-deps .
autoclip --version
```

Perintah di atas untuk macOS / Linux. Di Windows, buat dengan `py -m venv venv` dan aktifkan dengan `.\venv\Scripts\Activate.ps1`, lalu pakai perintah instalasi `python -m pip` yang sama.

Simpan pengaturan model dulu: pakai ulang pengaturan desktop, atau konfigurasi direktori data sendiri dari contoh tanpa kunci di ZIP. Lihat [panduan CLI / MCP](docs/CLI_AND_MCP.md) (Mandarin). `produce` tidak memakai override lama `run --provider`. Berikan `--srt` untuk melewati transkripsi.

```bash
autoclip --version
autoclip produce talk.mp4 --srt talk.srt --platform douyin --portrait-style podcast --json
autoclip outputs PROJECT_ID --export-kits
```

Klien MCP yang menyalakan server. Untuk debugging mandiri, jalankan `autoclip mcp` di terminal terpisah; pengguna OpenCode bisa menulis konfigurasi klien dengan `autoclip mcp install opencode`.

Ganti `PROJECT_ID` dengan ID proyek yang dikembalikan produksi. MCP memakai `start_quick_output` / `get_quick_output_status`; set `command` di klien ke path absolut `autoclip` milik virtualenv dan `args` ke `["mcp"]`. `run` / `export` lama dan alat clipping tetap tersedia. Lihat [CLI / MCP](docs/CLI_AND_MCP.md) (Mandarin), [OpenCode](docs/OPENCODE.en.md), dan [Agent skill](skills/autoclip/SKILL.md) (Mandarin).

Listing stdio lokal Smithery memakai bundel MCPB. Dari akar repo, jalankan `python scripts/pack_mcpb.py`. Artifact-nya `dist/autoclip-mcp.mcpb` dan tidak di-commit. Publikasikan dengan `smithery mcp publish ./dist/autoclip-mcp.mcpb -n io.github.zhouxiaoka/autoclip-mcp` memakai login pemelihara sendiri. Repo tidak menyimpan kunci API. Langkahnya ada di [CLI / MCP](docs/CLI_AND_MCP.md) (Mandarin).

## Penyiapan model

| Opsi | Penyiapan |
| --- | --- |
| API cloud | Pilih penyedia di Pengaturan dan masukkan kunci API-mu. Layanan kompatibel OpenAI juga menerima Base URL. |
| Ollama | Default `http://localhost:11434/v1`; unduh dan jalankan model lokal, lalu pilih model yang disediakan server-mu. Tanpa kunci API. |
| LM Studio | Muat model dan jalankan Local Server, default `http://localhost:1234/v1`. |

Di dalam Docker, `localhost` adalah container-nya. Arahkan ke alamat host yang bisa dijangkau container.

[Penyiapan model](docs/MULTI_LLM_PROVIDER_GUIDE.md) (Mandarin) · [Model lokal dan container](docs/CLI_AND_MCP.md) (Mandarin)

## Terima kasih khusus ❤️

<table>
  <tr>
    <td align="center" width="140">
      <a href="https://88api.ai/sign-up?aff=2PIc"><img src="docs/sponsors/88api-logo.jpg" alt="88API" width="88"></a><br>
      <a href="https://88api.ai/sign-up?aff=2PIc"><strong>88API</strong></a>
    </td>
    <td>
      Terima kasih kepada <strong>88API Token Platform</strong> yang mensponsori AutoClip! Platform ini menyatukan GPT, Claude, Gemini, Grok, DeepSeek, Kimi, dan GLM untuk analisis transkrip, pemilihan highlight, dan pembuatan judul.<br>
      🎨 <strong>Kemampuan media</strong>: Platform menyediakan model gambar, video, dan audio, termasuk GPT-Image, Seedance, Veo, MiniMax Hailuo H3, Kling, Whisper, dan TTS. AutoClip memakai API analisis, gambar sampul, dan transkripsi yang kompatibel.<br>
      🏷️ <strong>Layanan dan penagihan</strong>: Mitra melaporkan operasi korporat luar negeri, dukungan langsung, invoice, dan rasio isi ulang 1:1; ketentuan platform berlaku.<br>
      🎁 <strong>Penawaran pengguna baru</strong>: Dapatkan kredit percobaan untuk menguji model lewat <a href="https://88api.ai/sign-up?aff=2PIc">tautan pendaftaran referral</a> kami, sesuai ketentuan promosi. <a href="docs/88API_SETUP.en.md">Panduan penyiapan</a>
    </td>
  </tr>
  <tr>
    <td align="center" width="140">
      <a href="https://www.infistar.cc/register?aff=XLK3BCM6&amp;ref_source=link"><img src="docs/sponsors/infistar-logo.svg" alt="Infistar" width="88"></a><br>
      <a href="https://www.infistar.cc/register?aff=XLK3BCM6&amp;ref_source=link"><strong>Infistar.cc</strong></a>
    </td>
    <td>
      Terima kasih kepada <strong>Infistar.cc</strong> yang mensponsori AutoClip! Layanan API multi-model-nya bisa mendukung analisis transkrip video panjang, pemilihan highlight, dan pembuatan judul.<br>
      ⚙️ <strong>Penyiapan kompatibel</strong>: Pilih penyedia kompatibel OpenAI di AutoClip lalu masukkan Base URL, kunci API-mu, dan model yang tersedia.<br>
      🧩 <strong>Pilihan model</strong>: Mitra menawarkan Claude, GPT, Gemini, DeepSeek, dan keluarga model lain. Pilih model yang mendukung endpoint kompatibel untuk membandingkan analisis transkrip dan pemilihan highlight.<br>
      🏷️ <strong>Harga dan layanan</strong>: Menurut mitra, model tertentu berbiaya serendah <strong>1% dari harga resmi</strong>, dengan penagihan RMB, invoice, dan verifikasi keaslian model. Periksa platform untuk model yang memenuhi syarat, harga terkini, dan ketentuan layanan.<br>
      🎁 <strong>Penawaran AutoClip</strong>: Pengguna baru bisa menerima <strong>kredit percobaan $5</strong> lewat <a href="https://www.infistar.cc/register?aff=XLK3BCM6&amp;ref_source=link">tautan pendaftaran referral</a> kami, sesuai ketentuan promosi. <a href="docs/INFISTAR_SETUP.en.md">Panduan penyiapan</a>
    </td>
  </tr>
  <tr>
    <td align="center" width="140">
      <a href="https://go.apimart.ai/tw-autoclip"><img src="docs/sponsors/apimart.png" alt="APIMart" width="88"></a><br>
      <a href="https://go.apimart.ai/tw-autoclip"><strong>APIMart</strong></a>
    </td>
    <td>
      Terima kasih kepada <strong>APIMart</strong> yang mensponsori proyek ini! <strong>APIMart</strong> adalah platform API berbiaya rendah untuk pembuatan gambar &amp; video AI — GPT-Image-2 mulai <strong>$0,006/gambar</strong>, <strong>160+</strong> gambar per dolar. Satu API asinkron mencakup gambar dan video: kirim tugas, dapatkan ID, ambil hasil lewat polling atau callback. Batch puluhan ribu gambar tanpa timeout, ganti model tanpa mengubah kode. Bayar sesuai pemakaian tanpa biaya bulanan — <a href="https://go.apimart.ai/tw-autoclip">daftar di sini</a> untuk mulai.
    </td>
  </tr>
</table>

## Tautan rekomendasi

Ini tautan rekomendasi penulis. Terpisah dari sponsor di atas.

Pakai untuk mendaftar di Alibaba Cloud atau klaim penawarannya, lalu buat kunci API di konsol Bailian. Di AutoClip, buka Pengaturan → Model default → “Suara ke subtitle” untuk memakai transkripsi cloud Bailian. Audio diunggah ke cloud.

1. [Tautan rekomendasi penulis](https://www.aliyun.com/benefit?userCode=qmyj6jch): daftar atau klaim penawarannya.
2. [Konsol Bailian](https://bailian.console.aliyun.com/): buat kunci API.

## FAQ

<details>
<summary>Gratis? Perlu kunci API?</summary>

Aplikasinya gratis dan berlisensi MIT. Analisis cloud, transkripsi, dan gambar AI memakai kredensialmu dan tarif penyedia; desain sampul otomatis tidak memakai pembuatan gambar berbayar secara default. Ollama / LM Studio tidak perlu kunci cloud tapi butuh hardware yang memadai. Publikasi langsung butuh akun Bilibili atau [Upload-Post](https://www.upload-post.com) milikmu.

</details>

<details>
<summary>Apakah video saya diunggah?</summary>

Pemotongan dan rendering jalan di komputer kamu. Analisis cloud mengirim caption dan teks postingan yang relevan; pemahaman visual atau pembuatan gambar referensi mengirim frame sampel yang diperlukan, dan ASR cloud mengirim audio. Analisis dan transkripsi lokal tidak memerlukan API cloud terkait. Klip jadi diunggah ke platform terhubung saat kamu memilih mempublikasikan. Analitik dan laporan galat bisa dimatikan di Pengaturan. Lihat [privasi](docs/PRIVACY.en.md).

</details>

<details>
<summary>Video seperti apa yang paling cocok?</summary>

Wawancara, podcast, kursus, dan rekaman talking-head adalah kasus penggunaan utama yang sudah tervalidasi. Caption dari pembuat paling cepat; kalau tidak ada, pakai transkripsi lokal atau cloud. Untuk gameplay atau rekaman minim dialog, aktifkan pemahaman visual dengan model yang bisa membaca gambar dan tinjau momen yang dipilih.

</details>

<details>
<summary>Kenapa tidak ada klip yang dihasilkan?</summary>

Periksa tahap yang gagal: caption/transkripsi, koneksi model, FFmpeg, ruang disk, dan kelayakan platform. YouTube video panjang butuh klip utuh minimal 180 detik; pakai Shorts atau Bilibili untuk rekaman lebih pendek. Kalau masih gagal, sertakan versi dari `autoclip --version`, OS, durasi sumber, model, dan log yang sudah disamarkan di [masalah yang diketahui](https://github.com/zhouxiaoka/autoclip/issues/96).

</details>

[Pemecahan masalah lengkap](docs/FAQ.en.md) · [Masalah yang diketahui](https://github.com/zhouxiaoka/autoclip/issues/96)

<a id="documentation"></a>

## Dokumentasi

| Kamu mau | Dokumen |
| --- | --- |
| Memasang dan klip pertama | [Instalasi](docs/USER_INSTALLATION_GUIDE.en.md) |
| Self-host dan otomatisasi | [Docker](docs/DOCKER.en.md) · [CLI / MCP](docs/CLI_AND_MCP.md) (Mandarin) · [Agent skill](skills/autoclip/SKILL.md) (Mandarin) · [OpenCode](docs/OPENCODE.en.md) |
| Model dan pemecahan masalah | [Penyiapan model](docs/MULTI_LLM_PROVIDER_GUIDE.md) (Mandarin) · [FAQ](docs/FAQ.en.md) |
| Versi, roadmap, privasi | [Changelog](CHANGELOG.md) · [Roadmap](ROADMAP.md) (Mandarin) · [Papan komunitas](docs/COMMUNITY_BOARD.md) (Mandarin) · [Privasi](docs/PRIVACY.en.md) |
| Riset | [Catatan riset #1: Pilih momennya, bukan efeknya](docs/research/2026-10-what-drives-views/article-en.md) · [中文](docs/research/2026-10-what-drives-views/article-zh.md) |
| Berkontribusi dan menerjemahkan | [Panduan kontribusi](CONTRIBUTING.md) (Mandarin) · [Pemeliharaan terjemahan](docs/i18n.md) (Mandarin) |

## Berkontribusi

Perbaikan, contoh klip, masukan, dan peningkatan terjemahan sangat diterima. Kalau AutoClip membantumu, star sangat dihargai.

- **Diskusi:** [GitHub Discussions](https://github.com/zhouxiaoka/autoclip/discussions) · [Tanya jawab klip pertama](https://github.com/zhouxiaoka/autoclip/discussions/128) · [Ide](https://github.com/zhouxiaoka/autoclip/discussions/129)
- **Bug:** pakai [form issue](https://github.com/zhouxiaoka/autoclip/issues/new/choose) dengan OS, versi, model, langkah reproduksi, dan log yang sudah disamarkan
- **Kemitraan:** [christine_zhouye@163.com](mailto:christine_zhouye@163.com)

Dipelihara oleh satu orang. Balasan tidak instan; tidak ada dukungan langsung atau bantuan deploy satu-satu.

![Star History](https://api.star-history.com/svg?repos=zhouxiaoka/autoclip&type=Date)

Terima kasih kepada FastAPI, React, Tauri, FFmpeg, yt-dlp, Whisper, FunASR, dan semua kontributor. [MIT License](LICENSE).
