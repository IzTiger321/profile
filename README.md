<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IzTiger321 | Hub</title>
    <style>
        :root {
            --bg: #ffffff;
            --text: #111111;
            --accent: #777777;
            --border: #eeeeee;
        }

        @media (prefers-color-scheme: dark) {
            :root {
                --bg: #000000;
                --text: #ffffff;
                --accent: #888888;
                --border: #222222;
            }
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        
        body {
            background-color: var(--bg);
            color: var(--text);
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            line-height: 1.6;
            padding: 40px 20px;
            display: flex;
            justify-content: center;
        }

        main { max-width: 500px; width: 100%; animation: fadeIn 0.8s ease-in; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }

        header { margin-bottom: 50px; }
        h1 { font-size: 1.8rem; font-weight: 800; letter-spacing: -1px; text-transform: uppercase; }
        .bio { font-size: 0.9rem; color: var(--accent); margin-top: 5px; }

        .section-label { font-size: 0.7rem; text-transform: uppercase; letter-spacing: 2px; color: var(--accent); margin: 30px 0 15px 0; border-bottom: 1px solid var(--border); padding-bottom: 5px; }

        .link-grid { display: grid; grid-template-columns: 1fr; gap: 8px; }

        .link-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px 15px;
            text-decoration: none;
            color: inherit;
            border: 1px solid var(--border);
            border-radius: 8px;
            font-size: 0.9rem;
            transition: all 0.3s;
        }

        .link-item:active, .link-item:hover {
            background-color: var(--text);
            color: var(--bg);
            transform: scale(0.98);
        }

        .tag { font-size: 0.7rem; opacity: 0.5; text-transform: lowercase; }

        footer { margin-top: 60px; font-size: 0.7rem; text-align: center; color: var(--accent); }
    </style>
</head>
<body>

    <main>
        <header>
            <h1>IzTiger321</h1>
            <p class="bio">Mobile Developer • Content Creator • Learner</p>
        </header>

        <p class="section-label">Current Project</p>
        <div class="link-grid">
            <div class="link-item" style="border-style: dashed;">
                <p>Building this Site</p>
                <span class="tag">In Progress</span>
            </div>
        </div>

        <p class="section-label">Social & Content</p>
        <div class="link-grid">
            <a href="https://github.com/IzTiger321" class="link-item">GitHub <span class="tag">Code</span></a>
            <a href="https://www.patreon.com/IzTiger321" class="link-item">Patreon <span class="tag">Support</span></a>
            <a href="https://open.substack.com/pub/iztiger321" class="link-item">Substack <span class="tag">Writing</span></a>
            <a href="https://www.tiktok.com/@iz_tiger_321" class="link-item">TikTok <span class="tag">Video</span></a>
            <a href="https://t.me/s/iz_tiger_321" class="link-item">Telegram <span class="tag">Channel</span></a>
            <a href="https://bsky.app/profile/iztiger321.bsky.social" class="link-item">BlueSky <span class="tag">Social</span></a>
            <a href="https://mastodon.social/@IzTiger321" class="link-item">Mastodon <span class="tag">Fediverse</span></a>
            <a href="https://www.threads.net/@iz_tiger_321" class="link-item">Threads <span class="tag">Social</span></a>
        </div>

        <p class="section-label">More Platforms</p>
        <div class="link-grid">
            <a href="https://daun.me/iz_tiger_321" class="link-item">Daun.me</a>
            <a href="https://beacons.ai/iztiger321" class="link-item">Beacons</a>
            <a href="https://pixelfed.social/IzTiger321" class="link-item">Pixelfed</a>
            <a href="https://truthsocial.com/@iz_tiger_321" class="link-item">Truth Social</a>
        </div>

        <footer>
            Updated Feb 2026 • Built on Mobile
        </footer>
    </main>

</body>
</html>
