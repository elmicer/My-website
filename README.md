# My-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Shop for clothes and electronics at LuluHub555. Contact us for inquiries or support.">
  <meta name="keywords" content="LuluHub555, clothes, electronics, shopping, contact, WhatsApp">
  <meta name="author" content="LuluHub555 Team">
  <!-- Open Graph Tags for Social Media -->
  <meta property="og:title" content="LuluHub555 - Clothes & Electronics">
  <meta property="og:description" content="Shop for clothes and electronics at LuluHub555. Contact us for inquiries or support.">
  <meta property="og:image" content="luluhub-logo.jpg">
  <meta property="og:url" content="https://www.luluhub555.com">
  <title>LuluHub555 - Clothes & Electronics</title>
  <link rel="icon" href="luluhub-logo.jpg" type="image/jpg">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background-color: #FEFAE0;
    }

    header {
      background-color: #283618;
      color: white;
      padding: 10px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    .logo {
      width: 100px;
      height: auto;
    }

    .search-bar {
      flex-grow: 1;
      margin: 0 20px;
      display: flex;
    }

    .search-bar input {
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 4px 0 0 4px;
      background-color: #FDFAE5;
    }

    .search-bar button {
      padding: 10px;
      background-color: #283618;
      color: white;
      border: none;
      border-radius: 0 4px 4px 0;
      cursor: pointer;
    }

    .search-bar button:hover {
      background-color: #3C4F23;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 14px;
    }

    nav ul li a:hover {
      color: #DDA15E;
    }

    .cart {
      color: white;
      font-size: 16px;
    }

    .cart span {
      margin-left: 5px;
    }

    main {
      max-width: 1200px;
      margin: 20px auto;
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }

    .sidebar {
      width: 200px;
      background-color: #FDFAE5;
      padding: 20px;
      border-radius: 4px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    .sidebar h3 {
      margin-bottom: 10px;
      color: #283618;
    }

    .sidebar label {
      display: block;
      margin: 10px 0;
      font-size: 14px;
      color: #606C38;
    }

    .sidebar input[type="text"] {
      width: 100%;
      padding: 8px;
      border: 1px solid #ddd;
      border-radius: 4px;
      background-color: #FEFAE0;
      color: #606C38;
    }

    .content {
      flex-grow: 1;
      background-color: #FDFAE5;
      padding: 20px;
      border-radius: 4px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    .section {
      margin-bottom: 40px;
    }

    .section h2 {
      font-size: 24px;
      margin-bottom: 20px;
      color: #283618;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 20px;
    }

    .product-card {
      background-color: #FEFAE0;
      border: 1px solid #ddd;
      border-radius: 4px;
      padding: 10px;
      text-align: center;
      transition: transform 0.2s;
    }

    .product-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    .product-card img {
      max-width: 100%;
      height: auto;
      margin-bottom: 10px;
    }

    .product-card h3 {
      font-size: 16px;
      margin-bottom: 10px;
      color: #606C38;
    }

    .product-card p {
      color: #283618;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .product-card button {
      background-color: #DDA15E;
      border: none;
      padding: 8px;
      width: 100%;
      border-radius: 4px;
      cursor: pointer;
      font-size: 14px;
      color: #283618;
    }

    .product-card button:hover {
      background-color: #BC8A4E;
    }

    footer {
      background-color: #283618;
      color: white;
      padding: 20px;
      text-align: center;
      margin-top: 20px;
    }

    footer a {
      color: #FEFAE0;
      text-decoration: none;
    }

    footer a:hover {
      color: #DDA15E;
    }

    footer p {
      margin: 5px 0;
    }

    @media (max-width: 768px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }

      .search-bar {
        margin: 10px 0;
        width: 100%;
      }

      nav ul {
        flex-direction: column;
        gap: 10px;
      }

      main {
        flex-direction: column;
      }

      .sidebar {
        width: 100%;
      }

      .product-grid {
        grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="luluhub-logo.jpg" alt="LuluHub Logo" class="logo">
    <div class="search-bar">
      <input type="text" placeholder="Search LuluHub555" aria-label="Search products">
      <button type="submit">🔍</button>
    </div>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="#clothes">Clothes</a></li>
        <li><a href="#electronics">Electronics</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <div class="cart">
      <a href="#cart" aria-label="View cart">
        <span>🛒</span> <span id="cart-count">0</span> items
      </a>
    </div>
  </header>

  <main>
    <aside class="sidebar">
      <h3>Filters</h3>
      <label for="price-filter">Price ($):</label>
      <input type="text" id="price-filter" name="price" placeholder="e.g., 20-100" aria-label="Enter price or range">
    </aside>

    <div class="content">
      <section id="clothes" class="section">
        <h2>Clothes</h2>
        <div class="product-grid">
          <div class="product-card">
            <img src="mens-pjp.jpg" alt="Men's Shirt" loading="lazy">
            <h3>Men's Casual Shirt</h3>
            <p>Tsh/15000</p>
            <button onclick="addToCart('Men\'s Casual Shirt',Tsh/15000)">Add to Cart</button>
          </div>
          <div class="product-card">
            <img src="jeans.jpg" alt="Women's Jeans" loading="lazy">
            <h3>Women's Jeans</h3>
            <p>Tsh/45000</p>
            <button onclick="addToCart('Women\'s Jeans',Tsh/45000)">Add to Cart</button>
          </div>
          <div class="product-card">
            <img src="jacket.jpg" alt="Unisex Jacket" loading="lazy">
            <h3>Unisex Jacket</h3>
            <p>Tsh/30000</p>
            <button onclick="addToCart('Unisex Jacket',Tsh/30000)">Add to Cart</button>
          </div>
          <div class="product-card">
            <img src="dress.jpg" alt="Summer Dress" loading="lazy">
            <h3>Summer Dress</h3>
            <p>Tsh/20000</p>
            <button onclick="addToCart('Summer Dress',Tsh/20000)">Add to Cart</button>
          </div>
        </div>
      </section>

      <section id="electronics" class="section">
        <h2>Electronics</h2>
        <div class="product-grid">
          <div class="product-card">
            <img src="headphone.jpg" alt="Wireless Headphones" loading="lazy">
            <h3>Wireless Headphones</h3>
            <p>Tsh/80000</p>
            <button onclick="addToCart('Wireless Headphones',Tsh/80000)">Add to Cart</button>
          </div>
          <div class="product-card">
            <img src="whatch.jpg" alt="Smartwatch" loading="lazy">
            <h3>Smartwatch</h3>
            <p>Tsh/150000</p>
            <button onclick="addToCart('Smartwatch',Tsh/150000)">Add to Cart</button>
          </div>
          <div class="product-card">
            <img src="speaker.jpg" alt="Bluetooth Speaker" loading="lazy">
            <h3>Bluetooth Speaker</h3>
            <p>Tsh/20000</p>
            <button onclick="addToCart('Bluetooth Speaker',Tsh/20000)">Add to Cart</button>
          </div>
          <div class="product-card">
            <img src="ipad.jpg" alt="Tablet" loading="lazy">
            <h3>10-Inch Tablet</h3>
            <p>Tsh/1500000</p>
            <button onclick="addToCart('10-Inch Tablet',Tsh/1500000)">Add to Cart</button>
          </div>
        </div>
      </section>
    </div>
  </main>

  <footer id="contact">
    <p>Contact us: <a href="https://wa.me/+992077306252" target="_blank" rel="noopener">WhatsApp</a></p>
    <p>© 2025 LuluHub555. All rights reserved.</p>
  </footer>

  <script>
    // Cart Functionality
    let cartCount = 0;
    const cartItems = new Map(); // Use Map to track items and their quantities

    function addToCart(itemName, price) {
      if (cartItems.has(itemName)) {
        // Increment quantity if item exists
        cartItems.set(itemName, { ...cartItems.get(itemName), quantity: cartItems.get(itemName).quantity + 1 });
      } else {
        // Add new item with quantity 1
        cartItems.set(itemName, { price: price, quantity: 1 });
      }
      cartCount++;
      document.getElementById('cart-count').textContent = cartCount;
      alert(`${itemName} added to cart! (Total items: ${cartCount})`);
    }

    // Price Filter Functionality
    document.getElementById('price-filter').addEventListener('input', function () {
      const input = this.value.trim();
      const range = input.split('-').map(num => parseFloat(num.trim()));
      const productCards = document.querySelectorAll('.product-card');

      productCards.forEach(card => {
        const priceText = card.querySelector('p').textContent.replace('$', '');
        const price = parseFloat(priceText);

        if (input === '') {
          card.style.display = 'block';
        } else if (range.length === 1 && !isNaN(range[0])) {
          card.style.display = price === range[0] ? 'block' : 'none';
        } else if (range.length === 2 && !isNaN(range[0]) && !isNaN(range[1])) {
          card.style.display = price >= range[0] && price <= range[1] ? 'block' : 'none';
        } else {
          card.style.display = 'block';
        }
      });
    });
  </script>
</body>
</html
