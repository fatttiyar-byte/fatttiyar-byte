<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fatemeh | Frontend Developer</title>
    <!-- لینک به آیکون‌های Devicon -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">
    
    <style>
        /* ===== RESET & BASE ===== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #0d1117; /* رنگ پس‌زمینه تیره گیت‌هاب */
            color: #c9d1d9; /* رنگ متن اصلی */
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            padding: 40px 20px;
            display: flex;
            justify-content: center;
        }

        .container {
            max-width: 800px;
            width: 100%;
        }

        /* ===== TYPOGRAPHY ===== */
        h1, h2, h3 {
            color: #ffffff;
            font-weight: 600;
        }

        h1 {
            font-size: 2rem;
            margin-bottom: 5px;
        }

        .subtitle {
            font-size: 1.1rem;
            color: #8b949e;
            margin-bottom: 30px;
            border-bottom: 1px solid #30363d;
            padding-bottom: 20px;
        }

        h2 {
            font-size: 1.4rem;
            margin-top: 40px;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        h3 {
            font-size: 1.1rem;
            margin-bottom: 10px;
        }

        p {
            margin-bottom: 15px;
            color: #c9d1d9;
        }

        a {
            color: #58a6ff;
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }

        /* ===== CODE BLOCK ===== */
        .code-block {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 15px 20px;
            font-family: 'Courier New', Courier, monospace;
            font-size: 0.9rem;
            color: #c9d1d9;
            overflow-x: auto;
            margin: 20px 0;
            line-height: 1.5;
        }

        .code-block .key { color: #79c0ff; }
        .code-block .string { color: #a5d6ff; }
        .code-block .bracket { color: #ff7b72; }

        /* ===== LISTS ===== */
        ul {
            list-style: none;
            padding-right: 20px;
        }

        ul li {
            margin-bottom: 8px;
            position: relative;
            padding-right: 20px;
        }

        ul li::before {
            content: "•";
            color: #58a6ff;
            position: absolute;
            right: 0;
            font-weight: bold;
        }

        /* ===== TECH STACK GRID ===== */
        .tech-category {
            margin-bottom: 25px;
        }

        .tech-category-title {
            font-size: 0.9rem;
            font-weight: 600;
            color: #8b949e;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 12px;
            text-align: left;
        }

        .icon-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
        }

        .icon-box {
            width: 55px;
            height: 55px;
            background-color: #21262d;
            border: 1px solid #30363d;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s ease;
            cursor: pointer;
        }

        .icon-box:hover {
            transform: translateY(-3px);
            background-color: #30363d;
            border-color: #58a6ff;
            box-shadow: 0 0 12px rgba(88, 166, 255, 0.2);
        }

        .icon-box i {
            font-size: 28px;
        }

        /* ===== ICON COLORS ===== */
        .icon-js { color: #f7df1e; }
        .icon-ts { color: #3178c6; }
        .icon-react { color: #61dafb; }
        .icon-vite { color: #646cff; }
        .icon-bootstrap { color: #7952b3; }
        .icon-mui { color: #007fff; }
        .icon-node { color: #339933; }
        .icon-express { color: #ffffff; }
        .icon-mongo { color: #47a248; }
        .icon-git { color: #f05032; }
        .icon-github { color: #ffffff; }
        .icon-vscode { color: #007acc; }

        /* ===== PROJECT CARDS ===== */
        .project-card {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 12px;
            padding: 20px;
            margin-bottom: 20px;
        }

        .project-card h3 {
            margin-top: 0;
            color: #58a6ff;
        }

        .project-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-top: 15px;
        }

        .tag {
            background-color: #21262d;
            border: 1px solid #30363d;
            border-radius: 20px;
            padding: 4px 12px;
            font-size: 0.8rem;
            color: #c9d1d9;
        }

        /* ===== DIVIDER ===== */
        hr {
            border: none;
            border-top: 1px solid #30363d;
            margin: 40px 0;
        }

        /* ===== FOOTER ===== */
        .footer-text {
            text-align: center;
            color: #8b949e;
            font-style: italic;
            margin-top: 30px;
        }

        /* ===== RESPONSIVE ===== */
        @media (max-width: 600px) {
            h1 { font-size: 1.6rem; }
            h2 { font-size: 1.2rem; }
            .icon-box { width: 48px; height: 48px; }
            .icon-box i { font-size: 24px; }
        }
    </style>
</head>
<body>

    <div class="container">
        
        <!-- ===== HEADER ===== -->
        <h1>👋🏻 Hey, I'm Fatemeh</h1>
        <p class="subtitle">Frontend Developer · React.js · JavaScript · Node.js</p>

        <!-- ===== ABOUT ME ===== -->
        <h2>👩🏻 About Me</h2>
        <p>I'm a <strong>Frontend Developer</strong> who enjoys transforming ideas into clean, interactive, and responsive web experiences.</p>
        <p>My primary focus is <strong>JavaScript and React.js</strong>, with a growing focus on backend development using <strong>Node.js and Express.js</strong>.</p>

        <div class="code-block">
            <span class="key">const</span> fatemeh = {<br>
            &nbsp;&nbsp;<span class="key">role</span>: <span class="string">"Frontend Developer"</span>,<br>
            &nbsp;&nbsp;<span class="key">focus</span>: [<span class="string">"React.js"</span>, <span class="string">"JavaScript"</span>, <span class="string">"Node.js"</span>],<br>
            &nbsp;&nbsp;<span class="key">currentlyLearning</span>: [<span class="string">"Backend Development"</span>, <span class="string">"MongoDB"</span>, <span class="string">"APIs"</span>],<br>
            };
        </div>

        <!-- ===== WHAT I DO ===== -->
        <h2>⚡ What I Do</h2>
        <ul>
            <li>⚛️ Build scalable and responsive <strong>website</strong></li>
            <li>🎨 Design modern interfaces with <strong>MUI, Bootstrap & React</strong></li>
            <li>🟢 Develop backend applications with <strong>Node.js & Express</strong></li>
        </ul>

        <!-- ===== TECHNOLOGIES & TOOLS ===== -->
        <h2>🛠️ Technologies & Tools</h2>

        <!-- Frontend -->
        <div class="tech-category">
            <div class="tech-category-title">Frontend</div>
            <div class="icon-grid">
                <div class="icon-box" title="JavaScript"><i class="devicon-javascript-plain icon-js"></i></div>
                <div class="icon-box" title="TypeScript"><i class="devicon-typescript-plain icon-ts"></i></div>
                <div class="icon-box" title="React"><i class="devicon-react-original icon-react"></i></div>
                <div class="icon-box" title="Vite"><i class="devicon-vitejs-plain icon-vite"></i></div>
            </div>
        </div>

        <!-- UI & Styling -->
        <div class="tech-category">
            <div class="tech-category-title">UI & Styling</div>
            <div class="icon-grid">
                <div class="icon-box" title="Bootstrap"><i class="devicon-bootstrap-plain icon-bootstrap"></i></div>
                <!-- Material UI به عنوان آیکون درآمده است -->
                <div class="icon-box" title="Material UI"><i class="devicon-materialui-plain icon-mui"></i></div>
            </div>
        </div>

        <!-- Backend & Database -->
        <div class="tech-category">
            <div class="tech-category-title">Backend & Database</div>
            <div class="icon-grid">
                <div class="icon-box" title="Node.js"><i class="devicon-nodejs-plain icon-node"></i></div>
                <div class="icon-box" title="Express"><i class="devicon-express-original icon-express"></i></div>
                <div class="icon-box" title="MongoDB"><i class="devicon-mongodb-plain icon-mongo"></i></div>
            </div>
        </div>

        <!-- Development Tools -->
        <div class="tech-category">
            <div class="tech-category-title">Development Tools</div>
            <div class="icon-grid">
                <div class="icon-box" title="Git"><i class="devicon-git-plain icon-git"></i></div>
                <div class="icon-box" title="GitHub"><i class="devicon-github-original icon-github"></i></div>
                <div class="icon-box" title="VS Code"><i class="devicon-vscode-plain icon-vscode"></i></div>
            </div>
        </div>

        <hr>

        <!-- ===== FEATURED WORK ===== -->
        <h2>🚀 Featured Work</h2>

        <!-- Project 1: Smart Library -->
        <div class="project-card">
            <h3>📚 Smart Library</h3>
            <p>A modern <strong>React-based digital bookstore and library platform</strong> designed with a focus on user experience and interactive functionality.</p>
            <p><strong>Key Features</strong></p>
            <ul>
                <li>🔎 Intelligent book search & filtering</li>
                <li>📚 Genre-based browsing</li>
                <li>❤️ Favorites management</li>
                <li>🛒 Shopping cart</li>
                <li>💾 Local storage persistence</li>
                <li>🤖 Interactive book assistant</li>
                <li>📱 Responsive design</li>
                <li>🎨 Modern Material UI interface</li>
            </ul>
            <div class="project-tags">
                <span class="tag">React</span>
                <span class="tag">JavaScript</span>
                <span class="tag">MUI</span>
                <span class="tag">Bootstrap</span>
            </div>
        </div>

        <!-- Project 2: Diamond Shop -->
        <div class="project-card">
            <h3>💎 Diamond Shop</h3>
            <p>A responsive e-commerce interface developed from scratch with a focus on clean layout, responsive design, and practical frontend implementation.</p>
            <div class="project-tags">
                <span class="tag">HTML</span>
                <span class="tag">CSS</span>
                <span class="tag">JavaScript</span>
                <span class="tag">Bootstrap</span>
            </div>
        </div>

        <hr>

        <!-- ===== FOOTER / CONNECT ===== -->
        <h2>🌐 Connect</h2>
        <p>You can find me on <a href="https://github.com/fatttiyar-byte" target="_blank">GitHub</a>.</p>
        
        <p class="footer-text">Turning ideas into interfaces, and interfaces into experiences.<br>Currently learning. Constantly building. Always improving.</p>

    </div>

</body>
</html>
