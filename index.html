<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>J.A.R.V.I.S. - Advanced AI Interface</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #000;
      color: #0ff;
      font-family: 'Orbitron', 'Arial', sans-serif;
      height: 100vh;
      overflow: hidden;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
    }

    /* 添加 Orbitron 字体（科技感） */
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700&display=swap');

    /* 星空背景 */
    .stars {
      position: absolute;
      width: 100%;
      height: 100%;
      background: radial-gradient(ellipse at center, #111 0%, #000 100%);
    }

    .star {
      position: absolute;
      background: #fff;
      border-radius: 50%;
      animation: twinkle 3s infinite alternate;
    }

    @keyframes twinkle {
      0% { opacity: 0.2; }
      100% { opacity: 1; }
    }

    /* 核心反应堆 - 呼吸光圈 */
    .reactor {
      width: 200px;
      height: 200px;
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
      margin-bottom: 50px;
    }

    .core {
      width: 60px;
      height: 60px;
      background: #0ff;
      border-radius: 50%;
      box-shadow: 0 0 40px #0ff, 0 0 80px rgba(0, 255, 255, 0.5);
      position: relative;
      z-index: 3;
      animation: breathe 3s ease-in-out infinite alternate;
    }

    @keyframes breathe {
      0% { box-shadow: 0 0 30px #0ff, 0 0 60px rgba(0, 255, 255, 0.3); }
      100% { box-shadow: 0 0 60px #0ff, 0 0 120px rgba(0, 255, 255, 0.6); }
    }

    .ring {
      position: absolute;
      border: 2px solid rgba(0, 255, 255, 0.3);
      border-radius: 50%;
      animation: expand 4s infinite;
      opacity: 0;
    }

    .ring:nth-child(2) { animation-delay: 0.8s; }
    .ring:nth-child(3) { animation-delay: 1.6s; }
    .ring:nth-child(4) { animation-delay: 2.4s; }

    @keyframes expand {
      0% {
        width: 180px;
        height: 180px;
        opacity: 0.6;
      }
      100% {
        width: 300px;
        height: 300px;
        opacity: 0;
      }
    }

    /* 雷达扫描效果 */
    .radar {
      position: absolute;
      width: 250px;
      height: 250px;
      border: 1px solid rgba(0, 255, 255, 0.4);
      border-radius: 50%;
      animation: rotate 10s linear infinite;
      clip: rect(0px, 250px, 250px, 125px);
    }

    .radar::before {
      content: '';
      position: absolute;
      top: 50%;
      left: 50%;
      width: 2px;
      height: 125px;
      background: linear-gradient(to top, transparent, #0ff);
      transform-origin: bottom center;
      transform: translate(-50%, -100%) rotate(0deg);
      animation: scan 5s linear infinite;
    }

    @keyframes rotate {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    @keyframes scan {
      0% { transform: translate(-50%, -100%) rotate(0deg); }
      100% { transform: translate(-50%, -100%) rotate(360deg); }
    }

    /* 主容器 */
    .container {
      text-align: center;
      z-index: 10;
      padding: 20px;
    }

    h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
      letter-spacing: 4px;
      text-shadow: 0 0 10px #0ff;
      color: #0ff;
    }

    .subtitle {
      font-size: 1.2rem;
      margin-bottom: 30px;
      color: #0f8;
    }

    .status {
      font-size: 1.1rem;
      margin: 15px 0;
      min-height: 24px;
      color: #0ff;
      text-shadow: 0 0 5px #0ff;
    }

    .mic-button {
      padding: 14px 36px;
      font-size: 1.1rem;
      background: transparent;
      color: #0ff;
      border: 2px solid #0ff;
      border-radius: 30px;
      cursor: pointer;
      outline: none;
      transition: all 0.3s;
      box-shadow: 0 0 15px rgba(0, 255, 255, 0.5);
      letter-spacing: 1px;
    }

    .mic-button:hover {
      background: rgba(0, 255, 255, 0.1);
      transform: scale(1.05);
    }

    .mic-button.listening {
      animation: pulse 1.2s infinite;
      box-shadow: 0 0 20px #0ff, 0 0 40px rgba(0, 255, 255, 0.8);
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.1); }
      100% { transform: scale(1); }
    }

    /* 对话气泡 */
    .chat {
      margin-top: 20px;
      max-width: 500px;
      font-size: 0.95rem;
      line-height: 1.5;
    }

    .msg {
      margin: 8px 0;
      padding: 8px 12px;
      border-radius: 12px;
      display: inline-block;
      max-width: 80%;
    }

    .you {
      background: rgba(0, 255, 255, 0.2);
      color: #0ff;
      align-self: flex-start;
      border-left: 3px solid #0ff;
    }

    .jarvis {
      background: rgba(0, 255, 0, 0.2);
      color: #0f8;
      align-self: flex-end;
      margin-left: auto;
      border-left: 3px solid #0f8;
    }

    .chat-container {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      min-height: 80px;
    }
  </style>
</head>
<body>

  <!-- 星空背景 -->
  <div class="stars" id="stars"></div>

  <div class="container">
    <h1>J.A.R.V.I.S.</h1>
    <p class="subtitle">Just A Rather Very Intelligent System</p>

    <!-- 反应堆核心 -->
    <div class="reactor">
      <div class="core"></div>
      <div class="ring" style="width:180px;height:180px;"></div>
      <div class="ring" style="width:180px;height:180px;"></div>
      <div class="ring" style="width:180px;height:180px;"></div>
      <div class="ring" style="width:180px;height:180px;"></div>
      <div class="radar"></div>
    </div>

    <!-- 对话区域 -->
    <div class="chat-container">
      <div class="chat" id="chat">
        <div class="msg jarvis">系统启动中... 欢迎回来，斯塔克先生。</div>
      </div>
      <p class="status" id="status">等待指令...</p>
    </div>

    <button id="micBtn" class="mic-button">激活语音</button>
  </div>

  <script>
    // 创建星空
    const stars = document.getElementById('stars');
    for (let i = 0; i < 100; i++) {
      const star = document.createElement('div');
      star.classList.add('star');
      star.style.width = Math.random() * 3 + 'px';
      star.style.height = star.style.width;
      star.style.left = Math.random() * 100 + 'vw';
      star.style.top = Math.random() * 100 + 'vh';
      star.style.animationDelay = Math.random() * 3 + 's';
      stars.appendChild(star);
    }

    // 语音识别
    const SpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;
    const synth = window.speechSynthesis;
    const micBtn = document.getElementById('micBtn');
    const statusText = document.getElementById('status');
    const chat = document.getElementById('chat');

    let recognition;
    if (SpeechRecognition) {
      recognition = new SpeechRecognition();
      recognition.continuous = false;
      recognition.interimResults = false;
      recognition.lang = 'zh-CN'; // 可改为 'en-US'
    } else {
      statusText.textContent = '您的浏览器不支持语音识别';
      micBtn.disabled = true;
    }

    // 添加消息
    function addMsg(text, sender) {
      const msg = document.createElement('div');
      msg.classList.add('msg', sender);
      msg.textContent = text;
      chat.appendChild(msg);
      chat.scrollTop = chat.scrollHeight;
    }

    // 语音合成
    function speak(text) {
      const utterance = new SpeechSynthesisUtterance(text);
      utterance.lang = 'zh-CN';
      utterance.rate = 0.9;
      utterance.pitch = 1.1;
      synth.speak(utterance);
      addMsg(text, 'jarvis');
      statusText.textContent = `Jarvis: ${text}`;
    }

    // 启动问候
    window.onload = () => {
      setTimeout(() => {
        speak("系统已上线。J.A.R.V.I.S. 随时为您服务，斯塔克先生。");
      }, 1000);
    };

    // 按钮交互
    micBtn.addEventListener('click', () => {
      micBtn.classList.add('listening');
      statusText.textContent = '👂 正在聆听...';
      try {
        recognition.start();
      } catch (e) {
        statusText.textContent = '语音识别启动失败';
      }
    });

    recognition.onresult = (event) => {
      const transcript = event.results[0][0].transcript.trim();
      const confidence = event.results[0][0].confidence;
      addMsg(transcript, 'you');
      micBtn.classList.remove('listening');

      // 简单命令识别
      let response = "";

      if (transcript.includes('你好') || transcript.includes('hello')) {
        response = "您好，先生。";
      } else if (transcript.includes('名字') || transcript.includes('你是谁')) {
        response = "我是 J.A.R.V.I.S.，您的个人人工智能系统。";
      } else if (transcript.includes('时间') || transcript.includes('几点')) {
        const now = new Date();
        response = `当前时间为 ${now.toLocaleTimeString('zh-CN')}。`;
      } else if (transcript.includes('天气')) {
        response = "室内气候稳定，外部天气晴朗，适合飞行测试。";
      } else if (transcript.includes('战甲') || transcript.includes('suit')) {
        response = "Mark 85 已准备就绪，随时可穿戴。";
      } else if (transcript.includes('关闭') || transcript.includes('退出')) {
        response = "正在进入休眠模式。祝您晚安，先生。";
        setTimeout(() => speak(response), 500);
        return;
      } else {
        response = "抱歉，我未理解该指令。";
      }

      setTimeout(() => speak(response), 600);
    };

    recognition.onerror = (event) => {
      statusText.textContent = `❌ 识别失败: ${event.error}`;
      micBtn.classList.remove('listening');
    };

    recognition.onend = () => {
      micBtn.classList.remove('listening');
    };
  </script>

</body>
</html><!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>J.A.R.V.I.S. - Advanced AI Interface</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #000;
      color: #0ff;
      font-family: 'Orbitron', 'Arial', sans-serif;
      height: 100vh;
      overflow: hidden;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
    }

    /* 添加 Orbitron 字体（科技感） */
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700&display=swap');

    /* 星空背景 */
    .stars {
      position: absolute;
      width: 100%;
      height: 100%;
      background: radial-gradient(ellipse at center, #111 0%, #000 100%);
    }

    .star {
      position: absolute;
      background: #fff;
      border-radius: 50%;
      animation: twinkle 3s infinite alternate;
    }

    @keyframes twinkle {
      0% { opacity: 0.2; }
      100% { opacity: 1; }
    }

    /* 核心反应堆 - 呼吸光圈 */
    .reactor {
      width: 200px;
      height: 200px;
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
      margin-bottom: 50px;
    }

    .core {
      width: 60px;
      height: 60px;
      background: #0ff;
      border-radius: 50%;
      box-shadow: 0 0 40px #0ff, 0 0 80px rgba(0, 255, 255, 0.5);
      position: relative;
      z-index: 3;
      animation: breathe 3s ease-in-out infinite alternate;
    }

    @keyframes breathe {
      0% { box-shadow: 0 0 30px #0ff, 0 0 60px rgba(0, 255, 255, 0.3); }
      100% { box-shadow: 0 0 60px #0ff, 0 0 120px rgba(0, 255, 255, 0.6); }
    }

    .ring {
      position: absolute;
      border: 2px solid rgba(0, 255, 255, 0.3);
      border-radius: 50%;
      animation: expand 4s infinite;
      opacity: 0;
    }

    .ring:nth-child(2) { animation-delay: 0.8s; }
    .ring:nth-child(3) { animation-delay: 1.6s; }
    .ring:nth-child(4) { animation-delay: 2.4s; }

    @keyframes expand {
      0% {
        width: 180px;
        height: 180px;
        opacity: 0.6;
      }
      100% {
        width: 300px;
        height: 300px;
        opacity: 0;
      }
    }

    /* 雷达扫描效果 */
    .radar {
      position: absolute;
      width: 250px;
      height: 250px;
      border: 1px solid rgba(0, 255, 255, 0.4);
      border-radius: 50%;
      animation: rotate 10s linear infinite;
      clip: rect(0px, 250px, 250px, 125px);
    }

    .radar::before {
      content: '';
      position: absolute;
      top: 50%;
      left: 50%;
      width: 2px;
      height: 125px;
      background: linear-gradient(to top, transparent, #0ff);
      transform-origin: bottom center;
      transform: translate(-50%, -100%) rotate(0deg);
      animation: scan 5s linear infinite;
    }

    @keyframes rotate {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    @keyframes scan {
      0% { transform: translate(-50%, -100%) rotate(0deg); }
      100% { transform: translate(-50%, -100%) rotate(360deg); }
    }

    /* 主容器 */
    .container {
      text-align: center;
      z-index: 10;
      padding: 20px;
    }

    h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
      letter-spacing: 4px;
      text-shadow: 0 0 10px #0ff;
      color: #0ff;
    }

    .subtitle {
      font-size: 1.2rem;
      margin-bottom: 30px;
      color: #0f8;
    }

    .status {
      font-size: 1.1rem;
      margin: 15px 0;
      min-height: 24px;
      color: #0ff;
      text-shadow: 0 0 5px #0ff;
    }

    .mic-button {
      padding: 14px 36px;
      font-size: 1.1rem;
      background: transparent;
      color: #0ff;
      border: 2px solid #0ff;
      border-radius: 30px;
      cursor: pointer;
      outline: none;
      transition: all 0.3s;
      box-shadow: 0 0 15px rgba(0, 255, 255, 0.5);
      letter-spacing: 1px;
    }

    .mic-button:hover {
      background: rgba(0, 255, 255, 0.1);
      transform: scale(1.05);
    }

    .mic-button.listening {
      animation: pulse 1.2s infinite;
      box-shadow: 0 0 20px #0ff, 0 0 40px rgba(0, 255, 255, 0.8);
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.1); }
      100% { transform: scale(1); }
    }

    /* 对话气泡 */
    .chat {
      margin-top: 20px;
      max-width: 500px;
      font-size: 0.95rem;
      line-height: 1.5;
    }

    .msg {
      margin: 8px 0;
      padding: 8px 12px;
      border-radius: 12px;
      display: inline-block;
      max-width: 80%;
    }

    .you {
      background: rgba(0, 255, 255, 0.2);
      color: #0ff;
      align-self: flex-start;
      border-left: 3px solid #0ff;
    }

    .jarvis {
      background: rgba(0, 255, 0, 0.2);
      color: #0f8;
      align-self: flex-end;
      margin-left: auto;
      border-left: 3px solid #0f8;
    }

    .chat-container {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      min-height: 80px;
    }
  </style>
</head>
<body>

  <!-- 星空背景 -->
  <div class="stars" id="stars"></div>

  <div class="container">
    <h1>J.A.R.V.I.S.</h1>
    <p class="subtitle">Just A Rather Very Intelligent System</p>

    <!-- 反应堆核心 -->
    <div class="reactor">
      <div class="core"></div>
      <div class="ring" style="width:180px;height:180px;"></div>
      <div class="ring" style="width:180px;height:180px;"></div>
      <div class="ring" style="width:180px;height:180px;"></div>
      <div class="ring" style="width:180px;height:180px;"></div>
      <div class="radar"></div>
    </div>

    <!-- 对话区域 -->
    <div class="chat-container">
      <div class="chat" id="chat">
        <div class="msg jarvis">系统启动中... 欢迎回来，斯塔克先生。</div>
      </div>
      <p class="status" id="status">等待指令...</p>
    </div>

    <button id="micBtn" class="mic-button">激活语音</button>
  </div>

  <script>
    // 创建星空
    const stars = document.getElementById('stars');
    for (let i = 0; i < 100; i++) {
      const star = document.createElement('div');
      star.classList.add('star');
      star.style.width = Math.random() * 3 + 'px';
      star.style.height = star.style.width;
      star.style.left = Math.random() * 100 + 'vw';
      star.style.top = Math.random() * 100 + 'vh';
      star.style.animationDelay = Math.random() * 3 + 's';
      stars.appendChild(star);
    }

    // 语音识别
    const SpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;
    const synth = window.speechSynthesis;
    const micBtn = document.getElementById('micBtn');
    const statusText = document.getElementById('status');
    const chat = document.getElementById('chat');

    let recognition;
    if (SpeechRecognition) {
      recognition = new SpeechRecognition();
      recognition.continuous = false;
      recognition.interimResults = false;
      recognition.lang = 'zh-CN'; // 可改为 'en-US'
    } else {
      statusText.textContent = '您的浏览器不支持语音识别';
      micBtn.disabled = true;
    }

    // 添加消息
    function addMsg(text, sender) {
      const msg = document.createElement('div');
      msg.classList.add('msg', sender);
      msg.textContent = text;
      chat.appendChild(msg);
      chat.scrollTop = chat.scrollHeight;
    }

    // 语音合成
    function speak(text) {
      const utterance = new SpeechSynthesisUtterance(text);
      utterance.lang = 'zh-CN';
      utterance.rate = 0.9;
      utterance.pitch = 1.1;
      synth.speak(utterance);
      addMsg(text, 'jarvis');
      statusText.textContent = `Jarvis: ${text}`;
    }

    // 启动问候
    window.onload = () => {
      setTimeout(() => {
        speak("系统已上线。J.A.R.V.I.S. 随时为您服务，斯塔克先生。");
      }, 1000);
    };

    // 按钮交互
    micBtn.addEventListener('click', () => {
      micBtn.classList.add('listening');
      statusText.textContent = '👂 正在聆听...';
      try {
        recognition.start();
      } catch (e) {
        statusText.textContent = '语音识别启动失败';
      }
    });

    recognition.onresult = (event) => {
      const transcript = event.results[0][0].transcript.trim();
      const confidence = event.results[0][0].confidence;
      addMsg(transcript, 'you');
      micBtn.classList.remove('listening');

      // 简单命令识别
      let response = "";

      if (transcript.includes('你好') || transcript.includes('hello')) {
        response = "您好，先生。";
      } else if (transcript.includes('名字') || transcript.includes('你是谁')) {
        response = "我是 J.A.R.V.I.S.，您的个人人工智能系统。";
      } else if (transcript.includes('时间') || transcript.includes('几点')) {
        const now = new Date();
        response = `当前时间为 ${now.toLocaleTimeString('zh-CN')}。`;
      } else if (transcript.includes('天气')) {
        response = "室内气候稳定，外部天气晴朗，适合飞行测试。";
      } else if (transcript.includes('战甲') || transcript.includes('suit')) {
        response = "Mark 85 已准备就绪，随时可穿戴。";
      } else if (transcript.includes('关闭') || transcript.includes('退出')) {
        response = "正在进入休眠模式。祝您晚安，先生。";
        setTimeout(() => speak(response), 500);
        return;
      } else {
        response = "抱歉，我未理解该指令。";
      }

      setTimeout(() => speak(response), 600);
    };

    recognition.onerror = (event) => {
      statusText.textContent = `❌ 识别失败: ${event.error}`;
      micBtn.classList.remove('listening');
    };

    recognition.onend = () => {
      micBtn.classList.remove('listening');
    };
  </script>

</body>
</html>
