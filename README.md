<div align="center">
  <style>
    @keyframes wave {
      0% { transform: rotate(0deg); }
      10% { transform: rotate(14deg); }
      20% { transform: rotate(-8deg); }
      30% { transform: rotate(14deg); }
      40% { transform: rotate(-4deg); }
      50% { transform: rotate(10deg); }
      60% { transform: rotate(0deg); }
      100% { transform: rotate(0deg); }
    }
    
    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }
    
    @keyframes blink {
      50% { border-color: transparent; }
    }
    
    @keyframes float {
      0%, 100% { transform: translateY(0px); }
      50% { transform: translateY(-10px); }
    }
    
    @keyframes glow {
      0%, 100% { box-shadow: 0 0 5px #00ff88; }
      50% { box-shadow: 0 0 20px #00ff88, 0 0 30px #00ff88; }
    }
    
    @keyframes gradient {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    
    .wave {
      animation: wave 2s linear infinite;
      transform-origin: 70% 70%;
      display: inline-block;
    }
    
    .typing-animation {
      overflow: hidden;
      border-right: 3px solid #00ff88;
      white-space: nowrap;
      margin: 0 auto;
      animation: typing 3s steps(40, end), blink 0.75s step-end infinite;
      font-family: 'Courier New', monospace;
    }
    
    .floating {
      animation: float 3s ease-in-out infinite;
    }
    
    .glow-effect {
      animation: glow 2s ease-in-out infinite alternate;
      border-radius: 10px;
      padding: 10px;
      margin: 5px;
      display: inline-block;
    }
    
    .gradient-text {
      background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
      background-size: 400% 400%;
      animation: gradient 3s ease infinite;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      font-weight: bold;
      font-size: 3em;
    }
    
    .tech-stack {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
      margin: 20px 0;
    }
    
    .tech-item {
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: white;
      padding: 10px 20px;
      border-radius: 25px;
      font-weight: bold;
      transition: all 0.3s ease;
      animation: float 4s ease-in-out infinite;
    }
    
    .tech-item:hover {
      transform: scale(1.1) translateY(-5px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.3);
    }
    
    .stats-container {
      background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
      border-radius: 15px;
      padding: 20px;
      margin: 20px 0;
      box-shadow: 0 8px 32px rgba(0,0,0,0.3);
    }
    
    .profile-container {
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      border-radius: 20px;
      padding: 30px;
      margin: 20px;
      box-shadow: 0 15px 35px rgba(0,0,0,0.3);
      backdrop-filter: blur(10px);
    }
    
    .social-links {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 20px 0;
    }
    
    .social-item {
      transition: all 0.3s ease;
      filter: grayscale(0%);
    }
    
    .social-item:hover {
      transform: scale(1.2) rotate(5deg);
      filter: brightness(1.2);
    }
    
    .animated-border {
      border: 3px solid;
      border-image: linear-gradient(45deg, #ff6b6b, #4ecdc4, #45b7d1, #96ceb4, #ffeaa7) 1;
      animation: gradient 3s ease infinite;
      border-radius: 15px;
      padding: 20px;
      margin: 20px 0;
    }
  </style>

  <div class="profile-container">
    <h1 class="gradient-text">Привет! <span class="wave">👋</span></h1>
    
    <div class="typing-animation">
      <h2>Я Frontend/Backend разработчик</h2>
    </div>
    
    <div class="floating">
      <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00FF88&center=true&vCenter=true&width=435&lines=Добро+пожаловать+в+мой+профиль!;Создаю+крутые+веб-приложения;Изучаю+новые+технологии+каждый+день" alt="Typing SVG" />
    </div>
  </div>

  <div class="animated-border">
    <h2>🚀 Мой технологический стек</h2>
    <div class="tech-stack">
      <div class="tech-item glow-effect">HTML5</div>
      <div class="tech-item glow-effect">CSS3</div>
      <div class="tech-item glow-effect">JavaScript</div>
      <div class="tech-item glow-effect">React</div>
      <div class="tech-item glow-effect">Node.js</div>
      <div class="tech-item glow-effect">Python</div>
      <div class="tech-item glow-effect">Git</div>
      <div class="tech-item glow-effect">MongoDB</div>
    </div>
  </div>

  <div class="stats-container">
    <h2 style="color: white; margin-bottom: 20px;">📊 GitHub Статистика</h2>
    <div class="floating">
      <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=00FF88&icon_color=00FF88&text_color=FFFFFF" alt="GitHub Stats" />
    </div>
    <br>
    <div class="floating" style="animation-delay: 0.5s;">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=radical&hide_border=true&background=0D1117&stroke=00FF88&ring=00FF88&fire=FF6B6B&currStreakLabel=00FF88" alt="GitHub Streak" />
    </div>
    <br>
    <div class="floating" style="animation-delay: 1s;">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=00FF88&text_color=FFFFFF" alt="Top Languages" />
    </div>
  </div>

  <div class="animated-border">
    <h2>🌟 Особенности</h2>
    <div style="display: flex; justify-content: space-around; flex-wrap: wrap; margin: 20px 0;">
      <div class="glow-effect" style="background: linear-gradient(135deg, #ff6b6b, #ee5a24); color: white; padding: 15px; border-radius: 10px; margin: 10px;">
        <h3>💻 Frontend</h3>
        <p>Создаю красивые интерфейсы</p>
      </div>
      <div class="glow-effect" style="background: linear-gradient(135deg, #4ecdc4, #44bd32); color: white; padding: 15px; border-radius: 10px; margin: 10px;">
        <h3>⚙️ Backend</h3>
        <p>Разрабатываю серверную логику</p>
      </div>
      <div class="glow-effect" style="background: linear-gradient(135deg, #45b7d1, #3742fa); color: white; padding: 15px; border-radius: 10px; margin: 10px;">
        <h3>📱 Mobile</h3>
        <p>Адаптивные приложения</p>
      </div>
    </div>
  </div>

  <div class="social-links">
    <h2>🤝 Связаться со мной</h2>
  </div>
  
  <div class="social-links">
    <a href="https://linkedin.com/in/YOUR_LINKEDIN" class="social-item">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://twitter.com/YOUR_TWITTER" class="social-item">
      <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" />
    </a>
    <a href="mailto:your.email@example.com" class="social-item">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://t.me/YOUR_TELEGRAM" class="social-item">
      <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
    </a>
  </div>

  <div class="floating">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=react-dark&bg_color=0D1117&color=00FF88&line=00FF88&point=FFFFFF&area=true&hide_border=true" alt="Activity Graph" />
  </div>

  <div class="animated-border">
    <h2>🏆 Достижения</h2>
    <div class="floating">
      <img src="https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=radical&no-frame=true&no-bg=true&margin-w=4&row=1" alt="Trophies" />
    </div>
  </div>

  <div style="margin: 30px 0;">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer&text=Спасибо%20за%20визит!&fontSize=30&fontAlignY=70&desc=Давайте%20создадим%20что-то%20потрясающее%20вместе!&descAlignY=88&descAlign=50" alt="Footer" />
  </div>

  <div class="glow-effect" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 20px; border-radius: 15px; margin: 20px 0;">
    <h3>💡 Интересный факт</h3>
    <p>Я верю, что код - это поэзия, а программирование - это искусство!</p>
  </div>

  <div style="margin-top: 30px;">
    <img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&label=Просмотры%20профиля&color=0e75b6&style=flat" alt="Profile Views" />
  </div>

</div>
```

Этот README профиль включает в себя:

🎨 **Анимации:**
- Машущая рука
- Печатающийся текст
- Плавающие элементы
- Светящиеся эффекты
- Градиентные переходы

✨ **Особенности:**
- Красивые градиентные фоны
- Анимированные границы
- Интерактивные элементы при наведении
- Адаптивный дизайн
- Статистика GitHub
- Социальные ссылки

📝 **Что нужно изменить:**
1. Замените `YOUR_USERNAME` на ваш GitHub username
2. Обновите ссылки на социальные сети
3. Измените email адрес
4. Добавьте свои технологии в стек

Просто скопируйте этот код в файл `README.md` в репозитории с именем вашего GitHub username (например, `username/username`), и у вас будет красивый анимированный профиль!

