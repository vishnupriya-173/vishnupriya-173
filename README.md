<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Vishnupriya M — Software Engineer</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
html{ scroll-behavior: smooth; }   /* <-- IMPORTANT */

:root{
  --bg:#ffffff;
  --card:#f9fafc;
  --text:#222;
  --muted:#5f6c7b;
  --accent:#6c63ff;
  --accent-light:#ecebff;
  --radius:14px;
  --shadow:0 8px 24px rgba(0,0,0,0.08);
  --max-width:1100px;
}

*{box-sizing:border-box;margin:0;padding:0;}

body{
  font-family:'Poppins',sans-serif;
  background:var(--bg);
  color:var(--text);
  line-height:1.6;
  display:flex;
  justify-content:center;
  padding:40px 20px;
}

.wrap{width:100%;max-width:var(--max-width)}

header{
  display:flex;justify-content:space-between;align-items:center;margin-bottom:40px;
}

.brand{display:flex;align-items:center;gap:12px;}

.logo{
  width:56px;height:56px;border-radius:14px;
  background:linear-gradient(135deg,var(--accent),#00c4ff);
  display:flex;align-items:center;justify-content:center;
  color:white;font-weight:700;font-size:20px;
  box-shadow:var(--shadow);
}

nav{display:flex;gap:12px;}

.btn{
  text-decoration:none;
  padding:10px 16px;
  border-radius:10px;
  font-weight:600;
  font-size:14px;
  border:1px solid #e4e7eb;
  color:var(--muted);
}

.btn.primary{
  background:var(--accent);
  color:white;
  border:none;
}

main.hero{
  display:grid;
  grid-template-columns:1fr 340px;
  gap:32px;
}

.profile-card{
  background:var(--card);
  border-radius:var(--radius);
  padding:24px;
  box-shadow:var(--shadow);
  display:grid;
  grid-template-columns:120px 1fr;
  gap:22px;
}

.avatar{
  width:110px;
  height:110px;
  border-radius:50%;
  overflow:hidden;
  border:3px solid white;
  box-shadow:0 6px 16px rgba(108,99,255,0.25);
}

.avatar img{
  width:100%;
  height:100%;
  object-fit:cover;
}

.card{
  background:var(--card);
  border-radius:var(--radius);
  padding:20px;
  box-shadow:var(--shadow);
  margin-top:32px;
}

.projects{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:16px;
  margin-top:10px;
}

.project{
  background:white;
  border-radius:10px;
  padding:16px;
  box-shadow:0 3px 10px rgba(0,0,0,0.05);
}

.chip{
  background:var(--accent-light);
  color:var(--accent);
  padding:6px 10px;
  border-radius:999px;
  font-size:13px;
  font-weight:600;
}

@media(max-width:900px){
  main.hero{grid-template-columns:1fr;}
}
</style>
</head>

<body>
<div class="wrap">

<header>
  <div class="brand">
    <div class="logo">VP</div>
    <div>
      <h1>Vishnupriya M</h1>
      <p>B.E - Electronics and Communication Engineer</p>
    </div>
  </div>

  <!-- ✅ FIXED NAVBAR ORDER -->
  <nav>
    <a class="btn" href="#education">Education</a>
    <a class="btn" href="#projects">Projects</a>
    <a class="btn" href="#contact">Contact</a>
    <a class="btn primary" href="YOUR_RESUME_LINK">Resume</a>
  </nav>
</header>

<main class="hero">
<div class="intro">
<h2>Passionate ECE Engineer with a focus on web development and programming.</h2>
<p class="lead">
I’m a recent Electronics and Communication Engineering graduate with hands-on experience in 
<strong>Java, HTML, and CSS</strong>. I enjoy designing clean, responsive websites and building 
efficient programs that combine creativity with technical precision.
</p>
</div>

<div class="profile-card">

  <div class="avatar">
    <img src="F:\vishnupriya DOC\portfolio-main\portfolio-main\Vishnupriya_image .jpeg"
         alt="Vishnupriya M">
  </div>

  <div>
    <strong style="font-size:18px;">Vishnu Priya</strong><br/>
    <span style="color:var(--muted);font-size:13px;">
      Web Development & Programming
    </span>

    <div style="margin-top:12px;">
      <div style="font-size:13px;color:var(--muted);">Location</div>
      <strong>Thiruvallur, India</strong>
    </div>

    <div style="margin-top:12px;">
      <div style="font-size:13px;color:var(--muted);">Skills</div>
      <div style="margin-top:6px;">
        <span class="chip">Java</span>
        <span class="chip">HTML</span>
        <span class="chip">CSS</span>
        <span class="chip">Python</span>
        <span class="chip">Linux</span>
      </div>
    </div>

    <div style="margin-top:12px;display:flex;gap:10px;">
      <a class="btn primary" href="YOUR_LINKEDIN_URL">LinkedIn</a>
      <a class="btn" href="YOUR_GITHUB_URL">GitHub</a>
    </div>
  </div>

</div>
</main>

<!-- ✅ EDUCATION (FIRST — SAME CONTENT AS YOU GAVE) -->
<section id="education" class="card">
<h3>Education</h3>
<ul style="margin-top:12px; color:var(--muted); padding-left:18px;">
<li>
<strong>B.E - Electronics and Communication Engineering-2026 (upto 6th semester)</strong> — CGPA: 8.34<br>
Completed with strong academic performance and hands-on project experience in Embedded Systems and IoT.
</li>
<li><strong>Higher Secondary Education-2022 (12th Grade)</strong> — 88.4%</li>
<li><strong>Secondary School Education-2020 (10th Grade)</strong> — 84.4%</li>
</ul>
</section>

<!-- ✅ PROJECTS (SECOND — YOUR SAME PROJECTS) -->
<section id="projects" class="card">
  <h3>Projects</h3>
  <div class="projects">

    <div class="project">
      <h4>Automatic Switch Off Charger Using Voltage Doubler</h4>
      <p>
        This charger is efficient and prevents accidents by switching off the battery 
        once it reaches a threshold level of 13.2V.
      </p>
      <div style="margin-top:8px;display:flex;gap:6px;flex-wrap:wrap;">
        <span class="chip">Voltage Doubler Circuit</span>
        <span class="chip">Relay Module</span>
        <span class="chip">PCB & Soldering</span>
      </div>
    </div>

    <div class="project">
      <h4>Smart Scale Electricity Production</h4>
      <p>
        Used a horizontal windmill with an MPPT charge controller to generate electricity 
        with minimal power loss.
      </p>
      <div style="margin-top:8px;display:flex;gap:6px;flex-wrap:wrap;">
        <span class="chip">Horizontal Windmill</span>
        <span class="chip">MPPT Controller</span>
        <span class="chip">Digital Tachometer</span>
      </div>
    </div>

    <div class="project">
      <h4>Gemini AI Chatbot</h4>
      <p>
        Built an AI-powered chatbot using Gemini API with dynamic user interaction.
        Integrated real-time API communication to generate intelligent responses and 
        improve engagement.
      </p>
      <div style="margin-top:8px;display:flex;gap:6px;flex-wrap:wrap;">
        <span class="chip">Gemini API</span>
        <span class="chip">JavaScript</span>
        <span class="chip">HTML & CSS</span>
      </div>
    </div>

    <div class="project">
      <h4>Web Development Projects</h4>
      <p>
        Designed and developed a personal portfolio, perfume web application, and 
        interactive calculator using modern web technologies.
      </p>
      <div style="margin-top:8px;display:flex;gap:6px;flex-wrap:wrap;">
        <span class="chip">HTML</span>
        <span class="chip">CSS</span>
        <span class="chip">JavaScript</span>
      </div>
    </div>

  </div>
</section>

<!-- ✅ CONTACT (THIRD — SAME FORM) -->
<section id="contact" class="card">
<h3>Contact</h3>
<p style="color:var(--muted)">
Feel free to reach out by filling out the form below. I’ll get back to you as soon as possible.
</p>

<form style="margin-top:12px; display:flex; flex-direction:column; gap:10px;">
<input type="text" name="name" placeholder="Your Name" required>
<input type="email" name="email" placeholder="Your Email" required>
<input type="text" name="subject" placeholder="Subject">
<textarea name="message" placeholder="Your Message" rows="4" required></textarea>
<button type="submit" class="btn primary">Send Message</button>
</form>
</section>

<footer style="margin-top:40px;text-align:center;color:var(--muted);">

</footer>

</div>
</body>
</html>
