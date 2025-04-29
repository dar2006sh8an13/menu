<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Restaurant Menu</title>
 <style>body {
    font-family: 'Segoe UI', sans-serif;
    margin: 0;
    background: #0d0701;
    color: #333;
  }
  
  header {
    background-color: rebeccapurple;
    color: white;
    text-align: center;
    padding: 2rem 1rem;
  }
  
  header h1 {
    margin: 0;
    font-size: 2.5rem;
  }
  
  .menu {
    padding: 2rem;
  }
  
  .menu-category {
    margin-bottom: 2.5rem;
  }
  
  .menu-category h2 {
    color: #c0392b;
    border-bottom: 2px solid #c0392b;
    display: inline-block;
    padding-bottom: 5px;
    margin-bottom: 1rem;
  }
  
  .menu-items {
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;
  }
  
  .item {
    background: white;
    border: 1px solid #eee;
    border-radius: 8px;
    padding: 1rem;
    width: calc(50% - 1rem);
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    transition: transform 0.3s;
  }
  
  .item:hover {
    transform: scale(1.02);
  }
  
  .item img {
    width: 100%;
    border-radius: 8px;
    margin-bottom: 0.5rem;
  }
  
  .item h3 {
    display: flex;
    justify-content: space-between;
    font-size: 1.1rem;
    margin: 0;
  }
  
  footer {
    text-align: center;
    padding: 1rem;
    background-color: #9b79ea;
    font-size: 0.9rem;
  }
  
  @media (max-width: 600px) {
    .item {
      width: 100%;
    }
  }
  </style>
</head>
<body>
  <header>
    <h2>DS GROUP OF HOTELS</h2>
    <h1>Spice Delight Restaurant</h1>
    <p>Our Special Menu</p>
  </header>

  <section class="menu">
    <div class="menu-category">
      <h2>Starters</h2>
      <div class="menu-items">
        <div class="item">
          <img src="Tomato Soup.jpg" alt="Soup" />
          <h3>Tomato Soup <span>$4.99</span></h3>
        </div>
        <div class="item">
          <img src="Spring-Rolls.avif" alt="Spring Rolls" />
          <h3>Spring Rolls <span>$6.50</span></h3>
        </div>
        <div class="item">
            <img src="pani-puri.webp" alt="Spring Rolls" />
            <h3>Panipuri<span>$6.50</span></h3>
          </div>
          <div class="item">
            <img src="samosa.webp" alt="Spring Rolls" />
            <h3>Samosa<span>$6.50</span></h3>
          </div>
          <div class="item">
            <img src="chilli paneer.jpeg" alt="Spring Rolls" />
            <h3>chilli paneer<span>$6.50</span></h3>
          </div>
          <div class="item">
            <img src="Chicken-Tikka.jpg"alt="Spring Rolls" />
            <h3>Chicken tikka<span>$6.50</span></h3>
          </div>
          <div class="item">
            <img src="Aloo bonda.avif" alt="Spring Rolls" />
            <h3>Aloo bonda<span>$6.50</span></h3>
          </div>
          <div class="item">
            <img src="Dahi kebabs.jpg" alt="Spring Rolls" />
            <h3>Dahi kebabs<span>$6.50</span></h3>
          </div>
          <div class="item">
            <img src="paneer-pakora.webp" alt="Spring Rolls" />
            <h3>Paneer pakoda<span>$6.50</span></h3>
          </div>  
          <div class="item">
            <img src="Vegetable kabab" alt="Spring Rolls" />
            <h3>Vegetable kabab<span>$6.50</span></h3>
          </div>        
      </div>
    </div>

    <div class="menu-category">
      <h2>Main Course</h2>
      <div class="menu-items">
        <div class="item">
          <img src="PaneerButterMasala.webp" alt="Paneer Butter Masala" />
          <h3>Paneer Butter Masala <span>$9.99</span></h3>
        </div>
        <div class="item">
          <img src="veg-biryani.jpg" alt="Veg Biryani" />
          <h3>Veg Biryani <span>$8.50</span></h3>
        </div>
        <div class="menu-items">
            <div class="item">
              <img src="kerala fish curry.jpeg" alt="Paneer Butter Masala" />
              <h3>kerala fish curry<span>$9.99</span></h3>
            </div><div class="item">
                <img src="kerala sadya.jpg" alt="Paneer Butter Masala" />
                <h3>kerala sadyaa<span>$9.99</span></h3>
              </div>
              <div class="item">
                <img src="kodi kura.avif" alt="Paneer Butter Masala" />
                <h3>kodi kura<span>$9.99</span></h3>
              </div>
              <div class="item">
                <img src="hydrabad biriyani.webp" alt="Paneer Butter Masala" />
                <h3>hydrabad biriyani<span>$9.99</span></h3>
              </div>
              <div class="item">
                <img src="ragi mudde nati koli saaru.jpeg" alt="Paneer Butter Masala" />
                <h3>ragi mudde nati koli saaru<span>$9.99</span></h3>
              </div>
              <div class="item">
                <img src="majjige-huli.jpg" alt="Paneer Butter Masala" />
                <h3>majjige huli<span>$9.99</span></h3>
              </div>
              <div class="item">
                <img src="Jolada Rotti.jpeg" alt="Paneer Butter Masala" />
                <h3> Jolada Rotti uta<span>$9.99</span></h3>
              </div>
              <div class="item">
                <img src="ambur biryani.jpeg" alt="Paneer Butter Masala" />
                <h3>ambur biryani<span>$9.99</span></h3>
              </div>

      </div>
    </div>

    <div class="menu-category">
      <h2>Desserts</h2>
      <div class="menu-items">
        <div class="item">
          <img src="Gulab Jamun.webp" alt="Gulab Jamun" />
          <h3>Gulab Jamun <span>$3.99</span></h3>
        </div>
        <div class="item">
          <img src="Vanilla Ice Cream.webp" alt="Ice Cream" />
          <h3>Vanilla Ice Cream <span>$2.99</span></h3>
        </div>
        <div class="item">
            <img src="Cakes.jpg" alt="Ice Cream" />
            <h3>Cakes<span>$2.99</span></h3>
          </div>
          <div class="item">
            <img src="Cookies.jpeg" alt="Ice Cream" />
            <h3>Cookies<span>$2.99</span></h3>
          </div>
          <div class="item">
            <img src="Brownies.jpg" alt="Ice Cream" />
            <h3>Brownies<span>$2.99</span></h3>
          </div>
          <div class="item">
            <img src="Cheesecake.jpeg" alt="Ice Cream" />
            <h3>Cheesecake <span>$2.99</span></h3>
          </div>
          <div class="item">
            <img src="Pies.jpeg" alt="Ice Cream" />
            <h3>Pies <span>$2.99</span></h3>
          </div>
          <div class="item">
            <img src="Tarts.jpg" alt="Ice Cream" />
            <h3>Tarts<span>$2.99</span></h3>
          </div>
          <div class="item">
            <img src="Mousse.jpg" alt="Ice Cream" />
            <h3>Mousse <span>$2.99</span></h3>
          </div>
          <div class="item">
            <img src="Tiramisu.jpeg" alt="Ice Cream" />
            <h3>Tiramisu <span>$2.99</span></h3>
          </div>
    </div>
    </div>
  </section>
  <footer>
    <div class="footer-container">
      <div class="footer-info">
        <h4>Contact Us</h4>
        <p><strong>Address:</strong> Spice Delight Hostel, 2nd Cross, MG Road, Bengaluru, Karnataka</p>
        <p><strong>Email:</strong> <a href="mailto:spicedelight@email.com">spicedelight@email.com</a></p>
        <p><strong>Phone:</strong> <a href="tel:+919876543210">+91 98765 43210</a></p>
      </div>
      <div class="footer-social">
        <h4>Follow Us</h4>
        <a href="https://instagram.com/spicedelight" target="_blank">Instagram</a> |
        <a href="https://facebook.com/spicedelight" target="_blank">Facebook</a>
      </div>
    </div>
    <p class="copyright">&copy; 2025 Spice Delight. All rights reserved.</p>
  </footer>
  
</body>
</html>
