<!DOCTYPE html>
<html>
<body>
<head>
  <title>Adventure Travel </title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" type="text/css" href="kallesh.css">
  <style>body {
    background-image: url("https://th.bing.com/th/id/OIP.KD0O1anrRNqb3FZuf95kBwHaEo?w=300&h=187&c=7&r=0&o=5&dpr=1.1&pid=1.7");
    background-repeat: no-repeat;
    background-size: cover;
  } * {
    box-sizing: border-box;
  }

  body {
    margin: 0;
    font-family: Arial, sans-serif;
  }

  header {
    background-color: #333;
    padding: 10px;
    color: #fff;
    text-align: center;
    position: relative;
  }

  header h1 {
    margin: 0;
  }

  .profile-logo {
    position: absolute;
    top: 10px;
    right: 10px;
    color: #fff;
    font-size: 24px;
  }
 
  

  .search-bar {
    text-align: right;
    margin-top: 15px;
    position: absolute; 
    left:20%;
    top:25%;
    width:30%;
    
  }

  .search-bar input[type="text"] {
    padding: 10px;
    width: 300px;
    border: none;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  }

  .search-bar button {
    padding: 10px 20px;
    background-color: #333;
    color: #fff;
    border: none;
    border-radius: 5px;
    margin-left: 10px;
  }

  nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
  }

  nav ul li {
    float: left;
  }

  nav ul li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }

  nav ul li a:hover {
    background-color: #111;
  }

  .hero {
    background-image: url("hero.jpg");
    background-size: cover;
    background-position: center;
    height: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: #fff;
  }

  .hero h1 {
    font-size: 48px;
    margin: 0;
  }

  .btn {
    display: inline-block;
    background-color: #333;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    margin-top: 20px;
    font-size: 18px;
    border-radius: 5px;
  }

  .btn:hover {
    background-color: #111;
  }

  .features {
     background-image: url("https://images8.alphacoders.com/690/690881.jpg");
    padding: 40px 0;
    text-align: center;
  }

  .features h2 {
    margin: 0;
  }

  .feature {
    display: inline-block;
    vertical-align: top;
    margin: 0 20px;
    padding: 20px;
    background-color:#F4C2C2;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    width: 300px;
  }

  .feature i {
    font-size: 48px;
    margin-bottom: 10px;
  }

  .feature h3 {
    font-size: 24px;
    margin: 0;
  }

  .feature p {
    color: #888;
  }

  .destinations {
    padding: 40px 0;
    text-align: center;
  }

  .destinations h2 {
    margin: 0;
  }

  .destination {
    display: inline-block;
    vertical-align: top;
    margin: 0 20px;
    width: 300px;
  }

  .destination img {
    width: 100%;
    border-radius: 5px;
    margin-bottom: 10px;
  }

  .destination h3 {
    margin: 0;
  }

  .destination p {
    color: #888;
  }

  .offers {
    background-color: #FF7276;
    padding: 40px 0;
    text-align: center;
  }

  .offers h2 {
    margin: 0;
  }

  .offer {
    display: inline-block;
    vertical-align: top;
    margin: 0 20px;
    padding: 20px;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    width: 300px;
  }

  .offer img {
    width: 100%;
    border-radius: 5px;
    margin-bottom: 10px;
  }

  .offer h3 {
    margin: 0;
  }

  .offer p {
    color: #131212;
  }

  .tours {
    padding: 40px 0;
    text-align: center;
  }

  .tours h2 {
    margin: 0;
  }

  .tour {
    display: inline-block;
    vertical-align: top;
    margin: 0 20px;
    width: 300px;
  }

  .tour img {
    width: 100%;
    border-radius: 5px;
    margin-bottom: 10px;
  }

  .tour h3 {
    margin: 0;
    
  }

  .tour p {
    color: #070707;
  }

  .follow-us {
    background-color: #333;
    padding: 40px 0;
    text-align: center;
  }

  .follow-us h2 {
    color: #fff;
    margin: 0;
  }

  .social-icons a {
    color: #fff;
    font-size: 24px;
    margin: 0 10px;
  }

  .get-started {
    text-align: center;
    padding: 40px 0;
  }

  .get-started h2 {
    margin: 0;
  }

  .get-started p {
    color: #060505;
  }

  footer {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
  }</style>
  
    <h1>Adventure Travel</h1>
   <header>
    <div class="profile-logo">
      <i class="fa fa-user-circle"></i>
    </div> <div class="search-bar">
        <input type="text" placeholder="Search...">
        <button><i class="fa fa-search"></i></button>
      </div>
  </header>
<nav>
    <ul>
      <li><a href="#"><i class="fa fa-home"></i></a></li>
      <li><a href="#"><i class="fa fa-plane"></i></a></li>
      <li><a href="#"><i class="fa fa-map-marker"></i></a></li>
      <li><a href="#"><i class="fa fa-envelope"></i></a></li>
    </ul>
  </nav>
<div class="features">
    <h2>Our Features</h2>
<h2>ㅤ</h2>
    <div class="feature">
      <i class="fa fa-map-marker"></i>
      <h3>Explore Destinations</h3>
      
    </div>
    <div class="feature">
      <i class="fa fa-heart"></i>
      <h3>Make Memories</h3>
      
    </div>
    <div class="feature">
      <i class="fa fa-briefcase"></i>
      <h3>Great Deals</h3>
     
    </div>
  </div>

  <div class="destinations">
    <h2>Popular Destinations</h2>
<h2>ㅤ</h2>
    <div class="destination">
      <img src="https://i.pinimg.com/236x/3e/46/c1/3e46c1679dbf6dcdcfad94f7318f0756.jpg">
      <h3>Destination 1</h3>
      <p>"𝑫𝒊𝒔𝒄𝒐𝒗𝒆𝒓 𝒕𝒉𝒆 𝒉𝒊𝒅𝒅𝒆𝒏 𝒕𝒓𝒆𝒂𝒔𝒖𝒓𝒆𝒔 𝒐𝒇 𝑲𝒆𝒓𝒂𝒍𝒂, 𝒘𝒉𝒆𝒓𝒆 𝒆𝒗𝒆𝒓𝒚 𝒔𝒕𝒆𝒑 𝒊𝒔 𝒂 𝒋𝒐𝒖𝒓𝒏𝒆𝒚 𝒕𝒐 𝒑𝒂𝒓𝒂𝒅𝒊𝒔𝒆".</p>
    </div>
    <div class="destination">
      <img src="https://i.pinimg.com/564x/40/56/61/40566104a5c695063ac6e204c0f5a9d9.jpg">
      <h3>Destination 2</h3>
      <p>"𝑫𝒊𝒔𝒄𝒐𝒗𝒆𝒓 𝒕𝒉𝒆 𝒎𝒂𝒈𝒊𝒄 𝒐𝒇 𝑮𝒐𝒂, 𝒘𝒉𝒆𝒓𝒆 𝒓𝒆𝒍𝒂𝒙𝒂𝒕𝒊𝒐𝒏 𝒎𝒆𝒆𝒕𝒔 𝒂𝒅𝒗𝒆𝒏𝒕𝒖𝒓𝒆 𝒊𝒏 𝒑𝒆𝒓𝒇𝒆𝒄𝒕 𝒉𝒂𝒓𝒎𝒐𝒏𝒚."</p>
    </div>
    <div class="destination">
      <img src="https://i.pinimg.com/564x/22/d5/9a/22d59a0450b61c703e56a3768ff7a4cf.jpg">
      <h3>Destination 3</h3>
      <p>"𝑼𝒏𝒄𝒐𝒗𝒆𝒓 𝒕𝒉𝒆 𝒔𝒆𝒄𝒓𝒆𝒕𝒔 𝒐𝒇 𝑯𝒂𝒎𝒑𝒊, 𝒘𝒉𝒆𝒓𝒆 𝒉𝒊𝒔𝒕𝒐𝒓𝒚, 𝒔𝒑𝒊𝒓𝒊𝒕𝒖𝒂𝒍𝒊𝒕𝒚, 𝒂𝒏𝒅 𝒃𝒓𝒆𝒂𝒕𝒉𝒕𝒂𝒌𝒊𝒏𝒈 𝒍𝒂𝒏𝒅𝒔𝒄𝒂𝒑𝒆𝒔 𝒄𝒐𝒏𝒗𝒆𝒓𝒈𝒆 𝒕𝒐 𝒄𝒓𝒆𝒂𝒕𝒆 𝒂𝒏 𝒖𝒏𝒇𝒐𝒓𝒈𝒆𝒕𝒕𝒂𝒃𝒍𝒆 𝒕𝒓𝒂𝒗𝒆𝒍 𝒆𝒙𝒑𝒆𝒓𝒊𝒆𝒏𝒄𝒆."</p>
    </div>
  </div>

  <div class="offers">
    <h2>Special Offers</h2>
<h2> ㅤ</h2>
    <div class="offer">
      <img src="https://s-media-cache-ak0.pinimg.com/736x/8c/df/8e/8cdf8ebd244550515825842212edb881.jpg">
      <h3>Offer 1</h3>
      <p>"𝑫𝒊𝒔𝒄𝒐𝒗𝒆𝒓 𝒕𝒉𝒆 𝒑𝒂𝒓𝒂𝒅𝒊𝒔𝒆 𝒐𝒏 𝑬𝒂𝒓𝒕𝒉, 𝒘𝒉𝒆𝒓𝒆 𝒃𝒓𝒆𝒂𝒕𝒉𝒕𝒂𝒌𝒊𝒏𝒈 𝒃𝒆𝒂𝒖𝒕𝒚 𝒎𝒆𝒆𝒕𝒔 𝒕𝒊𝒎𝒆𝒍𝒆𝒔𝒔 𝒔𝒆𝒓𝒆𝒏𝒊𝒕𝒚".</p>
    </div>
    <div class="offer">
      <img src="https://media.istockphoto.com/id/1053122294/vector/kathmandu-nepal-city-skyline-silhouette.jpg?s=612x612&w=0&k=20&c=5ek48SURH0sirl1x2vggrpYz-8ZRNyxrsOBU3aqLF58=">
      <h3>Offer 2</h3>
      <p>"𝑻𝒉𝒓𝒊𝒍𝒍 𝒊𝒏 𝒕𝒓𝒆𝒌𝒌𝒊𝒏𝒈 𝑵𝒆𝒑𝒂𝒍'𝒔 𝒃𝒓𝒆𝒂𝒕𝒉𝒕𝒂𝒌𝒊𝒏𝒈 𝑯𝒊𝒎𝒂𝒍𝒂𝒚𝒂𝒔, 𝒘𝒊𝒕𝒏𝒆𝒔𝒔 𝒏𝒂𝒕𝒖𝒓𝒆'𝒔 𝒂𝒘𝒆-𝒊𝒏𝒔𝒑𝒊𝒓𝒊𝒏𝒈 𝒔𝒑𝒆𝒄𝒕𝒂𝒄𝒍𝒆."</p>
    </div>
    <div class="offer">
      <img src="https://cdn1.tripoto.com/media/filter/tst/img/747480/Image/1585825644_ooty.jpg">
      <h3>Offer 3</h3>
      <p>"𝑳𝒆𝒕 𝒕𝒉𝒆 𝒄𝒐𝒐𝒍 𝒃𝒓𝒆𝒆𝒛𝒆 𝒐𝒇 𝑶𝒐𝒕𝒚 𝒓𝒆𝒋𝒖𝒗𝒆𝒏𝒂𝒕𝒆 𝒚𝒐𝒖𝒓 𝒔𝒑𝒊𝒓𝒊𝒕 𝒂𝒏𝒅 𝒂𝒘𝒂𝒌𝒆𝒏 𝒚𝒐𝒖𝒓 𝒔𝒆𝒏𝒔𝒆𝒔."</p>
    </div>
  </div>

  <div class="tours">
    <h2>Featured Tours</h2>
<h2>ㅤ</h2>
    <div class="tour">
      <img src="https://i.pinimg.com/736x/e2/c7/97/e2c797e9693fdabfd63d92c3a7348cb6.jpg">
      <h3>Tour 1</h3>
      <p>"𝑰𝒎𝒎𝒆𝒓𝒔𝒆 𝒚𝒐𝒖𝒓𝒔𝒆𝒍𝒇 𝒊𝒏 𝑻𝒉𝒂𝒊𝒍𝒂𝒏𝒅'𝒔 𝒎𝒂𝒈𝒊𝒄, 𝒘𝒉𝒆𝒓𝒆 𝒂𝒏𝒄𝒊𝒆𝒏𝒕 𝒕𝒓𝒂𝒅𝒊𝒕𝒊𝒐𝒏𝒔 𝒃𝒍𝒆𝒏𝒅 𝒔𝒆𝒂𝒎𝒍𝒆𝒔𝒔𝒍𝒚 𝒘𝒊𝒕𝒉 𝒎𝒐𝒅𝒆𝒓𝒏 𝒘𝒐𝒏𝒅𝒆𝒓𝒔."</p>
    </div>
<div>

<div/>ㅤ
    <div class="tour">
      <img src="https://thumbs.dreamstime.com/z/japan-travel-infographic-vector-places-landmarks-87496337.jpg">
      <h3>Tour 2</h3>
      <p>"𝑫𝒆𝒍𝒗𝒆 𝒊𝒏𝒕𝒐 𝑱𝒂𝒑𝒂𝒏'𝒔 𝒄𝒖𝒍𝒕𝒖𝒓𝒂𝒍 𝒘𝒐𝒏𝒅𝒆𝒓𝒔, 𝒇𝒓𝒐𝒎 𝒗𝒊𝒃𝒓𝒂𝒏𝒕 𝒄𝒊𝒕𝒊𝒆𝒔 𝒕𝒐 𝒔𝒆𝒓𝒆𝒏𝒆 𝒄𝒐𝒖𝒏𝒕𝒓𝒚𝒔𝒊𝒅𝒆."</p>
    </div>
    <div class="tour">
      <img src="https://i.pinimg.com/564x/8b/c4/0a/8bc40affd23c0d015f7be48db0b9e302.jpg">
      <h3>Tour 3</h3>
      <p>"𝒘𝒉𝒆𝒓𝒆 𝒕𝒉𝒆 𝒑𝒂𝒔𝒕 𝒂𝒏𝒅 𝒇𝒖𝒕𝒖𝒓𝒆 𝒄𝒐𝒍𝒍𝒊𝒅𝒆 𝒊𝒏 𝒂 𝒅𝒂𝒛𝒛𝒍𝒊𝒏𝒈 𝒅𝒊𝒔𝒑𝒍𝒂𝒚 𝒐𝒇 𝒄𝒖𝒍𝒕𝒖𝒓𝒆 𝒂𝒏𝒅 𝒊𝒏𝒏𝒐𝒗𝒂𝒕𝒊𝒐𝒏. 𝑳𝒆𝒕 𝒊𝒕 𝒊𝒏𝒔𝒑𝒊𝒓𝒆 𝒚𝒐𝒖."</p>
    </div>
  </div>
  <div class="get-started">
    <h2>Get Started</h2>
    <p>start your journey with us</p>
    <a href="#" class="btn">Sign in</a>
 <a href="#" class="btn">Sign Up Now</a>
  </div>
<div class="follow-us">
    <h2>Follow Us</h2>
    <div class="social-icons">
      <a href="#"><i class="fa fa-facebook"></i></a>
      <a href="#"><i class="fa fa-twitter"></i></a>
      <a href="#"><i class="fa fa-instagram"></i></a>
      <a href="#"><i class="fa fa-youtube"></i></a>
    </div>
  </div>
  <footer>
    <p>&copy; 2023 Adventure Travel. All rights reserved.</p>
  </footer>
