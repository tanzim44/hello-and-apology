<!DOCTYPE html>
<html lang="en">
<head> 
  <meta charset="UTF-8" />
  <title>Forgive Me ❤️</title>
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Wendy+One&display=swap" rel="stylesheet" />
  <style>
    body {
      background-color: #fff0f5;
      font-family: 'Wendy One', cursive, sans-serif;
      text-align: center;
      padding: 50px;
      overflow-x: hidden;
      margin: 0;
      height: 100vh;
      position: relative;
    }

    h1 {
      color: #e91e63;
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 10px;
      cursor: pointer;
      position: relative;
      z-index: 10;
    }

    .flower {
      display: inline-block;
      font-size: 30px;
      animation: float 3s ease-in-out infinite;
    }

    @keyframes float {
      0%   { transform: translateX(0); }
      50%  { transform: translateX(10px); }
      100% { transform: translateX(0); }
    }

    .message {
      background-color: #ffe4e1;
      border-radius: 15px;
      padding: 30px;
      display: inline-block;
      box-shadow: 0 0 10px pink;
      position: relative;
      z-index: 1;
      max-width: 600px;
    }

    .heart {
      font-size: 50px;
      color: red;
      animation: pulse 1s infinite;
      margin: 20px 0;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.1); }
      100% { transform: scale(1); }
    }

    .love-rain {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      pointer-events: none;
      overflow: hidden;
      z-index: 0;
    }

    .heart-drop {
      position: absolute;
      color: red;
      font-size: 20px;
      animation: fall 3s linear forwards;
      opacity: 0.8;
      user-select: none;
    }

    @keyframes fall {
      0% {
        transform: translateY(-100px) rotate(0deg);
        opacity: 0;
      }
      10% {
        opacity: 1;
      }
      100% {
        transform: translateY(100vh) rotate(360deg);
        opacity: 0;
      }
    }

    /* Puppy watermark inside message */
    .puppy-inside {
      position: absolute;
      top: 10px;
      left: 50%;
      transform: translateX(-50%);
      width: 120px;
      opacity: 0.08;
      z-index: 2; /* increased so it’s clickable */
      animation: floatPuppy 4s ease-in-out infinite;
      cursor: pointer;
      user-select: none;
    }

    @keyframes floatPuppy {
      0% { transform: translateX(-50%) translateY(0); }
      50% { transform: translateX(-50%) translateY(-10px); }
      100% { transform: translateX(-50%) translateY(0); }
    }
  </style>
</head>
<body>
  <div class="love-rain" id="loveRainContainer"></div>

  <div class="message">
    <!-- Puppy watermark inside message -->
    <img
      src="https://i.ibb.co/8gZx4mG/cute-anime-dog.png"
      alt="Cute Anime Puppy Waving"
      class="puppy-inside"
      onclick="alert('Hi! 🐶 The puppy says you should forgive him! 💖')"
      draggable="false"
    />

    <h1 id="apologyTrigger">
      <span class="flower">🌸</span>
      Apology Application
      <span class="flower">🌸</span>
    </h1>
    <p><strong>To:</strong> My Most Beautiful Girlfriend</p>
    <p><strong>Subject:</strong> A Humble Request for Forgiveness</p>
    <p>Dear My Sweetest Love,</p>
    <p>
      Hey my sweet cupcake,  
      I know I’ve made a mistake, and I feel like a lost puppy without your love 🐶💔.  
      I’m sorry from the very bottom of my squishy, mushy heart.  
      If I could turn back time, I’d go back and hug you tight instead of hurting you even a little 💕.  
      You're my sunshine on gloomy days ☀️, my favorite person, my forever.  
      Please forgive this silly little potato 🥔 who loves you more than all the stars in the sky ✨🌙.  
      I pinky promise to make it up to you — with cuddles, smiles, and extra chocolate 🍫💝.  
      Will you forgive me, my love? 🥺❤️
    </p>

    <p class="heart">❤️</p>
    <p><em>Sincerely,<br>Your guilty but deeply loving babyboy <br>এখন কি আমাকে ক্ষমা করা হচ্ছে?</em></p>
  </div>

  <script>
    const apologyTrigger = document.getElementById('apologyTrigger');
    const rainContainer = document.getElementById('loveRainContainer');

    function createHeart() {
      const heart = document.createElement('div');
      heart.classList.add('heart-drop');
      heart.style.left = Math.random() * 100 + 'vw';
      heart.style.fontSize = (15 + Math.random() * 15) + 'px'; // random size
      heart.innerText = '❤️';
      rainContainer.appendChild(heart);

      setTimeout(() => {
        heart.remove();
      }, 3000);
    }

    apologyTrigger.addEventListener('click', () => {
      for (let i = 0; i < 30; i++) {
        setTimeout(createHeart, i * 100);
      }
    });
  </script>
</body>
</html>
