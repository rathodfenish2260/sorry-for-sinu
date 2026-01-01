# sorry-for-sinu
A small apology website made from the heart for Sinu 💖
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>I'm Sorry ❤️</title>
  <style>
    body{
      margin:0; font-family: 'Segoe UI', Tahoma, sans-serif;
      background: linear-gradient(135deg,#ffdde1,#ee9ca7);
      color:#2b2b2b; min-height:100vh; display:flex; align-items:center; justify-content:center;
    }
    .card{
      background:#fff; max-width:520px; width:92%; padding:28px 26px 34px;
      border-radius:20px; box-shadow:0 20px 40px rgba(0,0,0,.15);
      text-align:center; position:relative; overflow:hidden;
    }
    .heart{font-size:42px; animation:pulse 1.4s infinite}
    @keyframes pulse{0%{transform:scale(1)}50%{transform:scale(1.15)}100%{transform:scale(1)}}
    h1{margin:8px 0 6px; font-size:28px}
    p{line-height:1.6; font-size:16px}
    .note{
      background:#fff5f7; border:1px dashed #ff9fb2; padding:14px; border-radius:14px; margin:16px 0;
    }
    .promise{display:grid; gap:10px; margin-top:14px}
    .promise div{background:#f7f7f7; padding:10px; border-radius:12px}
    .btn{
      display:inline-block; margin-top:18px; padding:12px 18px; border-radius:999px;
      background:#ff5c8a; color:#fff; text-decoration:none; font-weight:600;
      box-shadow:0 10px 20px rgba(255,92,138,.35)
    }
    footer{margin-top:18px; font-size:13px; color:#777}
  </style>
</head>
<body>
  <!-- Background Music -->
  <iframe width="0" height="0" src="https://www.youtube.com/embed/fRh_vgS2dFE?autoplay=1&loop=1&playlist=fRh_vgS2dFE" frameborder="0" allow="autoplay"></iframe>
  <div class="card">
    <div class="heart">❤️</div>
    <h1>I'm Really Sorry, <span style="color:#ff5c8a">Sinu</span> 💖</h1>
    <p><strong>Hey…</strong></p>
    <p>
      Mujhse galti ho gayi. Jaan-bujhkar kabhi bhi tumhe hurt karna mera intention nahi tha.
      Shayad words kam pad jaayein, par dil se keh raha hoon — <strong>I'm sorry.</strong>
    </p>

    <div class="note">
      <p>
        Tum meri life ka bahut important hissa ho. Tumhari ek smile mere din ko better bana deti hai,
        aur tumhari narazgi mujhe andar se tod deti hai.
      </p>
    </div>

    <p><strong>Main wada karta hoon:</strong></p>
    <div class="promise">
      <div>✨ Main dhyaan se sununga, react nahi karunga</div>
      <div>✨ Tumhari feelings hamesha respect karunga</div>
      <div>✨ Galti repeat nahi karunga — action se prove karunga</div>
    </div>

    <a class="btn" href="#">Please Forgive Me 🥺</a>

    <footer>
      — From someone who truly cares for you
    </footer>
  </div>
</body>
</html>
