<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Terminal</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Courier New', monospace;
            min-height: 100vh;
            background: #0a0a0a;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            color: #00ff00;
            overflow-x: hidden;
        }

        /* Aurora Background */
        .aurora-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
            pointer-events: none;
        }

        #auroraCanvas {
            width: 100%;
            height: 100%;
            opacity: 0.3;
        }

        /* Click Glitch Effect */
        .glitch-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 9999;
        }

        .glitch-effect {
            position: absolute;
            width: 200px;
            height: 200px;
            pointer-events: none;
            transform: translate(-50%, -50%);
        }

        .glitch-ring {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            border: 2px solid #00ff00;
            border-radius: 50%;
            animation: glitchExpand 0.6s ease-out forwards;
        }

        .glitch-ring:nth-child(1) {
            animation-delay: 0s;
        }

        .glitch-ring:nth-child(2) {
            animation-delay: 0.1s;
            border-color: #ff00ff;
        }

        .glitch-ring:nth-child(3) {
            animation-delay: 0.2s;
            border-color: #00ffff;
        }

        @keyframes glitchExpand {
            0% {
                width: 20px;
                height: 20px;
                opacity: 1;
            }
            100% {
                width: 200px;
                height: 200px;
                opacity: 0;
            }
        }

        .glitch-line {
            position: absolute;
            background: #00ff00;
            height: 2px;
            animation: glitchLine 0.3s ease-out forwards;
        }

        @keyframes glitchLine {
            0% {
                width: 0;
                opacity: 1;
            }
            100% {
                width: 100px;
                opacity: 0;
            }
        }

        .boot-screen {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: #0a0a0a;
            z-index: 1000;
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            align-items: flex-start;
            padding: 40px;
        }

        .boot-screen.hidden {
            display: none;
        }

        .boot-text {
            color: #00ff00;
            font-size: 14px;
            margin: 2px 0;
            white-space: pre;
        }

        .loading-bar-container {
            margin-top: 20px;
            width: 100%;
            max-width: 500px;
        }

        .loading-bar {
            opacity: 0;
            transition: opacity 0.3s;
        }

        .loading-bar-bg {
            background: #1a1a1a;
            height: 20px;
            border: 1px solid #00ff00;
            position: relative;
            overflow: hidden;
        }

        .loading-fill {
            background: #00ff00;
            height: 100%;
            width: 0%;
            transition: width 0.1s linear;
        }

        .terminal {
            max-width: 700px;
            width: 100%;
            background: rgba(26, 26, 26, 0.9);
            border: 2px solid #333;
            border-radius: 8px;
            box-shadow: 0 0 40px rgba(0, 255, 0, 0.1);
            overflow: hidden;
            opacity: 0;
            transform: scale(0.95);
            transition: opacity 0.5s, transform 0.5s;
            position: relative;
            z-index: 1;
            backdrop-filter: blur(10px);
        }

        .terminal.visible {
            opacity: 1;
            transform: scale(1);
        }

        .terminal-header {
            background: rgba(45, 45, 45, 0.95);
            padding: 12px 15px;
            display: flex;
            align-items: center;
            gap: 8px;
            border-bottom: 1px solid #444;
        }

        .terminal-button {
            width: 12px;
            height: 12px;
            border-radius: 50%;
        }

        .btn-red { background: #ff5f56; }
        .btn-yellow { background: #ffbd2e; }
        .btn-green { background: #27c93f; }

        .terminal-title {
            margin-left: 10px;
            color: #888;
            font-size: 13px;
        }

        .terminal-body {
            padding: 25px;
            min-height: 400px;
        }

        .prompt-line {
            color: #00ff00;
            margin-bottom: 20px;
            font-size: 14px;
        }

        .prompt-line span {
            color: #0099ff;
        }

        .command-output {
            margin-bottom: 15px;
            color: #888;
            font-size: 13px;
        }

        .contact-list {
            display: none;
        }

        .contact-item {
            display: flex;
            align-items: center;
            padding: 18px 20px;
            margin-bottom: 15px;
            background: rgba(15, 15, 15, 0.8);
            border: 1px solid #222;
            border-left: 3px solid #00ff00;
            cursor: pointer;
            transition: all 0.3s ease;
            position: relative;
        }

        .contact-item:hover {
            border-left-color: #00ff00;
            border-color: #00ff00;
            background: rgba(21, 21, 21, 0.9);
            box-shadow: 0 0 20px rgba(0, 255, 0, 0.3);
            transform: translateX(5px);
            animation: glitchHover 0.4s ease forwards;
        }

        @keyframes glitchHover {
            0% {
                transform: translateX(0);
                text-shadow: none;
            }
            10% {
                transform: translateX(-3px) skew(-2deg);
                text-shadow: 2px 0 #ff00ff, -2px 0 #00ffff;
            }
            20% {
                transform: translateX(2px) skew(2deg);
                text-shadow: -2px 0 #ff00ff, 2px 0 #00ffff;
            }
            30% {
                transform: translateX(-2px);
                text-shadow: none;
            }
            100% {
                transform: translateX(5px);
                text-shadow: none;
            }
        }

        .contact-item.flashing {
            animation: flashGlitch 0.8s ease;
        }

        @keyframes flashGlitch {
            0% { 
                background: rgba(21, 21, 21, 0.9);
                box-shadow: 0 0 20px rgba(0, 255, 0, 0.3);
                transform: translateX(5px);
            }
            5% {
                transform: translateX(5px) skew(-5deg);
                text-shadow: 3px 0 #ff00ff, -3px 0 #00ffff;
            }
            10% {
                transform: translateX(2px) skew(5deg);
                text-shadow: -3px 0 #ff00ff, 3px 0 #00ffff;
            }
            15% { 
                background: #00ff00;
                color: #000;
                box-shadow: 0 0 40px rgba(0, 255, 0, 0.8);
                transform: translateX(5px);
                text-shadow: none;
            }
            30% { 
                background: rgba(21, 21, 21, 0.9);
                box-shadow: 0 0 20px rgba(0, 255, 0, 0.3);
            }
            35% {
                transform: translateX(5px) skew(-3deg);
                text-shadow: 2px 0 #ff00ff, -2px 0 #00ffff;
            }
            40% {
                transform: translateX(3px) skew(3deg);
                text-shadow: -2px 0 #ff00ff, 2px 0 #00ffff;
            }
            45% { 
                background: #00ff00;
                color: #000;
                box-shadow: 0 0 40px rgba(0, 255, 0, 0.8);
                transform: translateX(5px);
                text-shadow: none;
            }
            60% { 
                background: rgba(21, 21, 21, 0.9);
                box-shadow: 0 0 20px rgba(0, 255, 0, 0.3);
            }
            100% { 
                background: rgba(21, 21, 21, 0.9);
                box-shadow: 0 0 20px rgba(0, 255, 0, 0.3);
                transform: translateX(5px);
                text-shadow: none;
            }
        }

        .icon-wrapper {
            width: 50px;
            height: 50px;
            margin-right: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
        }

        .icon-wrapper img {
            width: 100%;
            height: 100%;
            object-fit: contain;
            filter: brightness(0) invert(1);
            transition: filter 0.3s ease;
        }

        .contact-item:hover .icon-wrapper img {
            filter: brightness(0) saturate(100%) invert(50%) sepia(100%) saturate(3000%) hue-rotate(80deg) brightness(1.2);
        }

        .contact-info {
            flex: 1;
        }

        .contact-label {
            color: #00ff00;
            font-size: 16px;
            margin-bottom: 5px;
            font-weight: bold;
        }

        .contact-value {
            color: #888;
            font-size: 13px;
            transition: color 0.3s ease;
        }

        .contact-value.glitch-copied {
            animation: glitchCopied 1.2s ease;
        }

        @keyframes glitchCopied {
            0% { 
                color: #888;
                text-shadow: none;
                opacity: 1;
            }
            10% {
                transform: translateX(0) skew(0deg);
                text-shadow: none;
                opacity: 0;
            }
            16% {
                transform: skew(0deg);
                text-shadow: 0 0 10px #00ff00;
                opacity: 1;
                color: #00ff00;
            }
            75% {
                color: #00ff00;
                text-shadow: 0 0 10px #00ff00;
                opacity: 1;
            }
            85% {
                opacity: 0;
                color: #00ff00;
            }
            100% {
                color: #888;
                transform: translateX(0) skew(0deg);
                text-shadow: none;
                opacity: 1;
            }
        }

        .arrow {
            color: #00ff00;
            font-size: 18px;
            margin-left: 10px;
            transition: transform 0.3s ease;
        }

        .contact-item:hover .arrow {
            transform: translateX(5px);
        }

        .cursor {
            display: inline-block;
            width: 2px;
            height: 10px;
            background: #00ff00;
            animation: blink 1s step-end infinite;
            margin-left: 5px;
        }
        
        @keyframes blink {
            0%, 50% { opacity: 1; }
            51%, 100% { opacity: 0; }
        }

        @media (max-width: 600px) {
            .terminal-body {
                padding: 20px 15px;
            }
            
            .contact-item {
                padding: 15px;
            }
            
            .icon-wrapper {
                width: 40px;
                height: 40px;
                margin-right: 15px;
            }
        }
    </style>
</head>
<body>
    <!-- Aurora Background -->
    <div class="aurora-container">
        <canvas id="auroraCanvas"></canvas>
    </div>

    <!-- Glitch Click Effect Overlay -->
    <div class="glitch-overlay" id="glitchOverlay"></div>

    <div class="boot-screen" id="bootScreen">
        <div id="bootMessages"></div>
        <div class="loading-bar-container">
            <div class="loading-bar" id="loadingBar">
                <div class="loading-bar-bg">
                    <div class="loading-fill" id="loadingFill"></div>
                </div>
            </div>
        </div>
    </div>

    <div class="terminal" id="terminal">
        <div class="terminal-header">
            <div class="terminal-button btn-red"></div>
            <div class="terminal-button btn-yellow"></div>
            <div class="terminal-button btn-green"></div>
            <div class="terminal-title">contact.sh — bash — 80×24</div>
        </div>
        <div class="terminal-body">
            <div class="prompt-line">
                <span>user@terminal</span>:~$ ./contact.sh
            </div>
            
            <div id="innerTerminalLoad"></div>

            <div class="contact-list">

                <div class="contact-item discord-server" onclick="handleClick(this, 'https://streamfinenotmevalorant-ux.github.io/portofolio/')">
                    <div class="icon-wrapper">
                        <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/discord.svg" alt="Portfolio">
                    </div>
                    <div class="contact-info">
                        <div class="contact-label">[1] Discord Portfolio</div>
                        <div class="contact-value">Wanna check out my work and contribution? Check out my Discord Portfolio!</div>
                    </div>
                    <div class="arrow">→</div>
                </div>

                <div class="contact-item discord-user" onclick="handleClick(this, 'copy', 'finenotme')">
                    <div class="icon-wrapper">
                        <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/discord.svg" alt="Discord">
                    </div>
                    <div class="contact-info">
                        <div class="contact-label">[2] Discord Username</div>
                        <div class="contact-value">finenotme</div>
                    </div>
                    <div class="arrow">⎘</div>
                </div>

                <div class="contact-item roblox" onclick="handleClick(this, 'https://www.roblox.com/users/1423358471/profile')">
                    <div class="icon-wrapper">
                        <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/roblox.svg" alt="Roblox">
                    </div>
                    <div class="contact-info">
                        <div class="contact-label">[3] Roblox Profile</div>
                        <div class="contact-value">Visit my Roblox profile! Feel free to drop a follow</div>
                    </div>
                    <div class="arrow">→</div>
                </div>

                <div class="contact-item email" onclick="handleClick(this, 'copy', 'streamfinenotmevalorant@gmail.com')">
                    <div class="icon-wrapper">
                        <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/gmail.svg" alt="Email">
                    </div>
                    <div class="contact-info">
                        <div class="contact-label">[4] My Email</div>
                        <div class="contact-value">streamfinenotmevalorant@gmail.com</div>
                    </div>
                    <div class="arrow">⎘</div>
                </div>
            </div>

            <div class="prompt-line" style="margin-top: 30px;">
                <span>user@terminal</span>:~$ <span class="cursor"></span>
            </div>
        </div>
    </div>

    <script>
        // Aurora Background Animation
        const canvas = document.getElementById('auroraCanvas');
        const ctx = canvas.getContext('2d');
        
        let width = canvas.width = window.innerWidth;
        let height = canvas.height = window.innerHeight;
        
        window.addEventListener('resize', () => {
            width = canvas.width = window.innerWidth;
            height = canvas.height = window.innerHeight;
        });
        
        class AuroraWave {
            constructor(color, speed, amplitude, frequency) {
                this.color = color;
                this.speed = speed;
                this.amplitude = amplitude;
                this.frequency = frequency;
                this.phase = Math.random() * Math.PI * 2;
            }
            
            draw(time) {
                ctx.beginPath();
                ctx.moveTo(0, height);
                
                for (let x = 0; x <= width; x += 5) {
                    const y = height * 0.5 + 
                             Math.sin((x * this.frequency + time * this.speed + this.phase)) * this.amplitude +
                             Math.sin((x * this.frequency * 0.5 + time * this.speed * 0.7)) * this.amplitude * 0.5;
                    ctx.lineTo(x, y);
                }
                
                ctx.lineTo(width, height);
                ctx.closePath();
                
                const gradient = ctx.createLinearGradient(0, 0, 0, height);
                gradient.addColorStop(0, this.color + '00');
                gradient.addColorStop(0.5, this.color + '60');
                gradient.addColorStop(1, this.color + '00');
                
                ctx.fillStyle = gradient;
                ctx.fill();
            }
        }
        
        const waves = [
            new AuroraWave('#00ff00', 0.0003, 150, 0.002),
            new AuroraWave('#00ffff', 0.0005, 100, 0.003),
            new AuroraWave('#0099ff', 0.0004, 120, 0.0025),
            new AuroraWave('#00ff88', 0.0006, 80, 0.0035)
        ];
        
        function animateAurora() {
            const time = Date.now();
            ctx.clearRect(0, 0, width, height);
            
            ctx.globalCompositeOperation = 'lighter';
            waves.forEach(wave => wave.draw(time));
            ctx.globalCompositeOperation = 'source-over';
            
            requestAnimationFrame(animateAurora);
        }
        
        animateAurora();

        // Glitch Click Effect
        document.addEventListener('click', (e) => {
            createGlitchEffect(e.clientX, e.clientY);
        });

        function createGlitchEffect(x, y) {
            const glitchContainer = document.createElement('div');
            glitchContainer.className = 'glitch-effect';
            glitchContainer.style.left = x + 'px';
            glitchContainer.style.top = y + 'px';

            // Create rings
            for (let i = 0; i < 3; i++) {
                const ring = document.createElement('div');
                ring.className = 'glitch-ring';
                glitchContainer.appendChild(ring);
            }

            // Create lines
            for (let i = 0; i < 8; i++) {
                const line = document.createElement('div');
                line.className = 'glitch-line';
                const angle = (i / 8) * Math.PI * 2;
                const distance = 50;
                line.style.left = '50%';
                line.style.top = '50%';
                line.style.transform = `translate(-50%, -50%) rotate(${angle}rad)`;
                line.style.transformOrigin = 'left center';
                glitchContainer.appendChild(line);
            }

            document.getElementById('glitchOverlay').appendChild(glitchContainer);

            setTimeout(() => {
                glitchContainer.remove();
            }, 600);
        }

        // Boot sequence
        const bootMessages = [
            'BIOS Version 4.2.0',
            'Initializing system...',
            'Loading kernel modules... [OK]',
            'Mounting file systems... [OK]',
            'Starting network interfaces... [OK]',
            'Checking disk integrity... [OK]',
            'Loading contact protocols...',
            'Establishing secure connections...',
            'System ready.'
        ];

        let messageIndex = 0;
        const bootMessagesEl = document.getElementById('bootMessages');
        const loadingBar = document.getElementById('loadingBar');
        const loadingFill = document.getElementById('loadingFill');
        const bootScreen = document.getElementById('bootScreen');
        const terminal = document.getElementById('terminal');

        function showBootMessage() {
            if (messageIndex < bootMessages.length) {
                const messageEl = document.createElement('div');
                messageEl.className = 'boot-text';
                messageEl.textContent = '> ' + bootMessages[messageIndex];
                bootMessagesEl.appendChild(messageEl);
                messageIndex++;
                
                setTimeout(showBootMessage, 400);
            } else {
                setTimeout(showLoadingBar, 500);
            }
        }

        function showLoadingBar() {
            loadingBar.style.opacity = '1';
            let progress = 0;
            const interval = setInterval(() => {
                progress += 2;
                loadingFill.style.width = progress + '%';
                
                if (progress >= 100) {
                    clearInterval(interval);
                    setTimeout(hideBootScreen, 500);
                }
            }, 20);
        }

        function hideBootScreen() {
            bootScreen.classList.add('hidden');
            terminal.classList.add('visible');

            setTimeout(() => {
                startInnerTerminalLoad();
            }, 300);
        }

        function handleClick(element, action, data) {
            element.classList.add('flashing');

            function glitchTypewriter(target, finalText, speed = 40) {
                target.textContent = "";
                let i = 0;

                const randomChar = () => {
                    const chars = "!<>-_\\/[]{}—=+*^?#________";
                    return chars[Math.floor(Math.random() * chars.length)];
                };

                const interval = setInterval(() => {
                    const displayed = finalText.slice(0, i) + (i < finalText.length ? randomChar() : "");
                    target.textContent = displayed;

                    if (i >= finalText.length) {
                        clearInterval(interval);
                        target.textContent = finalText;
                    }

                    i++;
                }, speed);
            }

            setTimeout(() => {
                if (action === "copy") {
                    navigator.clipboard.writeText(data).then(() => {
                        const valueDiv = element.querySelector(".contact-value");
                        const originalText = valueDiv.textContent;

                        valueDiv.classList.add("glitch-copied");
                        valueDiv.textContent = "✓ Copied to clipboard!";

                        setTimeout(() => {
                            glitchTypewriter(valueDiv, originalText, 35);

                            setTimeout(() => {
                                valueDiv.classList.remove("glitch-copied");
                            }, originalText.length * 40 + 200);
                        }, 1800);
                    });
                } else {
                    window.open(action, "_blank");
                }
            }, 300);

            setTimeout(() => {
                element.classList.remove("flashing");
            }, 800);
        }

        const innerTerminalMessages = [
            "loading contact.sh...",
            "initializing modules...",
            "reading databases...",
            "establishing connections...",
            "ready."
        ];

        function typeWriter(text, element, callback, speed = 30) {
            let i = 0;
            element.textContent = '';
            
            function type() {
                if (i < text.length) {
                    element.textContent += text.charAt(i);
                    i++;
                    setTimeout(type, speed);
                } else {
                    if (callback) callback();
                }
            }
            
            type();
        }

        function startInnerTerminalLoad() {
            const container = document.getElementById("innerTerminalLoad");
            container.innerHTML = ""; 

            let index = 0;

            function nextMessage() {
                if (index >= innerTerminalMessages.length) {
                    revealRealContent();
                    return;
                }

                const line = document.createElement("div");
                line.className = "command-output";
                container.appendChild(line);

                typeWriter(innerTerminalMessages[index], line, () => {
                    index++;
                    setTimeout(nextMessage, 200);
                });
            }

            nextMessage();
        }

        function revealRealContent() {
            const realContent = `
                <div class="command-output">Available contact methods:</div>
            `;

            const container = document.getElementById("innerTerminalLoad");
            container.insertAdjacentHTML("beforeend", realContent);

            document.querySelector(".contact-list").style.display = "block";
        }

        setTimeout(showBootMessage, 300);
    </script>
</body>
</html>