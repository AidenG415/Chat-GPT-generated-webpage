<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Sweet Crumbs Bakery!</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
</head>
<body>
 
<nav class="container-fluid">
  <ul>
    <li><strong>Sweet Crumbs</strong></li>
  </ul>
  <ul>
    <li><a href="#menu">Menu</a></li>
    <li><a href="#about">About Us</a></li>
    <li><a href="#contact" role="button">Contact</a></li>
  </ul>
</nav>

<main class="container">
  <div class="grid">
    <section>
      <hgroup>
        <h2>Welcome to Sweet Crumbs Bakery</h2>
        <h3>Freshly Baked Happiness</h3>
      </hgroup>
      <p>At Sweet Crumbs, we craft delicious pastries, breads, and cakes with love and the finest ingredients. Step into our cozy bakery and treat yourself today!</p>
      <figure>
        <img src="https://images.unsplash.com/photo-1511690743698-d9d85f2fbf38?auto=format&fit=crop&w=800&q=80" alt="Fresh baked bread">
        <figcaption><a href="https://unsplash.com/photos/LoGxtJVs2i8" target="_blank">Photo by Wesual Click</a></figcaption>
      </figure>
      
      <h3 id="menu">Our Menu</h3>
      <p>Discover our selection of breads, pastries, and special seasonal treats. Everything is baked fresh daily!</p>

      <h3 id="about">About Us</h3>
      <p>Sweet Crumbs started as a dream to bring a little more sweetness into the world. We use time-honored recipes and locally sourced ingredients whenever possible.</p>

      <h3 id="contact">Visit or Contact Us</h3>
      <p>We are located in the heart of town. Stop by for a treat or send us a message below!</p>
    </section>
  </div>
</main>

<section aria-label="Subscribe example">
  <div class="container">
    <article>
      <hgroup>
        <h2>Subscribe</h2>
        <h3>Get updates on fresh bakes and special offers</h3>
      </hgroup>
      <form class="grid">
        <input type="text" id="firstname" name="firstname" placeholder="First name" aria-label="First name" required>
        <input type="email" id="email" name="email" placeholder="Email address" aria-label="Email address" required>
        <button type="submit" onclick="event.preventDefault()">Subscribe</button>
      </form>
    </article>
  </div>
</section>

<footer class="container">
  <small>
    <a href="#">Privacy Policy</a> • <a href="#">Terms of Service</a>
  </small>
</footer>
