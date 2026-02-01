index.html<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Andruejel Perfume | Official Store</title>
  <style>
    body {font-family: Arial, sans-serif; margin:0; background:#f7f7f7; color:#333;}
    header {background:#000; color:#fff; padding:20px; text-align:center;}
    section {padding:30px; max-width:1100px; margin:auto;}
    .product {background:#fff; padding:20px; border-radius:10px; box-shadow:0 2px 8px rgba(0,0,0,0.1); display:grid; grid-template-columns:1fr 1fr; gap:20px;}
    .product img {width:100%; border-radius:10px;}
    .btn {display:inline-block; background:#000; color:#fff; padding:12px 20px; text-decoration:none; border-radius:6px; margin-top:10px;}
    .features {display:grid; grid-template-columns:repeat(auto-fit,minmax(200px,1fr)); gap:15px; margin-top:20px;}
    .feature {background:#fff; padding:15px; border-radius:8px; text-align:center;}
    footer {background:#111; color:#ccc; text-align:center; padding:15px; margin-top:30px;}
    @media(max-width:768px){.product{grid-template-columns:1fr;}}
  </style>
</head>
<body>

<header>
  <h1>ANDRUEJEL</h1>
  <p>Luxury Perfume for Confident Souls</p>
</header>

<section>
  <div class="product">
    <img src="https://via.placeholder.com/500x500?text=Andruejel+Perfume" alt="Andruejel Perfume">
    <div>
      <h2>Andruejel Premium Perfume</h2>
      <p>Andruejel ek premium fragrance hai jo aapki personality ko strong aur attractive banata hai. Long‑lasting smell jo din bhar fresh rakhe.</p>
      <h3>Price: ₹1299 <small>(Single Piece)</small></h3>
      <a href="#order" class="btn">Order Now</a>
    </div>
  </div>
</section>

<section>
  <h2>Why Choose Andruejel?</h2>
  <div class="features">
    <div class="feature">Long Lasting Fragrance</div>
    <div class="feature">Premium Quality</div>
    <div class="feature">Perfect for Daily & Party Use</div>
    <div class="feature">Cash on Delivery Available</div>
  </div>
</section>

<section id="order">
  <h2>Place Your Order</h2>
  <p>Niche form bharein. Order Cash on Delivery (COD) par deliver kiya jayega.</p>
  <form style="background:#fff;padding:20px;border-radius:10px;max-width:500px;" onsubmit="event.preventDefault(); alert('Order received! Ham jald hi aapse contact karenge.');">
    <label>Full Name</label><br>
    <input type="text" required style="width:100%;padding:10px;margin:8px 0;"><br>
    <label>Mobile Number</label><br>
    <input type="tel" required style="width:100%;padding:10px;margin:8px 0;"><br>
    <label>Full Address</label><br>
    <textarea required style="width:100%;padding:10px;margin:8px 0;"></textarea><br>
    <button class="btn" type="submit">Confirm Order (₹1299 COD)</button>
  </form>
</section>

<footer>
  <p>© 2026 Andruejel Perfume. All Rights Reserved.</p>
</footer>

</body>
</html>
