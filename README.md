<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | Advanced Minimalist</title>
    
    <style>
        /* 1. CSS VARIABLES - Easy to change colors in one place */
        :root {
            --bg: #ffffff;
            --text: #111111;
            --accent: #666666;
            --border: #e2e2e2;
            --speed: 0.4s;
        }

        /* 2. AUTOMATIC DARK MODE - Detects phone settings */
        @media (prefers-color-scheme: dark) {
            :root {
                --bg: #0a0a0a;
                --text: #f5f5f5;
                --accent: #888888;
                --border: #222222;
            }
        }

        /* 3. CORE DESIGN */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        
        body {
            background-color: var(--bg);
            color: var(--text);
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.5;
            padding: 10vh 5vw;
            transition: background-color var(--speed), color var(--speed);
            display: flex;
            justify-content: center;
        }

        main { max-width: 600px; width: 100%; opacity: 0; animation: fadeIn 1s forwards; }

        @keyframes fadeIn { to { opacity: 1; } }

        header { margin-bottom: 60px; }
        
        h1 { font-size: 2.5rem; font-weight: 700; letter-spacing: -1.5px; }
        
        .role { color: var(--accent); font-size: 1rem; margin-top: 5px; }

        /* 4. ADVANCED GRID LAYOUT */
        .section-title { font-size: 0.75rem; text-transform: uppercase; letter-spacing: 2px; color: var(--accent); margin-bottom: 20px; border-bottom: 1px solid var(--border); padding-bottom: 5px; }

        .project-grid { display: grid; gap: 15px; margin-bottom: 60px; }

        .project-card {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
            text-decoration: none;
            color: inherit;
            border-bottom: 1px solid var(--border);
            transition: padding-left var(--speed);
        }

        /* Subtle interaction on tap */
        .project-card:hover, .project-card:active {
            padding-left: 10px;
            color: var(--accent);
        }

        .project-card span { font-size: 0.8rem; opacity: 0.5; }

        footer { font-size: 0.75rem; color: var(--accent); margin-top: 100px; text-align: center; }

    </style>
</head>
<body>

    <main>
        <header>
            <h1>Your Name.</h1>
            <p class="role">Building tools with code and AI.</p>
        </header>

        <p class="section-title">Selected Works</p>
        <div class="project-grid">
            <a href="#" class="project-card">
                <p>GitHub Profile</p>
                <span>2026</span>
            </a>
            <a href="#" class="project-card">
                <p>Minimalist Engine</p>
                <span>WIP</span>
            </a>
            <a href="#" class="project-card">
                <p>Mobile Workflow</p>
                <span>Case Study</span>
            </a>
        </div>

        <p class="section-title">Connect</p>
        <div class="project-grid">
            <a href="mailto:your@email.com" class="project-card">Email</a>
            <a href="https://github.com/YOUR_USERNAME" class="project-card">GitHub</a>
        </div>

        <footer>
            Built on a smartphone using Gemini AI.
        </footer>
    </main>

</body>
</html>
