<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Profile – Srinivasan Packirisamy</title>

<style>
:root {
  --text-main: #111;
  --text-muted: #6b7280;
  --border-light: #e5e7eb;
  --bg-light: #fafafa;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  background: #fff;
  color: var(--text-main);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Inter, sans-serif;
  line-height: 1.6;
}

.container {
  max-width: 720px;
  margin: 60px auto;
  padding: 0 24px;
}

/* ---------- Header ---------- */
.header {
  display: flex;
  align-items: center;
  gap: 16px;
  margin-bottom: 32px;
}

.avatar {
  width: 56px;
  height: 56px;
  border-radius: 50%;
  background: #ddd;
  object-fit: cover;
}

.name {
  font-size: 1.4rem;
  font-weight: 600;
}

.meta {
  font-size: 0.9rem;
  color: var(--text-muted);
}

/* ---------- Sections ---------- */
.section {
  margin-top: 48px;
}

.section h2 {
  font-size: 0.85rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  color: var(--text-muted);
  margin-bottom: 16px;
}

/* ---------- About ---------- */
.about {
  font-size: 1rem;
}

/* ---------- Timeline ---------- */
.timeline-item {
  display: grid;
  grid-template-columns: 90px 1fr;
  gap: 16px;
  margin-bottom: 20px;
}

.year {
  font-size: 0.85rem;
  color: var(--text-muted);
}

.item-title {
  font-weight: 500;
}

.item-sub {
  font-size: 0.9rem;
  color: var(--text-muted);
}

/* ---------- Writing Card ---------- */
.card {
  display: flex;
  gap: 16px;
  border: 1px solid var(--border-light);
  border-radius: 8px;
  padding: 12px;
  margin-top: 8px;
}

.card img {
  width: 80px;
  height: 60px;
  border-radius: 6px;
  background: #ddd;
  object-fit: cover;
}

.card-title {
  font-size: 0.95rem;
  font-weight: 500;
}

.card-meta {
  font-size: 0.8rem;
  color: var(--text-muted);
}

/* ---------- Links ---------- */
a {
  color: inherit;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* ---------- Contact ---------- */
.contact-list div {
  margin-bottom: 8px;
  font-size: 0.9rem;
  color: var(--text-muted);
}

/* ---------- Footer spacing ---------- */
.footer-space {
  height: 80px;
}
</style>
</head>

<body>

<div class="container">

  <!-- Header -->
  <div class="header">
    <img class="avatar" src="https://via.placeholder.com/150" alt="Profile"/>
    <div>
      <div class="name">Srinivasan Packirisamy</div>
      <div class="meta">Software Engineer in India · <a href="#">srinivasan.com</a></div>
    </div>
  </div>

  <!-- About -->
  <div class="section">
    <h2>About</h2>
    <p class="about">
      I’m a passionate UX designer striving to create intuitive and engaging experiences.
      I’m a big believer that things can always be simpler than we think.
    </p>
  </div>

  <!-- Work Experience -->
  <div class="section">
    <h2>Work Experience</h2>

    <div class="timeline-item">
      <div class="year">2017 — Now</div>
      <div>
        <div class="item-title">Manager at Cognizant ↗</div>
        <div class="item-sub">Chennai, India</div>
      </div>
    </div>

    <div class="timeline-item">
      <div class="year">2015 — 2017</div>
      <div>
        <div class="item-title">Senior Software Engineer at Plintron↗</div>
        <div class="item-sub">Chennai, India</div>
      </div>
    </div>
    <div class="timeline-item">
      <div class="year">2009 — 2014</div>
      <div>
        <div class="item-title">Software Engineer at ShipNet↗</div>
        <div class="item-sub">Chennai, India</div>
      </div>
    </div>
  </div>

  <!-- Writing -->
  <div class="section">
    <h2>Writing</h2>

    <div class="timeline-item">
      <div class="year">2023</div>
      <div>
        <div class="item-title">Exploring the Intersection of Design and Technology ↗</div>
        <div class="item-sub">Collaboration with Mia, Leo, and Ava</div>

        <div class="card">
          <img src="https://via.placeholder.com/160x120" alt="">
          <div>
            <div class="card-title">This is a site title that can go…</div>
            <div class="card-meta">1 min read</div>
          </div>
        </div>
      </div>
    </div>
    <div class="timeline-item">
      <div class="year">2018</div>
      <div class="item-title">The Power of Visual Storytelling ↗</div>
    </div>
  </div>

  <!-- Speaking -->
  <div class="section">
    <h2>Speaking</h2>

    <div class="timeline-item">
      <div class="year">2024</div>
      <div>
        <div class="item-title">---↗</div>
        <div class="item-sub">---</div>
      </div>
    </div>
  </div>

  <!-- Side Projects -->
  <div class="section">
    <h2>Side Projects</h2>

    <div class="timeline-item">
      <div class="year">2021</div>
      <div class="item-title">---- ↗</div>
    </div>  
  </div>

  <!-- Education -->
  <div class="section">
    <h2>Education</h2>

    <div class="timeline-item">
      <div class="year">2010</div>
      <div>
        <div class="item-title">Master of Computer Application</div>
        <div class="item-sub">Anna University, Chennai, India</div>
      </div>
    </div>
  </div>

  <!-- Contact -->
  <div class="section">
    <h2>Contact</h2>
    <div class="contact-list">
      <div>Instagram · <a href="#">username ↗</a></div>
      <div>Figma · <a href="#">username ↗</a></div>
      <div>X · <a href="#">username ↗</a></div>
      <div>Bluesky · <a href="#">username ↗</a></div>
    </div>
  </div>

  <div class="footer-space"></div>
</div>

<script>
// Reserved for future interactivity (dark mode, filters, etc.)
</script>

</body>
</html>
