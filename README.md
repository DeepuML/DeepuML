<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Deependra Gangwar's Portfolio</title>
  <style>
    /* Smooth transition for elements */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Arial', sans-serif;
      background-color: #111;
      color: #fff;
      line-height: 1.6;
      padding: 20px;
      transition: background-color 0.3s ease, color 0.3s ease;
    }

    h1, h3 {
      transition: transform 0.5s ease, opacity 0.5s ease;
    }

    h1 {
      text-align: center;
      font-size: 3em;
      margin-bottom: 0.5em;
    }

    h3 {
      text-align: center;
      font-size: 1.5em;
      color: #00aaff;
      margin-bottom: 2em;
    }

    .typing-effect {
      display: block;
      text-align: center;
      font-family: 'Fira Code', monospace;
      font-size: 1.5em;
      margin-bottom: 2em;
    }

    /* Typing animation */
    @keyframes typing {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }

    @keyframes blink {
      50% {
        border-color: transparent;
      }
    }

    .typing {
      display: inline-block;
      white-space: nowrap;
      overflow: hidden;
      border-right: 0.1em solid #00aaff;
      animation: typing 4s steps(40) 1s forwards, blink 0.75s step-end infinite;
    }

    /* Card hover effects for tech stack */
    .tech-stack div {
      margin: 10px;
      padding: 15px;
      background: #222;
      border-radius: 10px;
      text-align: center;
      transition: transform 0.3s ease, background-color 0.3s ease;
    }

    .tech-stack div:hover {
      transform: scale(1.05);
      background-color: #333;
    }

    /* Hover effects for social links */
    .social-links a {
      margin: 0 10px;
      transition: transform 0.3s ease, color 0.3s ease;
    }

    .social-links a:hover {
      transform: scale(1.1);
      color: #ff9800;
    }

    /* Stats section transition */
    .stats img {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .stats img:hover {
      transform: scale(1.1);
      box-shadow: 0 0 15px rgba(0, 172, 255, 0.5);
    }

    /* General fade-in effect */
    .fade-in {
      opacity: 0;
      animation: fadeIn 1s forwards;
    }

    @keyframes fadeIn {
      to {
        opacity: 1;
      }
    }
  </style>
</head>
<body>
  <h1 class="fade-in">Hi 👋, I'm Deependra Gangwar</h1>
  <h3 class="fade-in">🚀 AI | ML | DL | NLP | Blockchain | Full-Stack | DevOps | Big - data | Research</h3>

  <p class="typing-effect">
    <span class="typing">AI Researcher | Full-Stack Developer | Blockchain Innovator | Data Enthusiast | Always Learning ✨ Always Building 🚀</span>
  </p>

  <hr>

  <div class="about-me fade-in">
    <h2>🧠 About Me</h2>
    <ul>
      <li>🎓 Pre-Final year student passionate about <strong>innovative problem-solving using AI</strong></li>
      <li>💡 Currently working on:
        <ul>
          <li>Malware detection via UI behavior (Computer Vision)</li>
          <li>Real-time crypto market trend prediction</li>
          <li>Smart contract NLP & AI-based decentralized platforms</li>
        </ul>
      </li>
      <li>🛠️ Exploring <strong>Generative AI, Web3, Docker, and MLOps</strong></li>
      <li>✍️ Research Published in <strong>Hindawi International Conference of NLP</strong></li>
    </ul>
  </div>

  <hr>

  <div class="tech-stack fade-in">
    <h2>🛠️ Tech Stack</h2>
    <div class="languages">
      <h3>👨‍💻 Languages</h3>
      <div>
        <img src="https://img.shields.io/badge/-Python-000?&logo=Python" />
        <img src="https://img.shields.io/badge/-C++-000?&logo=C%2B%2B" />
        <img src="https://img.shields.io/badge/-Go-000?&logo=Go" />
      </div>
    </div>
    <div class="libraries-frameworks">
      <h3>📚 Libraries/Frameworks</h3>
      <div>
        <img src="https://img.shields.io/badge/-TensorFlow-000?&logo=TensorFlow" />
        <img src="https://img.shields.io/badge/-Pandas-000?&logo=pandas" />
        <img src="https://img.shields.io/badge/-NumPy-000?&logo=numpy" />
        <img src="https://img.shields.io/badge/-Flask-000?&logo=flask" />
        <img src="https://img.shields.io/badge/-Angular-000?&logo=angular" />
        <img src="https://img.shields.io/badge/-Node.js-000?&logo=node.js" />
      </div>
    </div>
    <div class="devops-tools">
      <h3>☁️ DevOps / Tools</h3>
      <div>
        <img src="https://img.shields.io/badge/-Docker-000?&logo=docker" />
        <img src="https://img.shields.io/badge/-Kubernetes-000?&logo=kubernetes" />
        <img src="https://img.shields.io/badge/-VS%20Code-000?&logo=visual-studio-code" />
        <img src="https://img.shields.io/badge/-GitHub-000?&logo=github" />
      </div>
    </div>
  </div>

  <hr>

  <div class="projects fade-in">
    <h2>🚀 Projects Highlights</h2>
    <table>
      <tr>
        <td>🛡️ Malware Detection</td>
        <td>Computer Vision, CNN</td>
        <td>Detects Trojan-like behavior using GUI snapshots</td>
      </tr>
      <tr>
        <td>💰 Crypto Trend Prediction</td>
        <td>Clustering, Unsupervised ML</td>
        <td>Predicts crypto volatility (DOGE, BTC, ETH)</td>
      </tr>
      <tr>
        <td>🤖 JARVIS AI Assistant</td>
        <td>Python, NLP</td>
        <td>Personal voice-enabled AI agent</td>
      </tr>
      <tr>
        <td>📦 AI + Smart Contracts</td>
        <td>Web3, Solidity, NLP</td>
        <td>Generates & verifies smart contracts using AI</td>
      </tr>
    </table>
  </div>

  <hr>

  <div class="stats">
    <h2>📈 GitHub Stats</h2>
    <div>
      <img src="https://github-readme-stats.vercel.app/api?username=DeepuML&show_icons=true&theme=tokyonight" height="180"/>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DeepuML&layout=compact&theme=tokyonight" height="180"/>
    </div>
    <div>
      <img src="https://streak-stats.demolab.com?user=DeepuML&theme=tokyonight" height="160"/>
    </div>
  </div>

  <hr>

  <div class="contact fade-in">
    <h2>📬 Let's Connect</h2>
    <div class="social-links">
      <a href="mailto:deependragangwar.dev@gmail.com"><img src="https://img.shields.io/badge/Gmail-%2312100E.svg?style=for-the-badge&logo=Gmail&logoColor=white" /></a>
      <a href="https://www.linkedin.com/in/deependra-gangwar/"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=LinkedIn&logoColor=white" /></a>
    </div>
  </div>

  <hr>

  <div class="quote fade-in">
    <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" />
  </div>

  <hr>

  <div class="news fade-in">
    <h2>🆕 What's New?</h2>
    <ul>
      <li>🚀 Launched a **real-time sentiment analysis dashboard** with HuggingFace Transformers.</li>
      <li>🧠 Published research on **Language Identification in Code-Switching Text** at Hindawi NLP Conference.</li>
      <li>🧪 Experimenting with **Vision-based Malware Detection** using GUI behavior tracking.</li>
      <li>📦 Building a **JARVIS-like AI assistant** that speaks, sees, and codes 🤖.</li>
    </ul>
  </div>

  <hr>

  <div class="certifications fade-in">
    <h2>🎓 Certifications & Achievements</h2>
    <ul>
      <li>🥇 Google Data Analytics Professional Certificate</li>
      <li>🧠 DeepLearning.AI: Neural Networks and Deep Learning</li>
      <li>📊 Microsoft Certified: Data Fundamentals</li>
      <li>🧬 IBM AI Engineering Specialization</li>
      <li>💥 Finalist - Dr Code Hackathon</li>
    </ul>
  </div>

  <hr>

  <div class="talks fade-in">
    <h2>🎙️ Featured Talks & Research</h2>
    <ul>
      <li>🧾 *Language Identification in Code-Switching Social Media Text* - Hindawi NLP Conference 2024</li>
      <li>📊 *Unsupervised Market Clustering in Crypto Prediction* - Techniques: DOGE, KMeans, DBSCAN</li>
    </ul>
  </div>

  <hr>

  <div class="learning fade-in">
    <h2>🌱 Currently Learning</h2>
    <ul>
      <li>🔐 Zero-Knowledge Proofs and Blockchain Scaling</li>
      <li>🧬 Generative AI for Design & Manufacturing</li>
      <li>☁️ MLOps, CI/CD pipelines with Docker & Kubernetes</li>
      <li>⚙️ LangChain + Vector Databases for RAG systems</li>
    </ul>
  </div>

  <hr>

  <div class="thanks fade-in">
    <h2>🙏 Thanks for visiting!</h2>
    <img src="https://media.giphy.com/media/3o7abB06u9bNzA8lu8/giphy.gif" width="200"/>
    <p><i>“Dream Big. Build Bigger.”</i></p>
  </div>
</body>
</html>
