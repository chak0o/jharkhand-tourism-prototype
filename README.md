<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jharkhand Tourism Prototype</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #f4f4f9;
      color: #333;
    }
    header {
      background: #2c3e50;
      color: white;
      padding: 1.5em;
      text-align: center;
    }
    section {
      padding: 2em;
    }
    h2 {
      color: #2c3e50;
    }
    .map-container {
      position: relative;
      display: flex;
      justify-content: center;
      margin: 1em 0;
    }
    .map-container img {
      max-width: 100%;
      border-radius: 8px;
    }
    .pin {
      position: absolute;
      width: 14px;
      height: 14px;
      background: red;
      border-radius: 50%;
      cursor: pointer;
    }
    .search-bar {
      display: flex;
      justify-content: center;
      margin-bottom: 1.5em;
    }
    .search-bar input {
      width: 50%;
      padding: 0.8em;
      border-radius: 25px;
      border: 1px solid #ccc;
      margin-right: 10px;
    }
    .search-bar button {
      padding: 0.8em 1.5em;
      border-radius: 25px;
      border: none;
      background: #2980b9;
      color: white;
      cursor: pointer;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.5em;
    }
    .card {
      background: white;
      padding: 1em;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .chat-box {
      background: #fff;
      padding: 1em;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .channel {
      margin-bottom: 1em;
    }
    .channel h4 {
      margin: 0.5em 0;
      color: #2980b9;
    }
    .chat-message {
      padding: 0.5em;
      border-bottom: 1px solid #ddd;
    }
    .chat-message strong {
      color: #2c3e50;
    }
  </style>
</head>
<body>
  <header>
    <h1>Jharkhand Tourism Prototype</h1>
    <p>Explore | Connect | Experience</p>
  </header>

 <!-- Search Section -->
<section id="search">
  <h2>Search Places</h2>
  <p>Use the search bar to quickly find famous tourist spots, cultural heritage sites, waterfalls, temples, and hidden gems of Jharkhand.</p>
  <div class="search-bar">
    <input type="text" placeholder="Search for places...">
    <button>Search</button>
  </div>
  <div style="text-align:center; margin-top:1.5em;">
    <h3>Most Searched</h3>
    <ul style="list-style:none; padding:0; display:inline-block; text-align:left;">
      <li>Hundru Falls</li>
      <li>Dassam Falls</li>
      <li>Netarhat</li>
      <li>Deoghar Temple</li>
      <li>Betla National Park</li>
      <li>Patratu Valley</li>
      <li>Parasnath Hills</li>
    </ul>
  </div>
</section>

  <!-- Map Section -->
  <section id="map">
    <h2>Explore Jharkhand</h2>
    <div class="map-container">
      <img src="images.jpg" alt="Jharkhand Tourist Map">
      <!-- Pins aligned -->
      <div class="pin" style="top:55%;left:45%;" title="Ranchi"></div>
      <div class="pin" style="top:52%;left:50%;" title="Hundru Falls"></div>
      <div class="pin" style="top:60%;left:52%;" title="Dassam Falls"></div>
      <div class="pin" style="top:68%;left:35%;" title="Netarhat"></div>
      <div class="pin" style="top:25%;left:65%;" title="Deoghar"></div>
    </div>
  </section>

<!-- Emergency Section -->
<section id="emergency">
  <h2>Emergency Contacts</h2>
  <p>If you face any difficulty during your travel in Jharkhand, these emergency helplines are available 24/7. Save them before you begin your journey.</p>
  <div class="grid">
    <div class="card">
      <h3>Police Helpline</h3>
      <p>Dial 100 for immediate police assistance in case of theft, assault, missing persons, or unsafe situations.</p>
    </div>
    <div class="card">
      <h3>Ambulance</h3>
      <p>Dial 108 for medical emergencies. Trained paramedics and ambulances are available across Jharkhand 24/7.</p>
    </div>
    <div class="card">
      <h3>Women’s Helpline</h3>
      <p>Dial 181 to seek urgent help in cases of harassment, abuse, or unsafe environments.</p>
    </div>
    <div class="card">
      <h3>Child Helpline</h3>
      <p>Dial 1098 if you see a child in distress, lost, or in need of urgent care.</p>
    </div>
  </div>
  <p style="margin-top:1.5em; font-style: italic;">
    Disclaimer: If you are lost, stay calm and stay in your place. Do not panic. Ask for help from nearby locals or contact the helpline numbers above. 
    Always keep a written note of your hotel details and emergency contacts.
  </p>
</section>

  <!-- Recommendations Section -->
<section id="recommendations">
  <h2>Top Recommendations</h2>
  <p>Jharkhand is full of mesmerizing natural beauty, temples, forests, and cultural experiences. Here are some must-visit destinations for tourists:</p>
  <div class="grid">
    <div class="card">
      <h3>Hundru Falls</h3>
      <p>This place has the picture of Hundru Falls. Known for its breathtaking waterfall and lush greenery.</p>
    </div>
    <div class="card">
      <h3>Dassam Falls</h3>
      <p>This place has the picture of Dassam Falls. Perfect for nature lovers and photographers.</p>
    </div>
    <div class="card">
      <h3>Netarhat</h3>
      <p>This place has the picture of Netarhat Sunset Point. A hill station known as the ‘Queen of Chotanagpur’.</p>
    </div>
    <div class="card">
      <h3>Deoghar</h3>
      <p>This place has the picture of Baba Baidyanath Temple. One of the twelve Jyotirlingas in India.</p>
    </div>
  </div>
</section>

  <!-- Chat Section -->
  <section id="chat">
    <h2>Community Chat</h2>
    <div class="chat-box">
      <div class="channel">
        <h4>#general</h4>
        <div class="chat-message"><strong>Aditi:</strong> Hi! I just visited Hundru Falls today. Amazing experience!</div>
        <div class="chat-message"><strong>Ravi:</strong> Oh great! Planning to go next week. Any tips?</div>
      </div>
      <div class="channel">
        <h4>#food</h4>
        <div class="chat-message"><strong>Neha:</strong> Best litti-chokha stalls near Ranchi railway station!</div>
      </div>
      <div class="channel">
        <h4>#travel-tips</h4>
        <div class="chat-message"><strong>TouristGuideBot:</strong> Remember to carry light woolens if visiting Netarhat.</div>
      </div>
    </div>
  </section>

<!-- Marketplace Section -->
<section id="marketplace">
  <h2>Marketplace</h2>
  <p>Jharkhand is not just about scenic beauty, but also its vibrant local markets, tribal art, and traditional cuisines. Explore the marketplace to discover local culture.</p>
  <div class="grid">
    <div class="card">
      <h3>Handicrafts</h3>
      <p>Local artisans selling traditional tribal crafts. Great for souvenirs and unique handmade items.</p>
    </div>
    <div class="card">
      <h3>Textiles</h3>
      <p>Famous Jharkhand textiles and handloom fabrics, known for their durability and traditional patterns.</p>
    </div>
    <div class="card">
      <h3>Local Food Stalls</h3>
      <p>Explore authentic food joints serving dishes like litti-chokha, dhuska, and tribal delicacies.</p>
    </div>
  </div>
</section>

  <!-- Personal Dashboard -->
  <section id="dashboard">
    <h2>Plan Your Trip</h2>
    <p>Personal dashboard to plan your travel route, expenses, and trip settings.</p>
    <img src="images.jpg" alt="Jharkhand Map" style="max-width:100%; border-radius:10px; margin-bottom:1em;">
    <ul>
      <li>Plan your route across Jharkhand.</li>
      <li>Estimate budget for travel and stay.</li>
      <li>Save trips as Public or Private.</li>
      <li>Edit, update, or share your trip with others.</li>
      <li>Upload your trip map for others to see possible routes.</li>
    </ul>
  </section>
</body>
</html>
