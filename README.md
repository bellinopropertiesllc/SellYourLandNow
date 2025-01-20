<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bellino Properties LLC - Land Sales</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background: linear-gradient(to bottom, rgba(255, 255, 255, 0.5), rgba(255, 255, 255, 0.5)),
        url('mountain.jpg') no-repeat center/cover;
      color: #333;
      scroll-behavior: smooth;
    }
    header {
      background-color: rgba(255, 255, 255, 0.9);
      padding: 20px;
      border-bottom: 2px solid #ccc;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header img {
      height: 100px;
      margin-left: 12.7px; /* Move logo 1/2 inch to the right */
    }
    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      gap: 20px;
    }
    nav ul li a {
      text-decoration: none;
      font-weight: bold;
      color: #0056b3;
      transition: color 0.3s;
    }
    nav ul li a:hover {
      color: #003d80;
    }
    .hero {
      background: linear-gradient(to bottom, rgba(0, 86, 179, 0.95), rgba(0, 0, 0, 0.7)),
        url('https://via.placeholder.com/1200x500') no-repeat center/cover;
      height: 500px;
      color: white;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    .hero h1 {
      font-size: 56px;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 22px;
      text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.7);
    }
    .hero .tagline {
      font-size: 20px;
      font-weight: 600;
      margin: 15px 0;
    }
    .hero button {
      padding: 10px 20px;
      background: linear-gradient(to right, #0056b3, #3399ff);
      color: white;
      border: none;
      border-radius: 25px;
      font-size: 16px;
      cursor: pointer;
      box-shadow: 0 4px 6px rgba(0, 86, 179, 0.3);
      transition: all 0.3s;
    }
    .hero button:hover {
      background-color: #3399ff;
      transform: scale(1.1);
    }
    section {
      padding: 40px 10%;
      background-color: rgba(255, 255, 255, 0.85);
      margin: 20px 0;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }
    section ul {
      list-style: none;
      padding: 0;
      display: flex;
      gap: 20px;
    }
    section ul li {
      flex: 1;
      background-color: #ffffff;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      position: relative;
    }
    section ul li img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      margin-top: 10px;
      max-height: 150px;
    }
  </style>
</head>
<body>
  <header>
    <img src="bp-logo.jpg" alt="Bellino Properties LLC Logo">
    <nav>
      <ul>
        <li><a href="#accept-offers">Accept Offers</a></li>
        <li><a href="#properties-for-sale">Properties for Sale</a></li>
        <li><a href="#past-sales">Past Sales</a></li>
      </ul>
    </nav>
  </header>

  <div class="hero">
    <h1>Bellino Properties LLC</h1>
    <p class="tagline">Your Trusted Partner in Land Sales</p>
    <p>Cash Offers | No Fees | Quick Closes</p>
    <a href="#properties-for-sale"><button>Explore Properties</button></a>
  </div>

  <!-- Accept Offers Section -->
  <section id="accept-offers" style="text-align: center;">
    <h2>Accept an Offer</h2>
    <iframe
      src="https://docs.google.com/forms/d/e/1FAIpQLSeX19pIzaSywGQVpxsiM8POFiXGFcP88HvQSOlyQZ9klxZZLw/viewform?embedded=true"
      width="500"
      height="400"
      frameborder="0"
      marginheight="0"
      marginwidth="0"
      style="border: 1px solid #ccc; border-radius: 8px;">
    Loading…
    </iframe>
  </section>

  <!-- Properties for Sale Section -->
  <section id="properties-for-sale">
    <h2>Properties for Sale</h2>
    <ul>
      <li>
        <h3>2.7 Acres</h3>
        <p>$18,500</p>
        <p>Elko, NV</p>
        <a href="https://www.zillow.com/homedetails/Goldrush-Dr-Elko-NV-89801/247442961_zpid/" target="_blank">
          <img src="elko.jpg" alt="2.7 Acres in Elko, NV">
        </a>
      </li>
      <li style="position: relative;">
        <h3>0.5 Acres</h3>
        <p>$80,000</p>
        <p>Jupiter, FL</p>
        <a href="#" target="_blank" style="position: relative; display: inline-block;">
          <img src="florida.jpg" alt="0.5 Acres in Jupiter, FL" style="width: 100%; border-radius: 10px;">
          <span style="position: absolute; top: 10px; left: 10px; background-color: rgba(255, 0, 0, 0.8); color: white; padding: 5px 10px; font-size: 20px; font-weight: bold; border-radius: 5px;">Under Contract!</span>
        </a>
      </li>
      <li style="position: relative;">
        <h3>25 Acres</h3>
        <p>$73,250</p>
        <p>Hartsell, CO</p>
        <a href="#" target="_blank" style="position: relative; display: inline-block;">
          <img src="colorado.jpg" alt="25 Acres in Hartsell, CO" style="width: 100%; border-radius: 10px;">
          <span style="position: absolute; top: 10px; left: 10px; background-color: rgba(255, 0, 0, 0.8); color: white; padding: 5px 10px; font-size: 20px; font-weight: bold; border-radius: 5px;">Under Contract!</span>
        </a>
      </li>
    </ul>
  </section>

  <!-- Past Sales Section -->
  <section id="past-sales">
    <h2>Past Sales</h2>
    <ul>
      <li style="position: relative;">
        <h3>1.13 Acres</h3>
        <p>Sold for $7,995</p>
        <p>Yucca, AZ</p>
        <div style="position: relative;">
          <img src="az.jpg" alt="1.13 Acres in Yucca, AZ" style="width: 100%; border-radius: 10px; max-height: 150px;">
          <span style="
            position: absolute;
            top: 10px;
            left: 10px;
            background-color: rgba(255, 0, 0, 0.8);
            color: white;
            padding: 5px 10px;
            font-size: 20px;
            font-weight: bold;
            border-radius: 5px;
            text-transform: uppercase;">SOLD!</span>
        </div>
      </li>
      <li>
         <h3>1.13 Acres</h3>
        <p>Sold for $30,000</p>
        <p>Golden Valley, AZ</p>
        <div style="position: relative;">
          <img src="az2.jpg" alt="1.13 Acres in Golden Valley, AZ" style="width: 100%; border-radius: 10px; max-height: 150px;">
          <span style="
            position: absolute;
            top: 10px;
            left: 10px;
            background-color: rgba(255, 0, 0, 0.8);
            color: white;
            padding: 5px 10px;
            font-size: 20px;
            font-weight: bold;
            border-radius: 5px;
            text-transform: uppercase;">SOLD!</span>
        </div>
      </li>
      <li>
        <h3>0.25 Acres</h3>
        <p>Sold for $9,900</p>
        <p>Pahrump, NV</p>
        <div style="position: relative;">
          <img src="lv.jpg" alt="0.25 Acres in Pahrump,NV" style="width: 100%; border-radius: 10px; max-height: 150px;">
          <span style="
            position: absolute;
            top: 10px;
            left: 10px;
            background-color: rgba(255, 0, 0, 0.8);
            color: white;
            padding: 5px 10px;
            font-size: 20px;
            font-weight: bold;
            border-radius: 5px;
            text-transform: uppercase;">SOLD!</span>
        </div>

      </li>
    </ul>
  </section>
</body>
</html>
