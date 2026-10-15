<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fatemeh | Frontend Developer</title>
    <!-- Devicon CDN - نسخه پایدار -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">
    
    <style>
        /* ===== RESET & BASE ===== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #0d1117;
            color: #c9d1d9;
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
            direction: ltr;
            text-align: left;
        }

        .code-block .key { color: #79c0ff; }
        .code-block .string { color: #a5d6ff; }

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
            padding: 10px;
        }

        .icon-box:hover {
            transform: translateY(-3px);
            background-color: #30363d;
            border-color: #58a6ff;
            box-shadow: 0 0 12px rgba(88, 166, 255, 0.2);
        }

        .icon-box i {
            font-size: 32px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .icon-box svg {
            width: 32px;
            height: 32px;
            display: block;
        }

        /* ===== ICON COLORS ===== */
        .icon-js { color: #f7df1e; }
        .icon-ts { color: #3178c6; }
        .icon-react { color: #61dafb; }
        .icon-vite { color: #646cff; }
        .icon-bootstrap { color: #7952b3; }
        .icon-node { color: #339933; }
        .icon-mongo { color: #47a248; }
        .icon-git { color: #f05032; }
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
            body { padding: 20px 15px; }
            h1 { font-size: 1.6rem; }
            h2 { font-size: 1.2rem; }
            .icon-box { width: 48px; height: 48px; padding: 8px; }
            .icon-box i { font-size: 26px; }
            .icon-box svg { width: 26px; height: 26px; }
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
                <!-- Material UI - SVG مستقیم -->
                <div class="icon-box" title="Material UI">
                    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" fill="#007fff">
                        <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5-10-5-10 5zM12 22l10-5-10-5-10 5 10 5z" opacity="0.7"/>
                    </svg>
                </div>
            </div>
        </div>

        <!-- Backend & Database -->
        <div class="tech-category">
            <div class="tech-category-title">Backend & Database</div>
            <div class="icon-grid">
                <div class="icon-box" title="Node.js"><i class="devicon-nodejs-plain icon-node"></i></div>
                <!-- Express - SVG مستقیم -->
                <div class="icon-box" title="Express">
                    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" fill="#ffffff">
                        <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/>
                    </svg>
                </div>
                <div class="icon-box" title="MongoDB"><i class="devicon-mongodb-plain icon-mongo"></i></div>
            </div>
        </div>

        <!-- Development Tools -->
        <div class="tech-category">
            <div class="tech-category-title">Development Tools</div>
            <div class="icon-grid">
                <div class="icon-box" title="Git"><i class="devicon-git-plain icon-git"></i></div>
                <!-- GitHub - SVG مستقیم -->
                <div class="icon-box" title="GitHub">
                    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" fill="#ffffff">
                        <path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0 0 24 12c0-6.63-5.37-12-12-12z"/>
                    </svg>
                </div>
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
