## Hi there 👋
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sugarplume Study Hub</title>
  <style>
    :root {
      --bg: #f5f7fb;
      --text: #333;
      --card: #ffffff;
      --primary: #6c63ff;
    }body.dark {
  --bg: #121212;
  --text: #f1f1f1;
  --card: #1e1e1e;
  --primary: #4dd0e1;
}

body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: var(--bg);
  color: var(--text);
  transition: 0.3s;
}

header {
  background: linear-gradient(135deg, #6c63ff, #4dd0e1);
  color: white;
  padding: 40px 20px;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 2.5em;
}

nav {
  display: flex;
  justify-content: center;
  background: var(--card);
  padding: 10px;
  gap: 20px;
  position: sticky;
  top: 0;
}

nav a {
  text-decoration: none;
  color: var(--text);
  font-weight: bold;
}

.toggle-btn {
  position: absolute;
  right: 15px;
  top: 10px;
  padding: 5px 10px;
  cursor: pointer;
  border-radius: 8px;
  border: none;
  background: var(--primary);
  color: white;
}

section {
  padding: 40px 20px;
  max-width: 1000px;
  margin: auto;
}

.card {
  background: var(--card);
  padding: 20px;
  margin: 15px 0;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.08);
}

.btn {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 15px;
  background: var(--primary);
  color: white;
  border-radius: 8px;
  text-decoration: none;
}

footer {
  text-align: center;
  padding: 20px;
  background: #222;
  color: white;
  margin-top: 40px;
}

.quote {
  font-style: italic;
  color: gray;
}

  </style>
</head>
<body><header>
  <h1>Sugarplume Study Hub</h1>
  <p>Your free place for study schedules, notes & motivation</p>
  <button class="toggle-btn" onclick="toggleDark()">Dark Mode</button>
</header><nav>
  <a href="#home">Home</a>
  <a href="#schedules">Schedules</a>
  <a href="#notes">Notes</a>
  <a href="#motivation">Motivation</a>
  <a href="#about">About</a>
</nav><section id="home">
  <h2>Welcome 👋</h2>
  <div class="card">
    <p>This website helps students stay organized with ready-made study schedules, notes, and motivation to stay consistent.</p>
  </div>
</section><section id="schedules">
  <h2>Study Schedules 📚</h2>  <div class="card">
    <h3>10th Class Weekly Plan</h3>
    <p>Balanced schedule for all subjects with revision days.</p>
    <a class="btn" href="#">Download PDF</a>
  </div>  <div class="card">
    <h3>Exam Crash Plan</h3>
    <p>7-day focused revision plan for exams.</p>
    <a class="btn" href="#">Download PDF</a>
  </div>
</section><section id="notes">
  <h2>Notes 📝</h2>
  <div class="card">
    <p>Upload your subject notes here (PDFs or links).</p>
  </div>
</section><section id="motivation">
  <h2>Daily Motivation 💡</h2>  <div class="card">
    <p class="quote">"Small progress every day adds up to big results."</p>
  </div>  <div class="card">
    <p class="quote">"Don’t stop until you’re proud."</p>
  </div>  <div class="card">
    <p class="quote">"Someone out there is studying harder than you right now."</p>
  </div>
</section><section id="about">
  <h2>About Me ✨</h2>
  <div class="card">
    <p>Hi! I create simple study schedules to help students stay organized and improve their academic performance.</p><a class="btn" href="https://wa.me/0000000000">Contact on WhatsApp</a>

  </div>
</section><footer>
  <p>© 2026 Sugarplume Study Hub | Made with ❤️ for students</p>
</footer><script>
function toggleDark() {
  document.body.classList.toggle('dark');
}
</script></body>
</html>
<!--
**sugarplume/sugarplume** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
