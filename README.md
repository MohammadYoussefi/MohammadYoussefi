<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<title>Mohammad Youssefi - Portfolio</title>
<style>
    body {
        font-family: system-ui, -apple-system, Segoe UI, Roboto, sans-serif;
        background: #f7faff;
        color: #0f172a;
        margin: 0;
        padding: 0;
    }

    .container {
        max-width: 900px;
        margin: 40px auto;
        background: #ffffff;
        border-radius: 14px;
        padding: 40px;
        box-shadow: 0 10px 30px rgba(0, 60, 150, 0.08);
        border: 1px solid rgba(0, 90, 200, 0.1);
    }

    h1 {
        margin-top: 0;
        color: #0b3d91;
        letter-spacing: 0.5px;
    }

    h2 {
        color: #0b3d91;
        border-left: 4px solid #3b82f6;
        padding-left: 10px;
    }

    .section {
        margin-top: 30px;
    }

    .skills-grid {
        display: grid;
        grid-template-columns: repeat(2, minmax(300px, 1fr));
        gap: 8px 30px;
        margin-top: 10px;
    }

    .card {
        padding: 16px;
        border-radius: 10px;
        border: 1px solid rgba(0, 100, 200, 0.2);
        background: #f8fbff;
    }

    .footer {
        text-align: center;
        margin-top: 40px;
        color: #475569;
    }

    .links a {
        text-decoration: none;
        color: #0b3d91;
        font-weight: 500;
        margin: 0 10px;
        border-bottom: 1px solid transparent;
    }

    .links a:hover {
        border-bottom: 1px solid #0b3d91;
    }

    .center {
        text-align: center;
    }

    .separator {
        height: 1px;
        background: rgba(0, 80, 170, 0.25);
        margin: 30px 0;
        border-radius: 3px;
    }
</style>
</head>

<body>
<div class="container">

    <h1>Mohammad Youssefi</h1>
    <strong>Backend Engineer | Python & Django Specialist</strong>

    <div class="section">
        <h2>About</h2>
        <p>
            Dedicated web developer with strong focus on backend engineering using
            <b>Python</b>, <b>Django</b>, and relational databases. I emphasize performance,
            scalability, maintainability, and clarity of architecture in every project.
        </p>

        <ul>
            <li>Clean and well-structured code</li>
            <li>Production-oriented development</li>
            <li>Real-world problem solving</li>
            <li>Continuous improvement mindset</li>
        </ul>
    </div>

    <div class="separator"></div>

    <div class="section">
        <h2>Technical Expertise</h2>

        <div class="skills-grid">
            <div class="card">
                <b>Backend Development</b>
                <p>Python • Django • Django REST Framework • API Design</p>
            </div>

            <div class="card">
                <b>Frontend</b>
                <p>HTML5 • CSS3 • Tailwind CSS • JavaScript • Alpine.js</p>
            </div>

            <div class="card">
                <b>Databases</b>
                <p>MySQL • PostgreSQL</p>
            </div>

            <div class="card">
                <b>Tools & Environment</b>
                <p>Git • Docker • Linux</p>
            </div>
        </div>
    </div>

    <div class="separator"></div>

    <div class="section center">
        <h2>GitHub Overview</h2>
        <img height="170"
             src="https://github-readme-stats.vercel.app/api?username=MohammadYoussefi&show_icons=true&theme=tokyonight"
             alt="Github Stats">
    </div>

    <div class="separator"></div>

    <div class="section center">
        <h2>Contact</h2>
        <div class="links">
            <a href="https://linkedin.com/in/mohamad-youssefi-a60b8b342">LinkedIn</a>
            <a href="mailto:letshaverain@gmail.com">Email</a>
            <a href="https://t.me/Mohammadr_youssefi">Telegram</a>
        </div>
    </div>

    <p class="footer">
        Open to collaboration on meaningful and technically engaging projects.
    </p>

</div>
</body>
</html>
