# Nasahhara
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Birthday Nasahhara! 🎉</title>
  <style>
    body {
      margin: 0;
      background-color: #FAE0E4;
      font-family: 'Comic Sans MS', cursive;
      color: #333;
      text-align: center;
      padding: 30px;
      overflow: hidden;
    }

    h1 {
      font-size: 3em;
      margin-top: 20px;
    }

    p {
      font-size: 1.2em;
    }

    img {
      max-width: 250px;
      border-radius: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      margin: 20px 0;
    }
        .button {
            background-color: #f5f5dc;
            color: black;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
        }
        .button:hover {
            background-color: #ff1a1a;
        }
    .video-button {
      padding: 10px 20px;
      font-size: 1em;
      background-color: #FFB3C6;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .video-button:hover {
      background-color: #FF8FAB;
    }

    #videoContainer {
      display: none;
      margin-top: 20px;
    }

    /* Floating heart animation */
    .heart {
      position: absolute;
      width: 20px;
      height: 20px;
      background: red;
      transform: rotate(45deg);
      animation: float 10s ease-in;
    }

    .heart::before,
    .heart::after {
      content: "";
      position: absolute;
      width: 20px;
      height: 20px;
      background: red;
      border-radius: 50%;
    }

    .heart::before {
      top: -10px;
      left: 0;
    }

    .heart::after {
      left: -10px;
      top: 0;
    }

    @keyframes float {
      0% {
        transform: translateY(0) rotate(45deg);
        opacity: 1;
      }
      100% {
        transform: translateY(-800px) rotate(45deg);
        opacity: 0;
      }
    }
  </style>
</head>
<body>
  <h1>Happy Birthday Nasahhara! 💖</h1>
  <p>Barakallahu fii umrik, Semoga awak dipanjangkan umur dan diluaskan rezeki selalu ameeen! Selamat menyambut hari kelahiran yea. Saya mendoakan yang terbaik untuk awak! Jadi anak yang baik tau patuh taat kepada Mak, jangan melawan, sentiasa hormat mereka okay. Semoga awak sentiasa kuat hadapi ujian yang mendatang dalam kehidupan, kita sentiasa
diuji oleh yang Esa. That's means menunjukkan kita hanya manusia biasa yang kuat untuk menempuhi dugaan dalam kehidupan. Semoga sayang sentiasa kuat okay. I'm always here ! I Love You So Much Baby! ✨</p>

  <!-- Girlfriend Image -->
  <img src="IMG-20250401-WA0002.jpg" alt="My Beautiful Girlfriend" />
   <a href="FB_VID_3300536119473816444.mp4" class="button">Click Here !</a>
  <!-- Video button -->
  <br />
  <button class="video-button" onclick="showVideo()">Watch a Special Video 🎥</button>

  <!-- Video section -->
  <div id="videoContainer">
    <video width="320" height="240" controls autoplay>
      <source src="FB_VID_3300536119473816444.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <!-- Background music -->
  <audio autoplay loop>
<div style="position: absolute; left: -9999px;">
  <iframe
    width="0"
    height="0"
    src="[https://www.youtube.com/embed/0V6xMXv3Y0A?autoplay=1&loop=1&playlist=0V6xMXv3Y0A&controls=0&mute=0](https://www.youtube.com/watch?v=bp0LWCZJssw)"
    frameborder="0"
    allow="autoplay"
  ></iframe>
</div>
    Your browser does not support the audio element.
  </audio>

  <!-- Floating hearts -->
  <script>
    function showVideo() {
      document.getElementById('videoContainer').style.display = 'block';
    }

    // Create floating hearts
    function createHeart() {
      const heart = document.createElement('div');
      heart.classList.add('heart');
      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration = (5 + Math.random() * 5) + "s";
      document.body.appendChild(heart);
      setTimeout(() => {
        heart.remove();
      }, 10000);
    }

    setInterval(createHeart, 500);
  </script>
</body>
</html>
