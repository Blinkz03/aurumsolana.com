# aurumsolana.com
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>$AURUM – The Golden Memecoin</title>
  <style>
    body {
      font-family: 'Trebuchet MS', sans-serif;
      background: #000;
      color: #FFD700;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      padding: 2rem;
      background: linear-gradient(90deg, #111, #222);
      position: sticky;
      top: 0;
      z-index: 10;
    }
    nav a {
      margin: 0 1rem;
      color: #FFD700;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 3rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    h1, h2 {
      color: #FFD700;
      text-shadow: 0 0 10px #FFD700;
    }
    .countdown {
      font-size: 2rem;
      margin: 1rem 0;
    }
    .community a {
      display: inline-block;
      margin: 1rem;
      color: #FFD700;
      text-decoration: none;
      font-size: 1.2rem;
    }
    .scroll {
      border: 2px solid #FFD700;
      padding: 2rem;
      margin: 2rem auto;
      background: #111;
      border-radius: 10px;
      box-shadow: 0 0 20px #FFD700;
    }
    .golden-phrase {
      font-size: 1.4rem;
      margin-top: 2rem;
      color: #FFD700;
      text-shadow: 0 0 15px #FFD700;
    }
    img {
      max-width: 90%;
      border-radius: 12px;
      margin: 1.5rem 0;
      box-shadow: 0 0 15px #FFD700;
    }
  </style>
</head>
<body>
  <header>
    <h1>⚜️ $AURUM – Digital Meme-Gold on Solana ⚜️</h1>
    <nav>
      <a href="#prophecy">Prophecy</a>
      <a href="#community">Community</a>
    </nav>
  </header>

  <section>
    <h2>🚀 Launching Soon</h2>
    <p>$AURUM is coming live on <strong>30th October</strong> – on the Solana blockchain.</p>
    <div id="countdown" class="countdown"></div>
  </section>

  <section>
    <h2>💰 The Narrative</h2>
    <p>
      Now, $AURUM isn’t just gold… it’s digital meme-gold. Every bag you hold is basically a medieval treasure chest—but instead of pirates, your only enemy is paper hands.
    </p>
    <p>
      🏆 <strong>Ticker:</strong> $AURUM <br>
      ✨ <strong>Utility:</strong> Makes you richer in vibes. <br>
      🐒 <strong>Backed by science:</strong> (A.k.a. “Trust me, bro” tokenomics). <br>
      🗿 <strong>Community role:</strong> Modern-day alchemists turning memes into riches. 
    </p>
    <p>
      Legend says… when $AURUM hits $1, a random degen will evolve into a real-life golden statue.  
      When it hits $10, Elon might tweet “shiny.”  
      And when it moons to infinity? The whole internet will be blinded by your portfolio’s golden glow.
    </p>
    <p><strong>In memes we trust, in $AURUM we shine. 🌟</strong></p>
  </section>

  <section class="scroll" id="prophecy">
    <h2>🔮 The Golden Prophecy of $AURUM</h2>
    <p>
      The ancient scrolls (definitely not written last night by a degen with Cheeto dust on his hands) tell us this:
    </p>
    <blockquote>
      "He who hodls $AURUM shall unlock the gateway to endless memes, bottomless liquidity pools, and the eternal flex of digital gold."
    </blockquote>
    <p>
      But beware… not all can withstand the journey. Some will sell early. Some will FOMO late. And some will get liquidated while trying to leverage their grandma’s pension. Only the true golden apes will survive.
    </p>
    <h3>🪙 Token Utility (aka “Why number go up?”)</h3>
    <ul>
      <li><strong>Gold-backed vibes</strong> – Not backed by real gold… but if you believe hard enough, it’s basically the same thing.</li>
      <li><strong>Shiny flex</strong> – Post your wallet balance on X, blind your haters with golden screenshots.</li>
      <li><strong>Alchemical powers</strong> – Rumored to turn ramen packets into Wagyu steak once $AURUM hits ATH.</li>
    </ul>
    <h3>🏛 The Cult—I mean, Community</h3>
    <ul>
      <li><strong>Miners 🥇</strong> – Meme creators who dig deep for dank content.</li>
      <li><strong>Smiths 🔨</strong> – Shillers forging golden threads across X and TG.</li>
      <li><strong>Keepers 🗝</strong> – The diamond hands who swear never to sell (until it’s “life-changing money”).</li>
    </ul>
    <h3>🌌 The Final Vision</h3>
    <p>
      One day, all fiat will be worthless paper. Banks will collapse. Governments will panic.  
      And in the ashes of the old world, a new standard will rise:  
      <strong>The Aurum Standard™.</strong>
    </p>
    <p>
      Instead of paying rent in dollars, you’ll flick your landlord 0.00042 $AURUM and walk away a hero.
    </p>
    <p class="golden-phrase">✨ “When you realize it’s just a letter ‘A’… pray it’s never too late.” ✨</p>
  </section>

  <section id="gallery">
    <h2>🖼 The Golden Gallery</h2>
    <img src="Screenshot_20250910-143128.png" alt="AURUM Meme 1">
    <img src="Screenshot_20250910-091957.png" alt="AURUM Meme 2">
  </section>

  <section id="community" class="community">
    <h2>🌍 Join the $AURUM Community</h2>
    <a href="https://x.com/aurumchaindev" target="_blank">🐦 X (Twitter)</a>
    <a href="https://t.me/aurumchaincommunity" target="_blank">💬 Telegram</a>
    <a href="https://discord.gg/9Y6QEwRq" target="_blank">🎮 Discord</a>
  </section>

  <footer>
    <p>⚜️ $AURUM – Built on Solana. Powered by Memes. ⚜️</p>
  </footer>

  <script>
    // Countdown Timer
    const countdown = document.getElementById("countdown");
    const launchDate = new Date("October 30, 2025 00:00:00").getTime();
    const timer = setInterval(() => {
      const now = new Date().getTime();
      const diff = launchDate - now;
      if (diff <= 0) {
        clearInterval(timer);
        countdown.innerHTML = "🚀 $AURUM is LIVE!";
        return;
      }
      const days = Math.floor(diff / (1000 * 60 * 60 * 24));
      const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((diff % (1000 * 60)) / 1000);
      countdown.innerHTML = `${days}d ${hours}h ${minutes}m ${seconds}s`;
    }, 1000);
  </script>
</body>
</html>
