<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pudding Store</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="css/bootstrap.css">
    <style>
        
        /* Gaya tema hitam */
        *,
    html {
    margin: 0;
    padding: 0;
}

        
        body {
            background-color: white;
            background-image: url(wallpaperflare.com_wallpaper\ \(1\).jpg);
            background-position: 100%;
            backdrop-filter: blur(4px);
        }
        /* Reset default margin and padding for the list and list items */
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

/* Style the navigation bar */
nav {
    background-color: #333;
}

/* Style the list items in the navigation bar */
nav ul {
    display: flex;
    justify-content: space-around;
    padding: 10px 0;
}

nav li {
    margin: 0 10px;
}

/* Style the links in the navigation bar */
nav a {
    text-decoration: none;
    color: white;
    font-weight: bold;
}

/* Add hover effect to the links */
nav a:hover {
    color: yellow;
}

        /* Gaya untuk header */
        .header {
            background-color: #000;
            padding: 20px;
            text-align: center;
        }
        /* Gaya untuk konten */
        .content {
            padding: 20px;
        }
        /* Gaya untuk footer */
        .footer {
            background-color: #000;
            padding: 40px;
            text-align: center;
        }
        /* Pilih elemen dengan ID "teks-hover" */
teks-hover:hover {
  color: red; /* Mengubah warna teks menjadi merah saat dihover */
}

        /* baru */
        @keyframes neon-glow {
    0% {
        text-shadow: 0 0 10px #800080, 0 0 20px #800080, 0 0 30px #800080, 0 0 40px #ff00ff, 0 0 70px #ff00ff, 0 0 80px #ff00ff, 0 0 100px #ff00ff, 0 0 150px #ff00ff;
    }
    100% {
        text-shadow: 0 0 20px #800080, 0 0 30px #800080, 0 0 40px #ff00ff, 0 0 70px #ff00ff, 0 0 80px #ff00ff, 0 0 100px #ff00ff, 0 0 150px #ff00ff, 0 0 200px #ff00ff;
    }
}

.neon-text {
    font-size: 48px;
    color: #800080; /* Warna ungu */
    text-align: center;
    text-transform: uppercase;
    font-family: 'Arial', sans-serif;
    letter-spacing: 2px;
    animation: neon-glow 1s ease-in-out infinite alternate;
}


        /* baru */

        @keyframes neon-glow {
    0% {
        text-shadow: 0 0 10px #FF0000, 0 0 20px #FF0000, 0 0 30px #FF0000, 0 0 40px #FF00FF, 0 0 70px #FF00FF, 0 0 80px #FF00FF, 0 0 100px #FF00FF, 0 0 150px #FF00FF;
    }
    100% {
        text-shadow: 0 0 20px #FF0000, 0 0 30px #FF0000, 0 0 40px #FF00FF, 0 0 70px #FF00FF, 0 0 80px #FF00FF, 0 0 100px #FF00FF, 0 0 150px #FF00FF, 0 0 200px #FF00FF;
    }
}

.neon-text {
    font-size: 48px;
    color: #FF0000; /* Warna merah */
    text-align: center;
    text-transform: uppercase;
    font-family: 'Arial', sans-serif;
    letter-spacing: 2px;
    animation: neon-glow 1s ease-in-out infinite alternate;
}

        
        /* Gaya teks neon */
        .neon-text {
            font-size: 30px;
            color: #fff;
            text-align: center;
            text-transform: uppercase;
            font-family: 'Arial', sans-serif;
            letter-spacing: 2px;
            animation: neon-glow 5s ease-in-out infinite alternate;
        }
        
        @keyframes neon-glow {
            0% {
                text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #fff, 0 0 40px #ff00ff, 0 0 70px #ff00ff, 0 0 80px #ff00ff, 0 0 100px #ff00ff, 0 0 150px #ff00ff;
            }
            100% {
                text-shadow: 0 0 20px #fff, 0 0 30px #fff, 0 0 40px #ff00ff, 0 0 70px #ff00ff, 0 0 80px #ff00ff, 0 0 100px #ff00ff, 0 0 150px #ff00ff, 0 0 200px #ff00ff;
            }
        }
        
        .card {
            background-color: #000;
            color: #fff;
        }
    </style>
</head>
<body>
<!-- navbar -->
<nav>
    <ul>
        <li><a href="#">Beranda</a></li>
        <li><a href="#">Tentang Kami</a></li>
        <li><a href="#">Kontak</a></li>
    </ul>
</nav>

<!-- navbarend -->
<br>
<br>
<div class="neon-text">
    <h1 class="text-capitalize">Welcome to the reyna ult dessert</h1>
    <p>Delicious dessert Await You!</p>
</div>
<BR>

<div class="neon-text">
    Try Our Signature Dessert And Ice
</div>
<BR>
    <br>
<div class="content container">
    <div class="row">
        <div class="col-md-4">
            <div class="teks-hover">
            <div class="card">
                <img src="images (2).jpg" class="card-img-top" alt="Pudding 1">
                <div class="card-body">
                    <h5 class="card-title">Chocolate Pudding</h5>
                    <p class="card-text">Creamy and rich chocolate pudding.</p>
                    <a href="#" class="btn btn-primary">Buy Now</a>
                </div>
            </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card">
                <img src="images (1).jpg" class="card-img-top" alt="Pudding 2">
                <div class="card-body">
                    <h5 class="card-title">Vanilla Pudding</h5>
                    <p class="card-text">Smooth and creamy vanilla pudding.</p>
                    <a href="#" class="btn btn-primary">Buy Now</a>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card">
                <img src="images (1).jpg" class="card-img-top" alt="Pudding 3">
                <div class="card-body">
                    <h5 class="card-title">caramel Pudding</h5>
                    <p class="card-text">Fresh and fruity caramel pudding.</p>
                    <a href="#" class="btn btn-primary">Buy Now</a>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="footer">
    <p>&copy; 2023 Pudding Store</p>
</div>

</body>
</html>
