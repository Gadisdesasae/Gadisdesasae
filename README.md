<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PT Gadis Desa Ae - Ekspor Pertanian dan Perikanan</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- Header -->
<header class="bg-primary text-white text-center py-5">
    <h1>PT Gadis Desa Ae</h1>
    <p>Solusi Ekspor Pertanian, Perikanan, dan Produk UKM</p>
</header>

<!-- Navigation -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
        <a class="navbar-brand" href="#">PT Gadis Desa Ae</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item"><a class="nav-link" href="#services">Layanan</a></li>
                <li class="nav-item"><a class="nav-link" href="#products">Katalog Produk</a></li>
                <li class="nav-item"><a class="nav-link" href="#about">Tentang Kami</a></li>
                <li class="nav-item"><a class="nav-link" href="#contact">Kontak</a></li>
            </ul>
        </div>
    </div>
</nav>

<!-- Hero Section -->
<section class="hero bg-light text-center py-5">
    <div class="container">
        <h2 class="text-primary">Bersama Membawa Hasil Pertanian dan Perikanan ke Pasar Dunia</h2>
        <p class="lead">Kami mendukung petani dan UKM lokal untuk menembus pasar ekspor dengan layanan profesional dan terpercaya.</p>
    </div>
</section>

<!-- Services Section -->
<section id="services" class="py-5">
    <div class="container">
        <h3 class="text-center mb-4">Layanan Ekspor Kami</h3>
        <div class="row">
            <div class="col-md-4">
                <h5>Konsultasi Ekspor</h5>
                <p>Memberikan panduan bagi petani dan pelaku UKM dalam menyiapkan produk untuk pasar internasional.</p>
            </div>
            <div class="col-md-4">
                <h5>Pengurusan Dokumen</h5>
                <p>Membantu pengurusan dokumen dan perizinan ekspor dengan prosedur yang mudah dan cepat.</p>
            </div>
            <div class="col-md-4">
                <h5>Logistik dan Pengiriman</h5>
                <p>Menyediakan solusi pengiriman produk dengan jaminan keamanan dan kecepatan.</p>
            </div>
        </div>
    </div>
</section>

<!-- Products Section -->
<section id="products" class="py-5 bg-light">
    <div class="container">
        <h3 class="text-center mb-4">Katalog Produk</h3>
        <div class="row">
            <!-- Contoh produk -->
            <div class="col-md-4">
                <div class="card mb-4">
                    <img src="images/product1.jpg" class="card-img-top" alt="Produk 1">
                    <div class="card-body">
                        <h5 class="card-title">Jagung Pipil</h5>
                        <p class="card-text">Jagung pipil kualitas terbaik siap ekspor.</p>
                    </div>
                </div>
            </div>
            <!-- Tambahkan lebih banyak produk di sini -->
        </div>
    </div>
</section>

<!-- About Section -->
<section id="about" class="py-5">
    <div class="container">
        <h3 class="text-center mb-4">Tentang Kami</h3>
        <p class="text-center">PT Gadis Desa Ae berkomitmen untuk meningkatkan nilai produk lokal dan memperkenalkan produk petani dan pelaku UKM ke pasar internasional dengan layanan ekspor yang andal.</p>
    </div>
</section>

<!-- Contact Section -->
<section id="contact" class="py-5 bg-light">
    <div class="container">
        <h3 class="text-center mb-4">Kontak Kami</h3>
        <form>
            <div class="form-group">
                <label for="name">Nama</label>
                <input type="text" class="form-control" id="name" placeholder="Nama Anda">
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" class="form-control" id="email" placeholder="Email Anda">
            </div>
            <div class="form-group">
                <label for="message">Pesan</label>
                <textarea class="form-control" id="message" rows="3" placeholder="Pesan Anda"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Kirim</button>
        </form>
    </div>
</section>

<!-- Footer -->
<footer class="text-center py-4 bg-dark text-white">
    <p>&copy; 2024 PT Gadis Desa Ae. Semua Hak Dilindungi.</p>
</footer>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
/* style.css */
body {
    font-family: Arial, sans-serif;
}

.hero {
    background-image: url('images/hero-background.jpg'); /* Sesuaikan dengan gambar latar */
    background-size: cover;
    color: white;
    padding: 100px 0;
}

.card img {
    height: 200px;
    object-fit: cover;
}

footer {
    font-size: 0.9rem;
}
