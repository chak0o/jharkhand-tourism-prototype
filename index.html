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
      background: linear-gradient(to bottom, #f4f4f9, #dbe6f2);
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #2c3e50, #3498db);
      color: white;
      padding: 1.5em;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    section {
      padding: 2em;
      background: #ffffffcc;
      margin: 1em auto;
      border-radius: 12px;
      max-width: 1000px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    h2 {
      color: #e67e22;
      text-shadow: 1px 1px 2px rgba(0,0,0,0.2);
    }

    .map-container {
      position: relative;
      display: flex;
      justify-content: center;
      margin: 1em 0;
      border: 4px solid #3498db;
      border-radius: 12px;
      overflow: hidden;
    }

    .map-container img {
      max-width: 100%;
      border-radius: 8px;
      filter: brightness(1.1);
    }

    .pin {
      position: absolute;
      width: 16px;
      height: 16px;
      background: linear-gradient(to bottom, #e74c3c, #c0392b);
      border: 2px solid #fff;
      border-radius: 50%;
      cursor: pointer;
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .pin:hover {
      transform: scale(1.5);
      box-shadow: 0 0 10px #e74c3c;
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
      outline: none;
      transition: all 0.3s;
    }

    .search-bar input:focus {
      border-color: #3498db;
      box-shadow: 0 0 8px #3498db;
    }

    .search-bar button {
      padding: 0.8em 1.5em;
      border-radius: 25px;
      border: none;
      background: linear-gradient(to right, #2980b9, #6dd5fa);
      color: white;
      cursor: pointer;
      transition: all 0.3s;
    }

    .search-bar button:hover {
      background: linear-gradient(to right, #6dd5fa, #2980b9);
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.5em;
    }

    .card {
      background: linear-gradient(to bottom, #ffffff, #f1f8ff);
      padding: 1em;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    }

    .chat-box {
      background: #fefefe;
      padding: 1em;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    .channel h4 {
      color: #16a085;
    }

    .chat-message strong {
      color: #2980b9;
    }

    /* AI Chatbot */
    #chatbot {
      padding: 40px;
      background: linear-gradient(to right, #f7f9fc, #e0f7fa);
      border-radius: 12px;
      margin: 30px auto;
      max-width: 800px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .chat-container {
      border: 1px solid #ccc;
      border-radius: 10px;
      background: white;
      padding: 15px;
      max-width: 700px;
      margin: auto;
      display: flex;
      flex-direction: column;
    }

    .chat-box-inner {
      max-height: 250px;
      overflow-y: auto;
      margin-bottom: 15px;
      display: flex;
      flex-direction: column;
    }

    .message {
      padding: 10px;
      margin: 8px 0;
      border-radius: 8px;
      max-width: 75%;
    }

    .message.bot {
      background: #e1f0ff;
      align-self: flex-start;
    }

    .message.user {
      background: #d1ffd6;
      align-self: flex-end;
      margin-left: auto;
    }

    .chat-input {
      display: flex;
      gap: 10px;
    }

    .chat-input input {
      flex: 1;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }

    .chat-input button {
      padding: 10px 20px;
      background: #007bff;
      border: none;
      color: white;
      border-radius: 6px;
      cursor: pointer;
    }

    /* Center Personal Dashboard Section */
    #dashboard {
      padding: 40px;
      background: linear-gradient(to right, #fff0f5, #ffe4e1);
      border-radius: 12px;
      max-width: 900px;
      margin: 30px auto;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
      text-align: center;
    }

    #dashboard img {
      display: block;
      margin: 20px auto;
      border-radius: 12px;
    }

    #dashboard ul {
      list-style: none;
      padding: 0;
      margin: 20px auto;
      display: inline-block;
      text-align: left;
    }

    #dashboard ul li {
      margin: 10px 0;
      padding-left: 1em;
      position: relative;
    }

    #dashboard ul li::before {
      content: "✔";
      color: #e67e22;
      position: absolute;
      left: 0;
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
      <div class="pin" style="top:55%;left:45%;" title="Ranchi"></div>
      <div class="pin" style="top:52%;left:50%;" title="Hundru Falls"></div>
      <div class="pin" style="top:60%;left:52%;" title="Dassam Falls"></div>
      <div class="pin" style="top:68%;left:35%;" title="Netarhat"></div>
      <div class="pin" style="top:25%;left:65%;" title="Deoghar"></div>
    </div>
  </section>

  <!-- AI Chatbot Section -->
  <section id="chatbot">
    <h2>🤖 AI Travel Assistant</h2>
    <p>Meet our AI-powered assistant! It helps tourists with guidance, answers questions, and provides quick tips for emergencies. (Prototype only)</p>
    <div class="chat-container">
      <div class="chat-box-inner" id="chatBox">
        <div class="message bot">👋 Hello! I’m your Jharkhand Travel Assistant. How can I help you today?</div>
      </div>
      <div class="chat-input">
        <input type="text" id="chatInput" placeholder="Type your message here...">
        <button id="sendBtn">Send</button>
      </div>
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
  </section>

  <!-- Recommendations Section -->
  <section id="recommendations">
    <h2>Top Recommendations</h2>
    <p>Jharkhand is full of mesmerizing natural beauty, temples, forests, and cultural experiences. Here are some must-visit destinations for tourists:</p>
    <div class="grid">
      <div class="card">
        <h3>Hundru Falls</h3>
        <p>Breathtaking waterfall and lush greenery.</p>
      </div>
      <div class="card">
        <h3>Dassam Falls</h3>
        <p>Perfect for nature lovers and photographers.</p>
      </div>
      <div class="card">
        <h3>Netarhat</h3>
        <p>Known as the ‘Queen of Chotanagpur’.</p>
      </div>
      <div class="card">
        <h3>Deoghar</h3>
        <p>Baba Baidyanath Temple, one of the twelve Jyotirlingas in India.</p>
      </div>
    </div>
  </section>

  <!-- Personal Dashboard -->
  <section id="dashboard">
    <h2>Plan Your Trip</h2>
    <p>Personal dashboard to plan your travel route, expenses, and trip settings.</p>
    <img src="images.jpg" alt="Jharkhand Map">
    <ul>
      <li>Plan your route across Jharkhand.</li>
      <li>Estimate budget for travel and stay.</li>
      <li>Save trips as Public or Private.</li>
      <li>Edit, update, or share your trip with others.</li>
      <li>Upload your trip map for others to see possible routes.</li>
    </ul>
  </section>

  <!-- JavaScript for chatbot -->
  <script>
    const chatBox = document.getElementById("chatBox");
    const input = document.getElementById("chatInput");
    const button = document.getElementById("sendBtn");

    function addMessage(text, sender="user") {
      const msg = document.createElement("div");
      msg.classList.add("message", sender);
      msg.textContent = (sender === "user" ? "🙂 " : "🤖 ") + text;
      chatBox.appendChild(msg);
      chatBox.scrollTop = chatBox.scrollHeight;
    }

    button.addEventListener("click", () => {
      const text = input.value.trim();
      if(text) {
        addMessage(text, "user");
        input.value = "";

        // Simulated bot reply
        setTimeout(() => {
          let reply = "I’m still a demo 🤖, but I’ll soon be able to answer!";
          if(text.toLowerCase().includes("waterfall")) {
            reply = "You should visit Dassam Falls or Hundru Falls!";
          } else if(text.toLowerCase().includes("temple")) {
            reply = "Deoghar Temple is one of the best spiritual places to visit.";
          }
          addMessage(reply, "bot");
        }, 1000);
      }
    });
  </script>
</body>
</html>
