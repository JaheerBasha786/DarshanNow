# DarshanNow
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>DarshanNow | Spiritual Travel Platform</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Playfair Display',serif;
}

body{
background:#fff8f0;
color:#333;
}

/* HEADER */
header{
background:linear-gradient(135deg,#7a1f1f,#a83232);
padding:15px 40px;
display:flex;
justify-content:space-between;
align-items:center;
color:white;
}

.logo{
display:flex;
align-items:center;
gap:15px;
}

.logo-text{
font-size:24px;
font-weight:600;
color:#ffcc66;
letter-spacing:1px;
}

/* HERO */
.hero{
height:85vh;
background:
radial-gradient(circle at center, rgba(255,204,102,0.25) 0%, rgba(122,31,31,0.9) 60%, #5a0f0f 100%);
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:#fff8e6;
padding:20px;
position:relative;
overflow:hidden;
animation: glow 6s ease-in-out infinite;
}

.hero::before{
content:"ॐ";
position:absolute;
font-size:280px;
color:rgba(255,204,102,0.07);
top:50%;
left:50%;
transform:translate(-50%, -50%);
z-index:0;
}

@keyframes glow {
0% { filter: brightness(1); }
50% { filter: brightness(1.1); }
100% { filter: brightness(1); }
}

.hero-content{
position:relative;
z-index:2;
max-width:900px;
}

.hero h1{
font-size:38px;
margin-bottom:20px;
}

.hero p{
font-size:18px;
line-height:1.8;
}

/* SECTION */
section{
padding:60px 20px;
text-align:center;
}

.card-container{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:25px;
margin-top:30px;
}

.card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
transition:0.3s;
}

.card:hover{
transform:translateY(-5px);
}

.card h3{
color:#7a1f1f;
margin-bottom:15px;
}

button{
padding:10px;
background:linear-gradient(135deg,#ff9933,#ff4d4d);
border:none;
color:white;
font-weight:600;
border-radius:8px;
cursor:pointer;
width:100%;
margin-bottom:10px;
}

button:hover{
opacity:0.9;
}

.bus-section{
background:#fff3e6;
}

footer{
background:#5a0f0f;
color:#ffcc66;
text-align:center;
padding:25px;
}
footer a{
color:#ffcc66;
text-decoration:none;
margin:0 10px;
}
</style>
</head>

<body>

<header>
<div class="logo">
<svg width="50" height="50" viewBox="0 0 120 120">
  <circle cx="60" cy="60" r="55" fill="#7a1f1f" stroke="#ff9933" stroke-width="4"/>
  <path d="M40 80 L60 35 L80 80 Z" fill="#ffcc66"/>
  <rect x="50" y="80" width="20" height="15" fill="#ffcc66"/>
  <circle cx="60" cy="28" r="6" fill="#ff9933"/>
</svg>
<div class="logo-text">DarshanNow</div>
</div>
</header>

<section class="hero">
<div class="hero-content">
<h1>Plan Your Divine Journey Smartly</h1>
<p>
DarshanNow helps devotees plan temple visits, book travel, and arrange accommodation — all in one sacred space.
Focus on devotion. We help with the logistics.
</p>
<p style="margin-top:25px; font-style:italic; color:#ffcc66;">
"यात्रा केवल यात्रा नहीं, एक आस्था है।"
</p>
</div>
</section>

<!-- ALL PILGRIMAGE DESTINATIONS -->
<section id="temples">
<h2>Top Pilgrimage Destinations in India</h2>

<div class="card-container">

<div class="card"><h3>Tirupati Balaji</h3>
<a href="https://ttdevasthanams.ap.gov.in/home/dashboard" target="_blank"><button>Official Website</button></a>
<a href="https://www.booking.com" target="_blank"><button>Book Rooms</button></a></div>

<div class="card"><h3>Vaishno Devi</h3>
<a href="https://www.maavaishnodevi.org" target="_blank"><button>Official Website</button></a>
<a href="https://www.booking.com" target="_blank"><button>Book Rooms</button></a></div>

<div class="card"><h3>Shirdi Sai Baba</h3>
<a href="https://online.sai.org.in" target="_blank"><button>Official Website</button></a>
<a href="https://www.booking.com" target="_blank"><button>Book Rooms</button></a></div>

<div class="card"><h3>Somnath</h3>
<a href="https://somnath.org" target="_blank"><button>Official Website</button></a>
<a href="https://www.booking.com" target="_blank"><button>Book Rooms</button></a></div>

<div class="card"><h3>Kedarnath</h3>
<a href="https://badrinath-kedarnath.gov.in" target="_blank"><button>Official Website</button></a>
<a href="https://www.booking.com" target="_blank"><button>Book Rooms</button></a></div>

<div class="card"><h3>Kashi Vishwanath</h3>
<a href="https://kashivishwanath.temple" target="_blank"><button>Official Website</button></a>
<a href="https://www.booking.com" target="_blank"><button>Book Rooms</button></a></div>

<div class="card"><h3>Jagannath Puri</h3>
<a href="https://www.srikshetra.nic.in" target="_blank"><button>Official Website</button></a>
<a href="https://www.booking.com" target="_blank"><button>Book Rooms</button></a></div>

<div class="card"><h3>Meenakshi Amman</h3>
<a href="https://maduraimeenakshi.org" target="_blank"><button>Official Website</button></a>
<a href="https://www.booking.com" target="_blank"><button>Book Rooms</button></a></div>

<div class="card"><h3>Golden Temple</h3>
<a href="https://sgpc.net" target="_blank"><button>Official Website</button></a>
<a href="https://www.booking.com" target="_blank"><button>Book Rooms</button></a></div>

<div class="card"><h3>Rameshwaram</h3>
<a href="https://rameshwaramtemple.org" target="_blank"><button>Official Website</button></a>
<a href="https://www.booking.com" target="_blank"><button>Book Rooms</button></a></div>

<div class="card"><h3>Dwarkadhish Temple</h3>
<a href="https://dwarkadhish.org" target="_blank"><button>Official Website</button></a>
<a href="https://www.booking.com" target="_blank"><button>Book Rooms</button></a></div>

</div>
</section>

<!-- BUS BOOKING -->
<section id="bus" class="bus-section">
<h2>Book Bus for Your Spiritual Journey</h2>
<div class="card-container">

<div class="card">
<h3>RedBus</h3>
<a href="https://www.redbus.in" target="_blank">
<button>Go to Official Website</button>
</a>
</div>

<div class="card">
<h3>AbhiBus</h3>
<a href="https://www.abhibus.com" target="_blank">
<button>Go to Official Website</button>
</a>
</div>

</div>
</section>

<footer>
© 2026 DarshanNow | Spiritual Travel Simplified <br><br>
<a href="privacy.html">Privacy Policy</a> |
<a href="disclaimer.html">Disclaimer</a>
</footer>

</body>
</html>
