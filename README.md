<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Artemis IDE – Download</title>
  <style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Inter', sans-serif;
}

body {
  background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
  color: white;
}

.navbar {
  display: flex;
  justify-content: space-between;
  padding: 20px 40px;
}

.logo {
  font-size: 1.8rem;
  font-weight: 700;
}

.navbar a {
  color: white;
  text-decoration: none;
  margin-left: 20px;
  opacity: 0.8;
}

.hero {
  text-align: center;
  padding: 120px 20px;
}

.hero h2 {
  font-size: 3rem;
}

.hero p {
  margin: 15px 0 30px;
  opacity: 0.85;
}

button, .btn {
  padding: 15px 35px;
  border-radius: 30px;
  background: #6c63ff;
  color: white;
  text-decoration: none;
  border: none;
  font-size: 1rem;
  cursor: pointer;
  display: inline-block;
  transition: 0.2s;
}

button:hover, .btn:hover {
  transform: translateY(-3px);
}

.features {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
  padding: 80px 40px;
}

.card {
  background: rgba(255,255,255,0.08);
  padding: 30px;
  border-radius: 20px;
}

.download {
  text-align: center;
  padding: 80px 20px;
}

.download-buttons {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
  margin-top: 30px;
}

.note {
  margin-top: 20px;
  opacity: 0.6;
}

footer {
  text-align: center;
  padding: 20px;
  opacity: 0.6;
}
  </style>
</head>
<body>

  <header class="navbar">
    <h1 class="logo">Artemis</h1>
    <nav>
      <a href="#features">Features</a>
      <a href="#download">Download</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Artemis IDE</h2>
    <p>Modern. Fast. Built for Web Developers.</p>
    <button id="autoDownload">Download for Your OS</button>
  </section>

  <section id="features" class="features">
    <div class="card">
      <h3>⚡ Performance</h3>
      <p>Lightweight and fast startup.</p>
    </div>
    <div class="card">
      <h3>🎨 Modern Design</h3>
      <p>Clean UI with developer focus.</p>
    </div>
    <div class="card">
      <h3>🧩 Web Ready</h3>
      <p>Perfect for HTML, CSS & JavaScript.</p>
    </div>
  </section>

  <section id="download" class="download">
    <h2>Download Artemis</h2>

    <div class="download-buttons">
      <a href="https://download2283.mediafire.com/qcmb49lzlv1gqmCzSC4w2cS9cgY_C_qPDhBoxUCLvqxOBeFbo3vzYtJHSxX6ftq5TmzYtsu1XtogmPw_3rcAeVThywbpx_WVVFQbPvx5byEym9daBnbM_p-jX6Mv1A0cdMoOoNQz9NsOeRNbemVGblZ880gN2EwikhjkuvuLbM0/4o45333e489l8ka/ArtemisIDE-StableBuild.zip" class="btn">🪟 Windows</a>
      <a href="https://download2283.mediafire.com/qcmb49lzlv1gqmCzSC4w2cS9cgY_C_qPDhBoxUCLvqxOBeFbo3vzYtJHSxX6ftq5TmzYtsu1XtogmPw_3rcAeVThywbpx_WVVFQbPvx5byEym9daBnbM_p-jX6Mv1A0cdMoOoNQz9NsOeRNbemVGblZ880gN2EwikhjkuvuLbM0/4o45333e489l8ka/ArtemisIDE-StableBuild.zip" class="btn">🍎 macOS</a>
      <a href="https://download2283.mediafire.com/qcmb49lzlv1gqmCzSC4w2cS9cgY_C_qPDhBoxUCLvqxOBeFbo3vzYtJHSxX6ftq5TmzYtsu1XtogmPw_3rcAeVThywbpx_WVVFQbPvx5byEym9daBnbM_p-jX6Mv1A0cdMoOoNQz9NsOeRNbemVGblZ880gN2EwikhjkuvuLbM0/4o45333e489l8ka/ArtemisIDE-StableBuild.zip" class="btn">🐧 Linux</a>
    </div>

    <p class="note">Version 1.0 • Free • Offline Installer</p>
  </section>

  <footer>
    <p>© 2025 Artemis IDE</p>
  </footer>
  <script>
const button = document.getElementById("autoDownload");

button.addEventListener("click", () => {
  alert("Welcome to Artemis IDE 🚀");
});
  </script>
</body>
</html>
