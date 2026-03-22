<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Ucapan Ulang Tahun</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      overflow: hidden;
    }

    .container {
      display: flex;
      width: 300%;
      transition: transform 0.5s ease-in-out;
    }

    .slide {
      width: 100%;
      height: 100vh;
      flex-shrink: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      font-size: 24px;
      padding: 20px;
    }

    .slide:nth-child(1) { background: #ffb6c1; }
    .slide:nth-child(2) { background: #87cefa; }
    .slide:nth-child(3) { background: #98fb98; }

    button {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      font-size: 20px;
      padding: 10px 15px;
      border: none;
      background: black;
      color: white;
      cursor: pointer;
    }

    #prev { left: 10px; }
    #next { right: 10px; }
  </style>
</head>
<body>

<div class="container" id="slides">
  <div class="slide">
    <div>
      <h1>Bukaa Akoo 😆</h1>
    </div>
  </div>

  <div class="slide">
    <div>
      <h1>🎉 Selamat Ulang Tahun Kak Handi 🎉</h1>
      <p>Semoga selalu ke Dubai ✈️</p>
      <p>Bolehla coklat Dubai jugo hehe 🍫😄</p>
    </div>
  </div>

  <div class="slide">
    <div>
      <h1>😆 BTW</h1>
      <p>Aku baru nian tau buat ini wkwk</p>
      <p>Hal baru ini biso main coding 💻🔥</p>
    </div>
  </div>
</div>

<button id="prev">⬅</button>
<button id="next">➡</button>

<script>
  let index = 0;
  const slides = document.getElementById("slides");

  document.getElementById("next").onclick = () => {
    if (index < 2) {
      index++;
      slides.style.transform = `translateX(-${index * 100}%)`;
    }
  };

  document.getElementById("prev").onclick = () => {
    if (index > 0) {
      index--;
      slides.style.transform = `translateX(-${index * 100}%)`;
    }
  };
</script>

</body>
</html>
