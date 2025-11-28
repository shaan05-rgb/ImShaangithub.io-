# ImShaangithub.io- 
%%html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="x-ua-compatible" content="ie=edge">

    <title>Shaan Salman | York University Student</title>

    <meta name="description" content="Personal website of Shaan Salman, a student at York University.">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <style>
        * { box-sizing: border-box; }

        body {
            font-family: "Segoe UI", Roboto, Arial, sans-serif;
            background: #f5f8fc;
            color: #1a1a1a;
            margin: 0;
        }

        /* Navbar */
        .navbar {
            background: #0A2540;
            color: white;
            padding: 14px 28px;
            position: sticky;
            top: 0;
            z-index: 10;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 3px 8px rgba(0, 0, 0, 0.15);
        }

        .navbar-title {
            font-weight: bold;
            font-size: 1.25em;
            letter-spacing: 1px;
        }

        .navbar-links a {
            color: #dbeafe;
            text-decoration: none;
            margin-left: 18px;
            font-size: 1em;
            transition: 0.3s;
        }

        .navbar-links a:hover { color: white; }

        /* Main */
        #main {
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 20px 60px 20px;
        }

        /* Avatar */
        .avatar {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            background: linear-gradient(135deg, #0A2540, #1e3a8a);
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3em;
            font-weight: 700;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.25);
        }

        .top-section {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            gap: 26px;
            margin-bottom: 50px;
        }

        /* Title text */
        .site-title {
            font-size: 2.8em;
            font-weight: 800;
            margin: 0;
            background: linear-gradient(to right, #0A2540, #1e40af);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .site-subtitle {
            font-size: 1.2em;
            color: #475569;
            margin: 6px 0 0 0;
            font-weight: 500;
        }

        .tagline {
            font-size: 1em;
            color: #6b7280;
            margin-top: 8px;
        }

        /* Sections */
        .section-block { margin-bottom: 42px; }

        .section-title {
            font-size: 1.5em;
            font-weight: 700;
            color: #0A2540;
            border-left: 5px solid #1e40af;
            padding-left: 12px;
            margin-bottom: 18px;
        }

        .bio-text {
            font-size: 1.05em;
            line-height: 1.8;
            margin-bottom: 12px;
            text-align: justify;
        }

        /* Card */
        .card {
            background: white;
            border-radius: 10px;
            padding: 22px 25px;
            box-shadow: 0 3px 10px rgba(0, 0, 0, 0.08);
        }

        .card h4 { margin: 0 0 6px 0; color: #0A2540; }
        .muted { color: #64748b; margin: 0 0 12px 0; }

        ul { padding-left: 22px; }
        li { margin-bottom: 6px; color: #334155; }

        /* Footer */
        footer {
            margin-top: 20px;
            border-top: 1px solid #d1d5db;
            padding-top: 14px;
            text-align: center;
        }

        .footer-text {
            font-size: 0.88em;
            color: #64748b;
        }

        /* Mobile */
        @media (max-width: 650px) {
            .navbar { flex-direction: column; align-items: flex-start; padding-bottom: 20px; }
            .navbar-links { margin-top: 8px; display: flex; flex-wrap: wrap; gap: 10px; }
        }
    </style>
</head>

<body>

    <!-- NAVBAR -->
    <div class="navbar">
        <div class="navbar-title">Shaan Salman</div>
        <div class="navbar-links">
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#education">Education</a>
            <a href="#interests">Interests</a>
            <a href="#contact">Contact</a>
        </div>
    </div>

    <div id="main">

        <!-- HERO -->
        <section id="home" class="top-section">
            <div class="avatar">S</div>
            <div>
                <h1 class="site-title">Shaan Salman</h1>
                <p class="site-subtitle">York University Student</p>
                <p class="tagline">Learning. Growing. Building a future in technology.</p>
            </div>
        </section>

        <!-- ABOUT -->
        <section id="about" class="section-block">
            <h3 class="section-title">About Me</h3>
            <p class="bio-text">
                Hi! My name is <strong>Shaan Salman</strong> and I am a student at <strong>York University</strong>.
                I’m passionate about technology, solving problems, and becoming better every day.
            </p>
            <p class="bio-text">
                I enjoy exploring how computers, websites, and digital systems work.
                I’m always trying new ideas, learning new skills, and building confidence through small projects.
            </p>
        </section>

        <!-- EDUCATION -->
        <section id="education" class="section-block">
            <h3 class="section-title">Education</h3>
            <div class="card">
                <h4>York University</h4>
                <p class="muted">Undergraduate Student</p>
                <p class="bio-text">
                    At York, I am developing strong foundations in technology and critical thinking.
                    My courses teach me how digital systems work, how information is structured,
                    and how technology helps people and organizations solve real problems.
                </p>
            </div>
        </section>

        <!-- INTERESTS -->
        <section id="interests" class="section-block">
            <h3 class="section-title">Interests</h3>
            <p class="bio-text">I like learning about:</p>

            <ul>
                <li>How websites are made with HTML and CSS</li>
                <li>Programming step-by-step and problem solving</li>
                <li>How technology improves daily life</li>
            </ul>

            <p class="bio-text">
                I enjoy experimenting, building new things, and slowly growing my skills.
            </p>
        </section>

        <!-- CONTACT -->
        <section id="contact" class="section-block">
            <h3 class="section-title">Contact</h3>
            <p class="bio-text">
                You can reach me at:<br>
                <strong>shaan05@my.yorku.ca</strong>
            </p>
        </section>

        <footer>
            <p class="footer-text">© <span id="year"></span> Shaan Salman • York University Student</p>
        </footer>
    </div>

    <script>
        document.getElementById('year').textContent = new Date().getFullYear();
    </script>

</body>

</html>
