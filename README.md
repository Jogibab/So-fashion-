<!DOCTYPE html>
<html lang="te">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SK Fashion</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; padding: 20px; }
    .product { border: 1px solid #ddd; padding: 15px; margin: 15px auto; width: 300px; }
    img { max-width: 100%; }
    button { background: green; color: white; border: none; padding: 10px; cursor: pointer; }
  </style>
</head>
<body>
  <h1>👕 SK Fashion 👗</h1>
  <p>మనకి నచ్చిన బట్టను ఎంపిక చేసుకుని ఆర్డర్ పెట్టండి</p>

  <div class="product">
    <img src="https://via.placeholder.com/300x400.png?text=Cloth+Image" alt="Cloth">
    <h2>Trendy Shirt</h2>
    <p>Price: ₹499</p>
    <button onclick="order()">Order Now</button>
  </div>

  <script>
    function order() {
      alert("ధన్యవాదాలు! మీ ఆర్డర్ నమోదు అయింది ✅");
    }
  </script>
</body>
</html>
