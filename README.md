<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Katalog Produk</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI',sans-serif;
}

body{
    background:#f7f9fb;
    color:#333;
}

header{
    background:linear-gradient(135deg,#0f4c81,#00a8cc);
    color:white;
    text-align:center;
    padding:80px 20px;
}

header h1{
    font-size:2.8rem;
    margin-bottom:10px;
}

header p{
    max-width:600px;
    margin:auto;
    opacity:0.9;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}

.section-title{
    text-align:center;
    margin:60px 0 30px;
    color:#0f4c81;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
    margin-bottom:70px;
}

.card{
    background:white;
    border-radius:16px;
    overflow:hidden;
    box-shadow:0 4px 15px rgba(0,0,0,0.08);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
}

.placeholder{
    height:180px;
    background:linear-gradient(135deg,#d7eaf5,#eef6fa);
    display:flex;
    justify-content:center;
    align-items:center;
    color:#7a8b99;
    font-size:14px;
}

.content{
    padding:20px;
}

.category{
    display:inline-block;
    padding:6px 12px;
    border-radius:20px;
    font-size:12px;
    font-weight:600;
    margin-bottom:12px;
}

.agri{
    background:#e6f7ea;
    color:#2f8f46;
}

.fish{
    background:#e8f4ff;
    color:#0066cc;
}

.content p{
    font-size:14px;
    line-height:1.6;
    color:#666;
}

.btn{
    display:inline-block;
    margin-top:15px;
    padding:10px 20px;
    background:#0f4c81;
    color:white;
    text-decoration:none;
    border-radius:8px;
    font-size:14px;
}

footer{
    background:#0f4c81;
    color:white;
    text-align:center;
    padding:25px;
}
</style>
</head>
<body>

<header>
    <h1>Katalog Produk</h1>
    <p>
        Menyediakan berbagai produk unggulan sektor pertanian dan perikanan
        dengan kualitas terbaik untuk kebutuhan konsumen.
    </p>
</header>

<section class="container">
    <h2 class="section-title">Produk Unggulan</h2>

    <div class="products">

        <!-- AGRI 1 -->
        <div class="card">
            <div class="placeholder">Tambahkan Foto Produk</div>
            <div class="content">
                <span class="category agri">AGRI</span>
                <p>Produk pertanian berkualitas dengan proses pengolahan yang baik dan siap dipasarkan.</p>
                <a href="#" class="btn">Detail</a>
            </div>
        </div>

        <!-- AGRI 2 -->
        <div class="card">
            <div class="placeholder">Tambahkan Foto Produk</div>
            <div class="content">
                <span class="category agri">AGRI</span>
                <p>Produk hasil pertanian pilihan dengan mutu yang terjaga dan nilai ekonomi tinggi.</p>
                <a href="#" class="btn">Detail</a>
            </div>
        </div>

        <!-- PERIKANAN 1 -->
        <div class="card">
            <div class="placeholder">Tambahkan Foto Produk</div>
            <div class="content">
                <span class="category fish">PERIKANAN</span>
                <p>Produk perikanan berkualitas yang diproses secara higienis dan memenuhi standar mutu.</p>
                <a href="#" class="btn">Detail</a>
            </div>
        </div>

        <!-- PERIKANAN 2 -->
        <div class="card">
            <div class="placeholder">Tambahkan Foto Produk</div>
            <div class="content">
                <span class="category fish">PERIKANAN</span>
                <p>Produk perikanan dengan cita rasa khas dan bahan baku pilihan.</p>
                <a href="#" class="btn">Detail</a>
            </div>
        </div>

        <!-- PERIKANAN 3 -->
        <div class="card">
            <div class="placeholder">Tambahkan Foto Produk</div>
            <div class="content">
                <span class="category fish">PERIKANAN</span>
                <p>Produk olahan perikanan yang cocok untuk berbagai kebutuhan pasar modern.</p>
                <a href="#" class="btn">Detail</a>
            </div>
        </div>

        <!-- PERIKANAN 4 -->
        <div class="card">
            <div class="placeholder">Tambahkan Foto Produk</div>
            <div class="content">
                <span class="category fish">PERIKANAN</span>
                <p>Produk perikanan bernilai tambah dengan kualitas yang konsisten.</p>
                <a href="#" class="btn">Detail</a>
            </div>
        </div>

        <!-- PERIKANAN 5 -->
        <div class="card">
            <div class="placeholder">Tambahkan Foto Produk</div>
            <div class="content">
                <span class="category fish">PERIKANAN</span>
                <p>Produk perikanan unggulan yang siap dipromosikan untuk pasar lokal maupun nasional.</p>
                <a href="#" class="btn">Detail</a>
            </div>
        </div>

    </div>
</section>

<footer>
    © 2026 Katalog Produk Agri & Perikanan
</footer>

</body>
</html>
