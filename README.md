# MY DEAR BOOBU
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>For Teena Soni ❤️</title>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Montserrat:wght@300;600;900&display=swap" rel="stylesheet">
    <style>
        :root { --accent: #ff0055; --gold: #ffd700; --bg: #030303; }
        * { margin: 0; padding: 0; box-sizing: border-box; -webkit-tap-highlight-color: transparent; }
        body { background: var(--bg); font-family: 'Montserrat', sans-serif; color: white; height: 100vh; overflow: hidden; display: flex; justify-content: center; align-items: center; }

        /* --- Luxury Background --- */
        #bg-canvas { position: fixed; top: 0; left: 0; width: 100%; height: 100%; z-index: -1; background: radial-gradient(circle at center, #1e001a 0%, #030303 100%); }

        /* --- SCREEN 1: THE COSMIC UNLOCK --- */
        #lock-screen { text-align: center; z-index: 100; transition: 1.2s cubic-bezier(0.4, 0, 0.2, 1); }
        .main-heart { font-size: 100px; cursor: pointer; filter: drop-shadow(0 0 30px var(--accent)); animation: beat 1.2s infinite; }
        @keyframes beat { 0% { transform: scale(1); } 50% { transform: scale(1.15); filter: drop-shadow(0 0 50px var(--accent)); } 100% { transform: scale(1); } }
        .unlock-text { margin-top: 20px; font-weight: 300; letter-spacing: 5px; opacity: 0.6; font-size: 0.8rem; }

        /* --- MAIN INTERFACE --- */
        #app-body { display: none; width: 100%; height: 100%; flex-direction: column; padding: 20px; animation: entry 1s forwards; }
        @keyframes entry { from { opacity: 0; filter: blur(20px); transform: scale(0.8); } to { opacity: 1; filter: blur(0); transform: scale(1); } }

        .glass-card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(30px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 40px;
            padding: 40px 25px;
            height: 68vh;
            margin-top: 40px;
            display: none;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            box-shadow: 0 40px 80px rgba(0,0,0,0.7);
        }
        .glass-card.active { display: flex; animation: slideIn 0.6s cubic-bezier(0.23, 1, 0.32, 1); }
        @keyframes slideIn { from { opacity: 0; transform: translateY(100px); } to { opacity: 1; transform: translateY(0); } }

        h1 { font-family: 'Dancing Script', cursive; font-size: 3.2rem; color: var(--accent); margin-bottom: 15px; }
        h2 { font-size: 0.7rem; letter-spacing: 6px; color: #ffb6c1; margin-bottom: 25px; text-transform: uppercase; }
        p { font-size: 1.05rem; line-height: 1.8; color: #eee; font-weight: 300; }

        /* --- SHYARI & SIGNATURE --- */
        .shyari-content { font-style: italic; font-size: 1.3rem; color: var(--gold); position: relative; padding: 20px; }
        .shyari-content::before { content: '“'; position: absolute; top: -10px; left: 0; font-size: 4rem; opacity: 0.2; }
        .sig-box { width: 100%; text-align: right; margin-top: 20px; }
        .navuddin-sig { font-family: 'Dancing Script', cursive; font-size: 2rem; color: white; border-bottom: 2px solid var(--accent); display: inline-block; padding-bottom: 5px; }

        /* --- SUPREME COURT VERDICT --- */
        .sc-seal { width: 80px; height: 80px; border: 4px double var(--gold); border-radius: 50%; display: flex; align-items: center; justify-content: center; font-weight: 900; font-size: 0.6rem; color: var(--gold); margin-bottom: 20px; transform: rotate(-15deg); box-shadow: 0 0 20px rgba(255,215,0,0.3); }
        .sc-title { font-size: 2.2rem; color: var(--gold); font-weight: 900; text-shadow: 0 0 20px rgba(255,215,0,0.5); }

        /* --- TAB NAVIGATION --- */
        .app-nav { position: fixed; bottom: 30px; width: 90%; max-width: 380px; background: rgba(15, 15, 15, 0.9); border-radius: 30px; display: flex; justify-content: space-around; padding: 15px; border: 1px solid rgba(255,255,255,0.1); backdrop-filter: blur(20px); }
        .nav-btn { color: #555; font-size: 1.4rem; cursor: pointer; transition: 0.4s; position: relative; }
        .nav-btn.active { color: var(--accent); transform: translateY(-10px) scale(1.2); }
        .nav-btn.active::after { content: ''; position: absolute; bottom: -8px; left: 50%; transform: translateX(-50%); width: 5px; height: 5px; background: var(--accent); border-radius: 50%; }

        /* --- FLOATING MAGIC --- */
        .sparkle { position: absolute; color: var(--accent); pointer-events: none; animation: fly 5s linear forwards; }
        @keyframes fly { to { transform: translateY(-110vh) rotate(360deg); opacity: 0; } }
    </style>
</head>
<body>

    <div id="bg-canvas"></div>

    <div id="lock-screen">
        <div class="main-heart" onclick="initApp()">❤️</div>
        <h1 style="color: white; margin-top: 15px;">Teena Soni</h1>
        <div class="unlock-text">TAP TO UNLOCK LOVE</div>
    </div>

    <div id="app-body">
        
        <div class="glass-card active" id="p1">
            <div style="font-size: 50px; margin-bottom: 10px;">📅</div>
            <h1>Happy 5 Months</h1>
            <h2>ANNIVERSARY SPECIAL</h2>
            <p>Shaadi ke ye <span style="color:var(--accent); font-weight:700;">150 din</span> kisi sapne se kam nahi hain. Aapne meri zindagi mein aakar isse poora kar diya hai. I Love You, Wifey!</p>
        </div>

        <div class="glass-card" id="p2">
            <h1>Dil Se...</h1>
            <h2>A SPECIAL SHYARI</h2>
            <div class="shyari-content">
                "Aapki ek muskan pe dil har jaaun,<br>
                Aap kahein toh ye saari duniya vaar jaaun,<br>
                Zindagi ke har safar mein saath rehna,<br>
                Ki Aapke bina main khud ko bhool jaaun."
            </div>
            <div class="sig-box">
                <span class="navuddin-sig">- Navuddin</span>
            </div>
        </div>

        <div class="glass-card" id="p3">
            <div class="sc-seal">OFFICIAL SEAL</div>
            <h1 class="sc-title">Supreme Court</h1>
            <h2>FINAL JUDGEMENT</h2>
            <p>Sarkar chahe kisi ki bhi ho, par ghar mein sirf <br><b>Teena Soni</b> ji ka faisla hi aakhri hoga. <br><br>Aap hi meri <span style="color:var(--gold);">Supreme Court</span> hain!</p>
            <div style="font-size: 40px; margin-top: 15px;">⚖️</div>
        </div>

        <div class="glass-card" id="p4">
            <div style="font-size: 60px; margin-bottom: 20px; animation: bounce 2s infinite;">🎁</div>
            <h1>The Promise</h1>
            <h2>FOREVER & ALWAYS</h2>
            <p>Main waada karta hoon ki hamesha Aapki khushi ka khayal rakhunga aur har Anniversary par Aapko aise hi surprise deta rahunga.</p>
            <p style="margin-top: 20px; font-weight: 600; color: var(--accent);">Happy 5 Months, My Queen! 👑</p>
        </div>

        <div class="app-nav">
            <div class="nav-btn active" onclick="show(0, this)">🏠</div>
            <div class="nav-btn" onclick="show(1, this)">🖋️</div>
            <div class="nav-btn" onclick="show(2, this)">⚖️</div>
            <div class="nav-btn" onclick="show(3, this)">🎁</div>
        </div>
    </div>

    <script>
        function initApp() {
            const ls = document.getElementById('lock-screen');
            ls.style.opacity = '0';
            ls.style.transform = 'scale(2)';
            setTimeout(() => {
                ls.style.display = 'none';
                document.getElementById('app-body').style.display = 'flex';
                setInterval(spawnSparkle, 400);
            }, 800);
        }

        function show(idx, el) {
            const cards = document.querySelectorAll('.glass-card');
            const btns = document.querySelectorAll('.nav-btn');
            cards.forEach(c => c.classList.remove('active'));
            btns.forEach(b => b.classList.remove('active'));
            cards[idx].classList.add('active');
            el.classList.add('active');
            if (navigator.vibrate) navigator.vibrate(30);
        }

        function spawnSparkle() {
            const s = document.createElement('div');
            s.innerHTML = "❤️";
            s.className = "sparkle";
            s.style.left = Math.random() * 100 + "vw";
            s.style.top = "110vh";
            s.style.fontSize = Math.random() * 20 + 15 + "px";
            s.style.opacity = Math.random() * 0.6 + 0.2;
            document.body.appendChild(s);
            setTimeout(() => s.remove(), 5000);
        }
    </script>
</body>
</html>
