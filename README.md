<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CV. TIGA PUTRA JAYA</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background-color: #1c1c1c;
    color: #fff;
}

/* HERO SECTION */
.hero {
    height: 100vh;
    background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.8)),
                url('https://images.unsplash.com/photo-1586773860418-d37222d8fce3') center/cover;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 20px;
}

.hero-content h1 {
    font-size: 70px;
    color: #ff7a00;
    margin: 0;
    letter-spacing: 3px;
}

.hero-content p {
    font-size: 20px;
    margin: 15px 0;
    color: #ddd;
}

.buttons {
    margin-top: 25px;
}

.btn {
    padding: 12px 25px;
    margin: 5px;
    border: none;
    cursor: pointer;
    font-size: 16px;
    border-radius: 30px;
    transition: 0.3s;
}

.btn-primary {
    background: #ff7a00;
    color: white;
}

.btn-secondary {
    background: transparent;
    border: 2px solid #ff7a00;
    color: #ff7a00;
}

.btn:hover {
    transform: scale(1.05);
}

/* ABOUT SECTION */
.about {
    padding: 60px 20px;
    background: #2b2b2b;
}

.about-container {
    max-width: 1100px;
    margin: auto;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 40px;
}

.about-text {
    flex: 1;
}

.about-text h2 {
    color: #ff7a00;
    font-size: 32px;
}

.about-text p {
    line-height: 1.6;
    color: #ccc;
}

.about-image {
    flex: 1;
}

.about-image img {
    width: 100%;
    border-radius: 15px;
}

/* FOOTER */
.footer {
    text-align: center;
    padding: 20px;
    background: #111;
    color: #777;
}
</style>

</head>

<body>

<!-- HERO -->
<section class="hero">
    <div class="hero-content">
        <h1>DISPOBIN!</h1>
        <p>Kualitas terbaik, yang diproduksi dengan teliti dan detail.</p>
        <div class="buttons">
            <button class="btn btn-primary">Pesan Sekarang</button>
            <button class="btn btn-secondary">Lihat Model</button>
        </div>
    </div>
</section>

<!-- ABOUT -->
<section class="about">
    <div class="about-container">
        <div class="about-text">
            <h2>Tentang Kami</h2>
            <p>
                CV. TIGA PUTRA JAYA adalah perusahaan yang bergerak di bidang produksi 
                safety boxes, hampers, dan kalender dengan kualitas terbaik.
            </p>
            <p>
                Proses produksi dilakukan secara teliti dan detail menggunakan alat cetak modern, 
                serta dikerjakan oleh tenaga profesional di ruang produksi yang terstandar.
            </p>
        </div>

        <div class="about-image">
            <img src="https://images.unsplash.com/photo-1581090700227-1e8cbb9d5a6d" alt="Produksi">
        </div>
    </div>
</section>

<!-- FOOTER -->
<div class="footer">
    © 2026 CV. TIGA PUTRA JAYA
</div>

</body>
</html>
