<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Ramez invites you ✨</title>
  <style>
    :root { --bg:#fffaf7; --card:#ffffff; --accent:#5b7cfa; --text:#222; --muted:#777; --ok:#28a745; }
    body { margin:0; font-family: system-ui, -apple-system, Segoe UI, Roboto, sans-serif; background: linear-gradient(160deg,#fffaf7,#f7f9ff); color:var(--text); }
    .wrap { max-width: 680px; margin: 0 auto; padding: 28px; }
    .card { background:var(--card); border-radius: 18px; box-shadow: 0 10px 30px rgba(0,0,0,0.08); padding: 26px; }
    h1 { margin: 0 0 10px; font-size: 28px; }
    p { margin: 0 0 16px; color: var(--muted); }
    .grid { display: grid; gap: 14px; grid-template-columns: 1fr 1fr; }
    label { font-weight: 600; font-size: 14px; }
    input, select { width: 100%; padding: 10px 12px; border: 1px solid #e6e6e6; border-radius: 10px; font-size: 15px; }
    .plans { display: flex; gap: 10px; flex-wrap: wrap; }
    .pill { border: 1px solid #e6e6e6; border-radius: 999px; padding: 8px 12px; cursor: pointer; }
    .pill[data-selected="true"] { border-color: var(--accent); background: #eef2ff; }
    .cta { margin-top: 18px; display:flex; gap:10px; flex-wrap:wrap; }
    button { padding: 12px 16px; border: 0; border-radius: 12px; font-weight: 700; cursor: pointer; }
    .primary { background: var(--accent); color: white; }
    .ghost { background: #f3f3f3; }
    .foot { margin-top: 14px; font-size: 12px; color: var(--muted); }
    .heart { color: #ff4d6d; }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card">
      <h1>Hi! A tiny question…</h1>
      <p>Hi hi this is testing the github pages ✨</p>

      <div class="plans" id="plans">
        <div class="pill" data-value="Dinner at a cozy spot">Dinner 🍝</div>
        <div class="pill" data-value="Sunset walk and coffee">Walk + coffee ☕</div>
        <div class="pill" data-value="Cute surprise I think you'll love">Surprise 🎁</div>
        <div class="pill" data-value="Movie night with snacks">Movie night 🎬</div>
      </div>

      <div class="grid" style="margin-top: 14px;">
        <div>
          <label for="date">Date</label>
          <input type="date" id="date" />
        </div>
        <div>
          <label for="time">Time</label>
          <input type="time" id="time" />
        </div>
      </div>

      <div class="grid" style="margin-top: 14px;">
        <div>
          <label for="alt">If that doesn’t work, an alternative</label>
          <input type="text" id="alt" placeholder="e.g., Thursday evening or Saturday afternoon" />
        </div>
        <div>
          <label for="notes">Anything you’d like to add</label>
          <input type="text" id="notes" placeholder="Preferences, allergies, vibe…" />
        </div>
      </div>

      <div class="cta">
        <button class="primary" id="whatsappBtn">Send on WhatsApp</button>
        <button class="ghost" id="smsBtn">Send via SMS</button>
      </div>
      <div class="foot">Made with a little code and a lot of <span class="heart">♥</span></div>
    </div>
  </div>

  <script>
    // Set your phone here (international format without +). Example: Jordan 9627XXXXXXXX
    const YOUR_PHONE_INTL = "9627XXXXXXXX";

    const pills = document.querySelectorAll(".pill");
    pills.forEach(p => p.addEventListener("click", () => {
      pills.forEach(x => x.dataset.selected = "false");
      p.dataset.selected = "true";
    }));

    function buildMessage() {
      const planEl = Array.from(pills).find(p => p.dataset.selected === "true");
      const plan = planEl ? planEl.dataset.value : "A nice plan together";
      const date = document.getElementById("date").value;
      const time = document.getElementById("time").value;
      const alt = document.getElementById("alt").value.trim();
      const notes = document.getElementById("notes").value.trim();

      const dateTime = (date || time) ? `${date || "a day that works"} at ${time || "a good time"}` : "a time that’s good for you";

      let msg = `Hey! I’d love to take you out — thinking: ${plan}.\n\nAre you free on ${dateTime}?`;
      if (alt) msg += `\n\nIf not, ${alt} works too.`;
      if (notes) msg += `\n\nNotes: ${notes}`;
      msg += `\n\nIf you’re up for it, I’ll book everything. 💫`;

      return msg;
    }

    function openWhatsApp() {
      const text = encodeURIComponent(buildMessage());
      const url = `https://wa.me/${YOUR_PHONE_INTL}?text=${text}`;
      window.open(url, "_blank");
    }

    function openSMS() {
      const text = encodeURIComponent(buildMessage());
      // sms: works on mobile; may vary by platform
      const url = `sms:${YOUR_PHONE_INTL}?&body=${text}`;
      window.location.href = url;
    }

    document.getElementById("whatsappBtn").addEventListener("click", openWhatsApp);
    document.getElementById("smsBtn").addEventListener("click", openSMS);
  </script>
</body>
</html>
