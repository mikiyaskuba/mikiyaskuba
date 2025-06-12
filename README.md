<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Miko Kuba | README</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #0d0d0d;
      color: #fff;
      overflow: hidden;
    }
    #particles-js {
      position: absolute;
      width: 100%;
      height: 100%;
      z-index: 0;
    }
    .content {
      position: relative;
      z-index: 1;
      padding: 4rem;
      max-width: 800px;
      margin: 0 auto;
      text-align: center;
      background: rgba(0,0,0,0.5);
      border-radius: 20px;
    }
    h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
      background: linear-gradient(90deg, #00eaff, #ff00cc);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    p {
      font-size: 1.2rem;
      line-height: 1.6;
    }
    .tagline {
      font-style: italic;
      color: #aaa;
    }
  </style>
</head>
<body>
  <div id="particles-js"></div>
  <div class="content">
    <h1>Miko Kuba 🚀</h1>
    <p class="tagline">Code Alchemist · Dream Hacker · Ox Whisperer</p>
    <p>
      From the highlands of Ethiopia to the heart of the internet,<br>
      I'm building a universe of tech, culture, and wild innovation.<br><br>
      I build apps that digitize cattle, connect humans through AI-powered skill barter,
      and even write poetry in code.<br><br>
      ⚡️ I'm not just a coder — I'm a movement.<br>
      💡 If it sounds impossible, that’s when I know I’m close.<br>
    </p>
  </div>
  <script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
  <script>
    particlesJS("particles-js", {
      "particles": {
        "number": { "value": 80 },
        "color": { "value": "#ffffff" },
        "shape": { "type": "circle" },
        "opacity": { "value": 0.5 },
        "size": { "value": 3 },
        "line_linked": { "enable": true, "distance": 150, "color": "#ffffff", "opacity": 0.4, "width": 1 },
        "move": { "enable": true, "speed": 2 }
      },
      "interactivity": {
        "detect_on": "canvas",
        "events": { "onhover": { "enable": true, "mode": "repulse" } },
        "modes": { "repulse": { "distance": 100 } }
      },
      "retina_detect": true
    });
  </script>
</body>
</html>
