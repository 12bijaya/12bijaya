<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bijaya Kumal - Hacker Portfolio</title>
  <style>
    body {
      background-color: #1a1a1a;
      color: #0f0;
      font-family: 'Courier New', monospace;
      margin: 0;
      padding: 20px;
      overflow-x: hidden;
    }
    .terminal {
      background: #000;
      border: 2px solid #0f0;
      padding: 20px;
      max-width: 800px;
      margin: 0 auto;
      height: 300px;
      overflow: hidden;
      position: relative;
    }
    .terminal::before {
      content: '$ ';
      color: #0f0;
      position: absolute;
      left: 10px;
    }
    #terminal-text {
      display: inline-block;
      margin-left: 30px;
      white-space: pre-wrap;
      animation: typing 4s steps(30) forwards, blink-caret 0.75s step-end infinite;
    }
    .profile-content {
      max-width: 800px;
      margin: 20px auto;
      opacity: 0;
      transition: opacity 1s ease-in;
    }
    .profile-content.visible {
      opacity: 1;
    }
    h1, h2, h3 {
      color: #0f0;
    }
    a {
      color: #0f0;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .badges img {
      margin: 5px;
    }
    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }
    @keyframes blink-caret {
      from, to { border-right-color: transparent; }
      50% { border-right-color: #0f0; }
    }
    #terminal-text::after {
      content: '|';
      position: absolute;
      right: 0;
      border-right: 2px solid #0f0;
      animation: blink-caret 0.75s step-end infinite;
    }
  </style>
</head>
<body>
  <div class="terminal">
    <div id="terminal-text"></div>
  </div>
  <div class="profile-content">
    <h1>💫 About Me:</h1>
    <p>🛡️ Studying by day, 🕵️‍♂️ breaking things by night 😈</p>
    <p>🚩 Love playing <strong>CTFs</strong> & solving challenges</p>
    <p>💻 Languages I tinker with: Python 🐍, C/C++, Assembly ⚙️</p>
    <p>🌐 Interested in: Networking 🌍 | Exploits 💥 | Reverse Engineering 🔄 | Binary Exploitation 🔐</p>
    <p>📚 Always learning, always curious 🚀</p>

    <h2>🌐 Socials:</h2>
    <div class="badges">
      <a href="https://discord.gg/1320268411581763627"><img src="https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white" alt="Discord"></a>
      <a href="https://linkedin.com/in/Bijaya Kumal"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
      <a href="https://medium.com/@1conic"><img src="https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white" alt="Medium"></a>
    </div>

    <h2>💻 Tech Stack:</h2>
    <div class="badges">
      <img src="https://img.shields.io/badge/assembly%20script-%23000000.svg?style=for-the-badge&logo=assemblyscript&logoColor=white" alt="AssemblyScript">
      <img src="https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white" alt="C">
      <img src="https://img.shields.io/badge/c++-%2300599C.svg?style-for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++">
      <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
      <img src="https://img.shields.io/badge/css3-%231572B6.svg?style-for-the-badge&logo=css3&logoColor=white" alt="CSS3">
      <img src="https://img.shields.io/badge/bash_script-%23121011.svg?style-for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash Script">
      <img src="https://img.shields.io/badge/PowerShell-%235391FE.svg?style-for-the-badge&logo=powershell&logoColor=white" alt="PowerShell">
      <img src="https://img.shields.io/badge/javascript-%23323330.svg?style-for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript">
      <img src="https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style-for-the-badge&logo=windows-terminal&logoColor=white" alt="Windows Terminal">
      <img src="https://img.shields.io/badge/react-%2320232a.svg?style-for-the-badge&logo=react&logoColor=%2361DAFB" alt="React">
      <img src="https://img.shields.io/badge/node.js-6DA55F?style-for-the-badge&logo=node.js&logoColor=white" alt="NodeJS">
      <img src="https://img.shields.io/badge/NODEMON-%23323330.svg?style-for-the-badge&logo=nodemon&logoColor=%BBDEAD" alt="Nodemon">
      <img src="https://img.shields.io/badge/Canva-%2300C4CC.svg?style-for-the-badge&logo=Canva&logoColor=white" alt="Canva">
      <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style-for-the-badge&logo=figma&logoColor=white" alt="Figma">
      <img src="https://img.shields.io/badge/git-%23F05033.svg?style-for-the-badge&logo=git&logoColor=white" alt="Git">
      <img src="https://img.shields.io/badge/cisco-%23049fd9.svg?style-for-the-badge&logo=cisco&logoColor=black" alt="Cisco">
      <img src="https://img.shields.io/badge/Notion-%23000000.svg?style-for-the-badge&logo=notion&logoColor=white" alt="Notion">
      <img src="https://img.shields.io/badge/Postman-FF6C37?style-for-the-badge&logo=postman&logoColor=white" alt="Postman">
      <img src="https://img.shields.io/badge/Portfolio-%23000000.svg?style-for-the-badge&logo=firefox&logoColor=#FF7139" alt="Portfolio">
      <img src="https://img.shields.io/badge/mysql-4479A1.svg?style-for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
    </div>

    <h2>📊 GitHub Stats:</h2>
    <img src="https://github-readme-stats.vercel.app/api?username=12bijaya&theme=dark&hide_border=false&include_all_commits=false&count_private=false" alt="GitHub Stats"><br>
    <img src="https://nirzak-streak-stats.vercel.app/?user=12bijaya&theme=dark&hide_border=false" alt="GitHub Streak"><br>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=12bijaya&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact" alt="Top Languages">

    <h3>✍️ Random Dev Quote</h3>
    <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical" alt="Random Dev Quote">

    <h3>🔝 Top Contributed Repo</h3>
    <img src="https://github-contributor-stats.vercel.app/api?username=12bijaya&limit=5&theme=dark&combine_all_yearly_contributions=true" alt="Top Contributed Repos">

    <p><a href="https://visitcount.itsvg.in"><img src="https://visitcount.itsvg.in/api?id=12bijaya&icon=0&color=0" alt="Visitor Count"></a></p>
  </div>

  <script>
    const terminalText = `whoami
Bijaya Kumal
Cybersecurity Enthusiast | CTF Player | Code Breaker
Studying by day, hacking by night
Skills: Python, C/C++, Assembly
Interests: Networking, Exploits, Reverse Engineering, Binary Exploitation
Always learning, always curious
Initializing profile...`;

    const terminalElement = document.getElementById('terminal-text');
    const profileContent = document.querySelector('.profile-content');
    let i = 0;

    function typeWriter() {
      if (i < terminalText.length) {
        terminalElement.textContent += terminalText.charAt(i);
        i++;
        setTimeout(typeWriter, 50);
      } else {
        setTimeout(() => {
          profileContent.classList.add('visible');
        }, 500);
      }
    }

    window.onload = typeWriter;
  </script>
</body>
</html>
