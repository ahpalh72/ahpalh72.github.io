<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abdul Hakeem | Developer</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        :root { --bg:#0d1117; --card:#161b22; --text:#c9d1d9; --accent:#58a6ff; --green:#238636; }
        * { margin:0; padding:0; box-sizing:border-box; }
        body { font-family:'Poppins',sans-serif; background:var(--bg); color:var(--text); line-height:1.6; overflow-x:hidden; }
        .container { max-width:1100px; margin:0 auto; padding:20px; }
        header { min-height:100vh; display:flex; align-items:center; justify-content:center; text-align:center;
                 background:linear-gradient(135deg,#1f6feb,#0d1117); position:relative; }
        .hero h1 { font-size:4.5rem; font-weight:700; margin-bottom:10px; animation:fadeInDown 1s; }
        .hero h1 span { color:#58a6ff; }
        .hero p { font-size:1.5rem; margin:15px 0; animation:fadeInUp 1s 0.3s backwards; }
        .socials a { color:white; font-size:2rem; margin:0 15px; transition:0.3s; }
        .socials a:hover { transform:translateY(-8px); color:#58a6ff; }
        .section { padding:80px 20px; animation:fadeIn 1.5s; }
        .about,.skills { background:var(--card); margin:30px 0; padding:40px; border-radius:16px; border:1px solid #30363d; }
        h2 { font-size:2.5rem; color:#58a6ff; margin-bottom:30px; text-align:center; }
        .skills-grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(120px,1fr)); gap:20px; text-align:center; }
        .skill-item { background:#21262d; padding:20px; border-radius:12px; transition:0.3s; }
        .skill-item:hover { transform:translateY(-10px); background:#238636; }
        footer { text-align:center; padding:50px; font-size:1.1rem; }
        @keyframes fadeInDown { from{opacity:0;transform:translateY(-50px)} to{opacity:1;transform:translateY(0)} }
        @keyframes fadeInUp { from{opacity:0;transform:translateY(50px)} to{opacity:1;transform:translateY(0)} }
        @keyframes fadeIn { from{opacity:0} to{opacity:1} }
        @media(max-width:768px){ .hero h1{font-size:3rem} .hero p{font-size:1.2rem} }
    </style>
</head>
<body>
    <header>
        <div class="hero">
            <h1>Hi, I'm <span>Abdul Hakeem</span> <i class="fas fa-hand-sparkles"></i></h1>
            <p>BSCS Student</p>
            <p>Web & Mobile App Developer • React • Flutter • Python</p>
            <div class="socials" style="margin-top:30px;">
                <a href="https://github.com/ahpalh72" target="_blank"><i class="fab fa-github"></i></a>
                <a href="mailto:ahpalh72@gmail.com"><i class="fas fa-envelope"></i></a>
                <a href="https://linkedin.com/in/ahpalh" target="_blank"><i class="fab fa-linkedin"></i></a>
            </div>
        </div>
    </header>

    <div class="container">
        <div class="about section">
            <h2>About Me</h2>
            <p style="font-size:1.2rem;text-align:center;">
                Undergraduate Computer Science student at <strong>Shah Abdul Latif University, Khairpur Mir's, Sindh, Pakistan</strong>.<br>
                Passionate about building real-world web and mobile applications. Currently learning and working with React, Flutter, Firebase, and Python.<br>
                Open to internships & freelance opportunities!
            </p>
        </div>

        <div class="skills section">
            <h2>Skills & Tools</h2>
            <div class="skills-grid">
                <div class="skill-item">HTML/CSS</div>
                <div class="skill-item">JavaScript</div>
                <div class="skill-item">React.js</div>
                <div class="skill-item">Flutter</div>
                <div class="skill-item">Python</div>
                <div class="skill-item">Firebase</div>
                <div class="skill-item">Git & GitHub</div>
                <div class="skill-item">REST APIs</div>
            </div>
        </div>

        <div class="section" style="text-align:center;">
            <h2>Projects Coming Soon!</h2>
            <p style="font-size:1.3rem;">Full-stack apps, mobile apps, and open-source contributions are on the way…</p>
        </div>
    </div>

    <footer>
        Made with <i class="fas fa-heart" style="color:#e91e63;"></i> by Abdul Hakeem<br>
        © 2025 | Khairpur Mir's, Sindh
    </footer>
</body>
</html>
