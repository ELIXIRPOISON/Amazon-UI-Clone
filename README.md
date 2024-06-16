# Amazon UI Clone

This project is a clone of Amazon's UI, demonstrating various sections styled using CSS.
This project showcases a simple webpage layout with a header, banner, hero section, shop section, and footer. 
The HTML structure is organized using semantic tags, and the CSS provides styling and responsiveness to ensure a clean and user-friendly interface. 
The use of flexbox and grid layouts allows for flexible and responsive design.

## Hosted Link

The project is hosted on GitHub Pages. [Live Demo](https://elixirpoison.github.io/Amazon-UI-Clone/WT5Amazon)

## Screenshots

### Header
![Header](screenshots/header.png)
- **CSS Properties Used:** `background-color`, `height`, `display`, `align-items`, `justify-content`, `color`, `max-width`, `margin`, `cursor`

### Banner
![Banner](screenshots/banner.png)
- **CSS Properties Used:** `padding`, `background-color`, `color`, `font-size`, `margin`, `display`, `align-items`, `justify-content`, `gap`

### Hero Section
![Hero Section](screenshots/hero-section.png)
- **CSS Properties Used:** `height`, `background-image`, `background-position`, `background-size`

### Shop Section
![Shop Section](screenshots/shop-section.png)
- **CSS Properties Used:** `display`, `align-items`, `flex-direction`, `background-color`, `padding`, `grid-template-columns`, `gap`, `max-width`, `overflow`, `transform`, `transition`

### Footer
![Footer](screenshots/footer.png)
- **CSS Properties Used:** `background-color`, `color`, `font-size`, `font-weight`, `display`, `justify-content`, `width`, `margin`, `list-style`, `text-decoration`, `hover`

## HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Amazon UI Clone</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Geekster Project</title>
  <link rel="stylesheet" href="WT5Amazon.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200">
  </head>
  <body>
    <header>
      <nav class="navbar">
        <div class="nav-logo">
          <a href="#"><img src="https://priyanshu-240499.github.io/Assignments-CSS/Weekly%20Test%20for%20CSS%20(Week-3)/images/amazon_logo.png" alt="logo"></a>
        </div>
        <div class="address">
          <a href="#" class="deliver">Deliver</a>
          <div class="map-icon">
            <span class="material-symbols-outlined">location_on</span>
            <a href="#" class="location">India</a>
          </div>
        </div>

        <div class="nav-search">
          <select class="select-search">
            <option>All</option>
            <option>All Categories</option>
            <option>Amazon Devices</option>
          </select>
          <input type="text" placeholder="Search Amazon" class="search-input">
          <div class="search-icon">
            <span class="material-symbols-outlined">search</span>
          </div>
        </div>

        <div class="sign-in">
         <a href="#"> <p>Hello, sign in</p>
          <span>Account &amp; Lists</span></a>
        </div>

        <div class="returns">
          <a href="#"><p>Returns</p>
            <span>&amp; Orders</span></a>
        </div>

        <div class="cart">
          <a href="#">
            <span class="material-symbols-outlined cart-icon">shopping_cart</span>
            </a>
            <p>Cart</p>
        </div>
      </nav>
      
      <div class="banner">
        <div class="banner-content">
          <div class="panel">
            <span class="material-symbols-outlined">menu</span>
            <a href="#">All</a>
          </div>
  
          <ul class="links">
            <li><a href="#">Today's Deals</a></li>
            <li><a href="#">Customer Service</a></li>
            <li><a href="#">Registry</a></li>
            <li><a href="#">Gift Cards</a></li>
            <li><a href="#">Sell</a></li>
          </ul>
          <div class="deals">
            <a href="#">Shop deals in Electronics</a>
          </div>
        </div>
      </div>
    </header>

    <section class="hero-section"></section>

    <section class="shop-section">
      <div class="shop-images">
        <div class="shop-link" data-aos="flip-left" data-aos-duration='900'>
          <h3>Shop Laptops &amp; Tables</h3>
          <img src="https://priyanshu-240499.github.io/Assignments-CSS/Weekly%20Test%20for%20CSS%20(Week-3)/images/img-1.png" alt="card">
          <a href="#">Shop now</a>
        </div>
        <div class="shop-link" data-aos="flip-left" data-aos-duration='1000' >
          <h3>Shop Smartwatches</h3>
          <img src="https://priyanshu-240499.github.io/Assignments-CSS/Weekly%20Test%20for%20CSS%20(Week-3)/images/img-2.png" alt="card">
          <a href="#">Shop now</a>
        </div>
        <div class="shop-link" data-aos="flip-left" data-aos-duration='1100'>
          <h3>Create with Strip Lights</h3>
          <img src="https://priyanshu-240499.github.io/Assignments-CSS/Weekly%20Test%20for%20CSS%20(Week-3)/images/img-3.png" alt="card">
          <a href="#">Shop now</a>
        </div>
        <div class="shop-link" data-aos="flip-left" data-aos-duration='1200'>
          <h3>Home Refresh Ideas</h3>
          <img src="https://priyanshu-240499.github.io/Assignments-CSS/Weekly%20Test%20for%20CSS%20(Week-3)/images/img-4.png" alt="card">
          <a href="#">Shop now</a>
        </div>
      </div>
    </section>

    <footer>
      <a href="#" class="footer-title">
        Back to top
      </a>
      <div class="footer-items">
        <ul>
          <h3>Get to Know Us</h3>
          <li><a href="#">About us</a></li>
          <li><a href="#">Careers</a></li>
          <li><a href="#">Press Release</a></li>
          <li><a href="#">Amazon Science</a></li>
        </ul>
        <ul>
          <h3>Connect with Us</h3>
          <li><a href="#">Facebook</a></li>
          <li><a href="#">Twitter</a></li>
          <li><a href="#">Instagram</a></li>
        </ul>
        <ul>
          <h3>Make Money with Us</h3>
          <li><a href="#">Sell on Amazon</a></li>
          <li><a href="#">Sell under Amazon Accelerator</a></li>
          <li><a href="#">Protect and Build Your Brand</a></li>
          <li><a href="#">Amazon Global Selling</a></li>
          <li><a href="#">Become an Affiliate</a></li>
          <li><a href="#">Fulfillment by Amazon</a></li>
          <li><a href="#">Advertise Your Products</a></li>
          <li><a href="#">Amazon Pay on Merchants</a></li>
        </ul>
        <ul>
          <h3>Let Us Help You</h3>
          <li><a href="#">COVID-19 and Amazon</a></li>
          <li><a href="#">Your Account</a></li>
          <li><a href="#">Return Centre</a></li>
          <li><a href="#">100% Purchase Protection</a></li>
          <li><a href="#">Amazon App Download</a></li>
          <li><a href="#">Help</a></li>
        </ul>
      </div>
    </footer>
  </body>
</body>
</html>>
</body>
</html>
