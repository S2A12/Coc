<p align="center">
<svg width="600" height="150" xmlns="http://www.w3.org/2000/svg">
  <style>
    .main {
      font: 700 64px 'Orbitron', monospace;
      fill: #00eaff;
      letter-spacing: 10px;
      animation: flicker 2s infinite;
    }
    .glitch1, .glitch2 {
      font: 700 64px 'Orbitron', monospace;
      letter-spacing: 10px;
      opacity: 0.35;
      animation: glitch 1s infinite;
    }
    .glitch1 { fill: #ff00f7; }
    .glitch2 { fill: #fcee0c; }
    @keyframes flicker {
      0% { opacity: 1; }
      10% { opacity: 0.95; }
      20% { opacity: 1; }
      30% { opacity: 0.98; }
      40% { opacity: 1; }
      50% { opacity: 0.96; }
      100% { opacity: 1; }
    }
    @keyframes glitch {
      0% { transform: translate(0,0); }
      20% { transform: translate(-2px, 2px); }
      40% { transform: translate(2px, -2px); }
      60% { transform: translate(-1px, 1px); }
      80% { transform: translate(1px, -1px); }
      100% { transform: translate(0,0); }
    }
  </style>

  <!-- glitch layers -->
  <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" class="glitch1">N1H4D</text>
  <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" class="glitch2">N1H4D</text>

  <!-- main neon text -->
  <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" class="main">N1H4D</text>
</svg>
</p>
