<div align="center">
<!-- Animated Banner SVG -->
<svg viewBox="0 0 800 450" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0d1117">
        <animate attributeName="stop-color" values="#0d1117;#161b22;#0d1117" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#161b22">
        <animate attributeName="stop-color" values="#161b22;#21262d;#161b22" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#0d1117">
        <animate attributeName="stop-color" values="#0d1117;#1a1f2e;#0d1117" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="2.5" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <rect width="800" height="450" fill="url(#bgGrad)"/>
  <g opacity="0.08" stroke="#58a6ff" stroke-width="0.5">
    <line x1="0" y1="100" x2="800" y2="100">
      <animate attributeName="x1" values="0;800;0" dur="20s" repeatCount="indefinite"/>
      <animate attributeName="x2" values="800;0;800" dur="20s" repeatCount="indefinite"/>
    </line>
    <line x1="0" y1="200" x2="800" y2="200">
      <animate attributeName="x1" values="800;0;800" dur="25s" repeatCount="indefinite"/>
      <animate attributeName="x2" values="0;800;0" dur="25s" repeatCount="indefinite"/>
    </line>
    <line x1="0" y1="300" x2="800" y2="300">
      <animate attributeName="x1" values="0;800;0" dur="22s" repeatCount="indefinite"/>
      <animate attributeName="x2" values="800;0;800" dur="22s" repeatCount="indefinite"/>
    </line>
    <line x1="200" y1="0" x2="200" y2="450">
      <animate attributeName="y1" values="0;450;0" dur="18s" repeatCount="indefinite"/>
      <animate attributeName="y2" values="450;0;450" dur="18s" repeatCount="indefinite"/>
    </line>
    <line x1="400" y1="0" x2="400" y2="450">
      <animate attributeName="y1" values="450;0;450" dur="24s" repeatCount="indefinite"/>
      <animate attributeName="y2" values="0;450;0" dur="24s" repeatCount="indefinite"/>
    </line>
    <line x1="600" y1="0" x2="600" y2="450">
      <animate attributeName="y1" values="0;450;0" dur="19s" repeatCount="indefinite"/>
      <animate attributeName="y2" values="450;0;450" dur="19s" repeatCount="indefinite"/>
    </line>
  </g>
  <g fill="#58a6ff" opacity="0.3">
    <circle cx="100" cy="400" r="2">
      <animate attributeName="cy" values="400;50;400" dur="12s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.6;0" dur="12s" repeatCount="indefinite"/>
    </circle>
    <circle cx="250" cy="420" r="1.5">
      <animate attributeName="cy" values="420;30;420" dur="15s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.5;0" dur="15s" repeatCount="indefinite"/>
    </circle>
    <circle cx="400" cy="410" r="2.5">
      <animate attributeName="cy" values="410;40;410" dur="10s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.7;0" dur="10s" repeatCount="indefinite"/>
    </circle>
    <circle cx="550" cy="430" r="1.8">
      <animate attributeName="cy" values="430;60;430" dur="14s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.4;0" dur="14s" repeatCount="indefinite"/>
    </circle>
    <circle cx="700" cy="400" r="2.2">
      <animate attributeName="cy" values="400;80;400" dur="11s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.6;0" dur="11s" repeatCount="indefinite"/>
    </circle>
    <circle cx="150" cy="440" r="1.2">
      <animate attributeName="cy" values="440;20;440" dur="16s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.5;0" dur="16s" repeatCount="indefinite"/>
    </circle>
    <circle cx="650" cy="450" r="1.6">
      <animate attributeName="cy" values="450;70;450" dur="13s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.5;0" dur="13s" repeatCount="indefinite"/>
    </circle>
    <circle cx="50" cy="410" r="2">
      <animate attributeName="cy" values="410;90;410" dur="17s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.6;0" dur="17s" repeatCount="indefinite"/>
    </circle>
    <circle cx="750" cy="420" r="1.4">
      <animate attributeName="cy" values="420;100;420" dur="14s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.4;0" dur="14s" repeatCount="indefinite"/>
    </circle>
    <circle cx="300" cy="440" r="2.3">
      <animate attributeName="cy" values="440;50;440" dur="12s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.7;0" dur="12s" repeatCount="indefinite"/>
    </circle>
  </g>
  <g stroke="#58a6ff" stroke-width="2" fill="none" opacity="0.6">
    <path d="M 40 40 L 40 70 L 70 70">
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="4s" repeatCount="indefinite"/>
    </path>
    <path d="M 760 40 L 760 70 L 730 70">
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="4s" begin="1s" repeatCount="indefinite"/>
    </path>
    <path d="M 40 410 L 40 380 L 70 380">
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="4s" begin="2s" repeatCount="indefinite"/>
    </path>
    <path d="M 760 410 L 760 380 L 730 380">
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="4s" begin="3s" repeatCount="indefinite"/>
    </path>
  </g>
  <g transform="translate(400, 140)" text-anchor="middle">
    <text font-family="'Segoe UI', 'Helvetica Neue', sans-serif" font-size="42" font-weight="bold" fill="#e6edf3" filter="url(#glow)">
      Bhabani Shankar Rath
      <animate attributeName="opacity" values="0;1" dur="1.5s" fill="freeze"/>
    </text>
    <line x1="-220" y1="15" x2="220" y2="15" stroke="#58a6ff" stroke-width="2" opacity="0">
      <animate attributeName="x2" values="-220;220" dur="1.5s" begin="1s" fill="freeze"/>
      <animate attributeName="opacity" values="0;1" dur="0.5s" begin="1s" fill="freeze"/>
    </line>
  </g>
  <g transform="translate(400, 195)" text-anchor="middle">
    <text font-family="'Segoe UI', 'Helvetica Neue', sans-serif" font-size="20" fill="#8b949e">
      <animate attributeName="opacity" values="0;1" dur="1s" begin="1.8s" fill="freeze"/>
      Passionate Frontend Developer
    </text>
  </g>
  <g transform="translate(400, 235)" text-anchor="middle">
    <rect x="-140" y="-14" width="280" height="28" rx="14" fill="#238636" opacity="0">
      <animate attributeName="opacity" values="0;0.15" dur="0.5s" begin="2.2s" fill="freeze"/>
    </rect>
    <text font-family="'Segoe UI', monospace" font-size="14" fill="#3fb950" font-weight="600">
      <animate attributeName="opacity" values="0;1" dur="0.8s" begin="2.4s" fill="freeze"/>
      215+ Design Systems Expertise
    </text>
  </g>
  <g transform="translate(400, 290)" text-anchor="middle">
    <text font-family="'Segoe UI', monospace" font-size="13" fill="#8b949e">
      <animate attributeName="opacity" values="0;1" dur="0.8s" begin="2.8s" fill="freeze"/>
      <tspan x="0" dy="0">🔭 Currently at </tspan>
      <tspan fill="#58a6ff" font-weight="bold">Raccoon Studio</tspan>
      <tspan> — Building scalable, responsive &amp; professional UI</tspan>
    </text>
  </g>
  <g transform="translate(400, 320)" text-anchor="middle">
    <text font-family="'Segoe UI', monospace" font-size="13" fill="#8b949e">
      <animate attributeName="opacity" values="0;1" dur="0.8s" begin="3.2s" fill="freeze"/>
      <tspan x="0" dy="0">🌱 Learning </tspan>
      <tspan fill="#d29922" font-weight="bold">Node.js</tspan>
      <tspan> &amp; </tspan>
      <tspan fill="#d29922" font-weight="bold">React Native</tspan>
    </text>
    <circle cx="155" cy="-5" r="3" fill="#d29922" opacity="0">
      <animate attributeName="opacity" values="0;1;0" dur="2s" begin="4s" repeatCount="indefinite"/>
      <animate attributeName="r" values="2;5;2" dur="2s" begin="4s" repeatCount="indefinite"/>
    </circle>
  </g>
  <g transform="translate(0, 370)">
    <rect x="50" y="0" width="700" height="30" fill="#161b22" opacity="0.5" rx="4"/>
    <g font-family="'Segoe UI', monospace" font-size="12" fill="#c9d1d9">
      <text x="800" y="20">
        <tspan fill="#e34c26">HTML</tspan> • 
        <tspan fill="#264de4">CSS</tspan> • 
        <tspan fill="#f7df1e">JavaScript</tspan> • 
        <tspan fill="#61dafb">React</tspan> • 
        <tspan fill="#38bdf8">Tailwind</tspan> • 
        <tspan fill="#7952b3">Bootstrap</tspan> • 
        <tspan fill="#68a063">Node.js</tspan> • 
        <tspan fill="#47a248">MongoDB</tspan> • 
        <tspan fill="#00758f">MySQL</tspan> • 
        <tspan fill="#3178c6">TypeScript</tspan> • 
        <tspan fill="#e34c26">HTML</tspan> • 
        <tspan fill="#264de4">CSS</tspan> • 
        <tspan fill="#f7df1e">JavaScript</tspan> • 
        <tspan fill="#61dafb">React</tspan> • 
        <tspan fill="#38bdf8">Tailwind</tspan> • 
        <tspan fill="#7952b3">Bootstrap</tspan> • 
        <tspan fill="#68a063">Node.js</tspan> • 
        <tspan fill="#47a248">MongoDB</tspan> • 
        <tspan fill="#00758f">MySQL</tspan> • 
        <tspan fill="#3178c6">TypeScript</tspan>
        <animateTransform attributeName="transform" type="translate" from="0 0" to="-800 0" dur="20s" repeatCount="indefinite"/>
      </text>
    </g>
  </g>
  <g transform="translate(400, 425)" text-anchor="middle" font-family="'Segoe UI', monospace" font-size="11" fill="#8b949e">
    <animate attributeName="opacity" values="0;1" dur="1s" begin="4s" fill="freeze"/>
    <text y="0">
      <tspan fill="#58a6ff">GitHub</tspan> • 
      <tspan fill="#58a6ff">LinkedIn</tspan> • 
      <tspan fill="#58a6ff">Instagram</tspan> • 
      <tspan fill="#58a6ff">Portfolio</tspan> • 
      <tspan fill="#58a6ff">bhabanishankarr21@gmail.com</tspan>
    </text>
  </g>
  <g transform="translate(400, 445)" text-anchor="middle">
    <text font-family="'Segoe UI', monospace" font-size="10" fill="#6e7681" font-style="italic">
      <animate attributeName="opacity" values="0;1" dur="1s" begin="4.5s" fill="freeze"/>
      ⚡ Fun fact: I think I can learn a tech in a single day.
    </text>
  </g>
  <g transform="translate(565, 140)">
    <rect x="0" y="-25" width="3" height="35" fill="#58a6ff" opacity="0">
      <animate attributeName="opacity" values="0;0;1;1" dur="1s" begin="2.5s" repeatCount="indefinite" calcMode="discrete"/>
    </rect>
  </g>
  <line x1="0" y1="2" x2="800" y2="2" stroke="#58a6ff" stroke-width="2" opacity="0.3">
    <animate attributeName="x1" values="0;800;0" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.1;0.5;0.1" dur="4s" repeatCount="indefinite"/>
  </line>
  <line x1="0" y1="448" x2="800" y2="448" stroke="#58a6ff" stroke-width="2" opacity="0.3">
    <animate attributeName="x2" values="800;0;800" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.1;0.5;0.1" dur="4s" begin="2s" repeatCount="indefinite"/>
  </line>
</svg>
<!-- Profile Views Counter -->
<img src="https://komarev.com/ghpvc/?username=bhabani-rath&label=Profile%20views&color=0e75b6&style=flat" alt="bhabani-rath" />
</div>
🏆 GitHub Trophies
<p align="left">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=bhabani-rath&theme=darkhub&no-frame=true&margin-w=15" alt="bhabani-rath" />
  </a>
</p>
👨‍💻 About Me
🔭 I'm currently working on Raccoon Studio as a Software Engineer to build scalable, responsive and professional UI design and Frontend Development.
🌱 I'm currently learning Node.js for gaining expertise in Backend Development and React Native for Mobile Development.
💬 Ask me about Web Development — HTML, CSS, JavaScript, Bootstrap, Tailwind, React, React Native
📫 How to reach me: bhabanishankarr21@gmail.com
⚡ Fun fact: I think I can learn a tech in a single day.
👨‍💻 All of my projects are available at https://portfolio-bhabani-v3.vercel.app/
📝 I regularly write articles on https://portfolio-bhabani-v3.vercel.app/blogs
📄 Know about my experiences Resume
🌐 Connect with Me
<p align="left">
  <a href="https://github.com/bhabani-rath" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" alt="GitHub" height="30" width="40" />
  </a>
  <a href="https://linkedin.com/in/bhabani-shankar-rath-5754b1250" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" />
  </a>
  <a href="https://instagram.com/bhabani_shankar_rath" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="30" width="40" />
  </a>
</p>
🛠️ Languages and Tools
<p align="left">
  <a href="https://getbootstrap.com" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=bootstrap" alt="bootstrap" width="40" height="40"/>
  </a>
  <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=css" alt="css3" width="40" height="40"/>
  </a>
  <a href="https://expressjs.com" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=express" alt="express" width="40" height="40"/>
  </a>
  <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=html" alt="html5" width="40" height="40"/>
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=js" alt="javascript" width="40" height="40"/>
  </a>
  <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=mongodb" alt="mongodb" width="40" height="40"/>
  </a>
  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=mysql" alt="mysql" width="40" height="40"/>
  </a>
  <a href="https://nodejs.org" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=nodejs" alt="nodejs" width="40" height="40"/>
  </a>
  <a href="https://www.oracle.com/" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/>
  </a>
  <a href="https://postman.com" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=postman" alt="postman" width="40" height="40"/>
  </a>
  <a href="https://reactjs.org/" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=react" alt="react" width="40" height="40"/>
  </a>
  <a href="https://reactnative.dev/" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=react" alt="reactnative" width="40" height="40"/>
  </a>
  <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=tailwind" alt="tailwind" width="40" height="40"/>
  </a>
  <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer">
    <img src="https://skillicons.dev/icons?i=ts" alt="typescript" width="40" height="40"/>
  </a>
</p>
📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bhabani-rath&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub Stats" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bhabani-rath&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages" height="170" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=bhabani-rath&theme=github-dark-blue&hide_border=true" alt="GitHub Streak" />
</p>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=58a6ff&height=100&section=footer&text=Thanks%20for%20visiting!&fontSize=24&fontColor=e6edf3&animation=fadeIn" />
</div>
