<div class="container">
  <div class="content">
    <h1 class="title">Your Name</h1>
    <p class="subtitle">GitHub Enthusiast & Eagle Lover</p>
  </div>
  <div class="eagles">
    <svg class="eagle eagle1" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
      <path d="M50 20 L70 40 L80 35 L90 40 L80 45 L70 50 L80 55 L70 60 L50 80 L30 60 L20 55 L30 50 L20 45 L10 40 L20 35 L30 40 Z" fill="white"/>
    </svg>
    <svg class="eagle eagle2" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
      <path d="M50 20 L70 40 L80 35 L90 40 L80 45 L70 50 L80 55 L70 60 L50 80 L30 60 L20 55 L30 50 L20 45 L10 40 L20 35 L30 40 Z" fill="white"/>
    </svg>
    <svg class="eagle eagle3" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
      <path d="M50 20 L70 40 L80 35 L90 40 L80 45 L70 50 L80 55 L70 60 L50 80 L30 60 L20 55 L30 50 L20 45 L10 40 L20 35 L30 40 Z" fill="white"/>
    </svg>
  </div>
  <style>
    .container {
      width: 100%;
      height: 200px;
      background: linear-gradient(45deg, #0047AB, #4169E1, #1E90FF);
      position: relative;
      overflow: hidden;
      border-radius: 10px;
    }
    .content {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
      z-index: 2;
    }
    .title {
      font-size: 3em;
      color: #ffffff;
      margin: 0;
      font-family: Arial, sans-serif;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    }
    .subtitle {
      font-size: 1.2em;
      color: #f0f0f0;
      margin-top: 10px;
      font-family: Arial, sans-serif;
    }
    .eagles {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: 1;
    }
    .eagle {
      position: absolute;
      width: 50px;
      height: 50px;
      opacity: 0.7;
    }
    .eagle1 {
      top: 20%;
      animation: fly1 15s linear infinite;
    }
    .eagle2 {
      top: 50%;
      animation: fly2 20s linear infinite;
    }
    .eagle3 {
      top: 70%;
      animation: fly3 25s linear infinite;
    }
    @keyframes fly1 {
      0% { left: -50px; }
      100% { left: calc(100% + 50px); }
    }
    @keyframes fly2 {
      0% { right: -50px; transform: scaleX(-1); }
      100% { right: calc(100% + 50px); transform: scaleX(-1); }
    }
    @keyframes fly3 {
      0% { left: -50px; }
      100% { left: calc(100% + 50px); }
    }
  </style>
</div>
