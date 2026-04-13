<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maxim Bagby | Portfolio</title>
    <style>
        :root {
            --primary-blue: #2E3192;
            --accent-purple: #E8EAF6;
            --text-dark: #333;
            --white: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            line-height: 1.6;
            color: var(--text-dark);
            background-color: #f9f9fb;
        }

        header {
            background: var(--primary-blue);
            color: var(--white);
            padding: 2rem 1rem;
            text-align: center;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        .profile-section {
            display: flex;
            align-items: center;
            gap: 2rem;
            background: var(--white);
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            margin-top: -40px;
        }

        .profile-pic {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 5px solid var(--white);
            object-fit: cover;
        }

        .hero-text h1 { margin: 0; font-size: 2.5rem; }
        .hero-text p { color: var(--primary-blue); font-weight: bold; }

        .grid {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 2rem;
            margin-top: 2rem;
        }

        section {
            background: var(--white);
            padding: 1.5rem;
            border-radius: 10px;
            margin-bottom: 1.5rem;
        }

        h2 {
            border-left: 5px solid var(--primary-blue);
            padding-left: 15px;
            color: var(--primary-blue);
        }

        .timeline-item {
            border-left: 2px solid var(--accent-purple);
            padding-left: 20px;
            position: relative;
            margin-bottom: 20px;
        }

        .timeline-date {
            font-weight: bold;
            color: var(--primary-blue);
            font-size: 0.9rem;
        }

        .skill-tag {
            display: inline-block;
            background: var(--accent-purple);
            padding: 5px 15px;
            border-radius: 20px;
            margin: 5px;
            font-size: 0.9rem;
        }

        footer {
            text-align: center;
            padding: 2rem;
            background: var(--primary-blue);
            color: white;
            margin-top: 3rem;
        }

        @media (max-width: 768px) {
            .profile-section, .grid { flex-direction: column; grid-template-columns: 1fr; }
            .profile-section { text-align: center; }
        }
    </style>
</head>
<body>

<header>
    <h1>Maxim Bagby</h1>
    <p>Aspiring Athletic Medical Professional</p>
</header>

<div class="container">
    <div class="profile-section">
        <img src="your-photo.jpg" alt="Maxim Bagby" class="profile-pic"> <div class="hero-text">
            <h2>About Me</h2>
            <p>High School Sophomore | Buchholz High School</p>
            <p>I am a dedicated student-athlete pursuing a career in the athletic medical field. I pride myself on staying committed to long-term goals and professional excellence.</p>
        </div>
    </div>

    <div class="grid">
        <div class="main-content">
            <section>
                <h2>Education</h2>
                <div class="timeline-item">
                    <span class="timeline-date">2026 (Expected)</span>
                    <h3>Buchholz High School</h3>
                    <p><strong>GPA: 3.5</strong><br>
                    Relevant Coursework: Algebra 2 Honors, Biology Honors, English 2 Honors</p>
                </div>
            </section>

            <section>
                <h2>Experience & Projects</h2>
                <div class="timeline-item">
                    <span class="timeline-date">2026</span>
                    <h3>SafeStride Entrepreneurship (DECA)</h3>
                    <p>Developed and presented a product presentation for the DECA States Project, focusing on teamwork and strategic planning.</p>
                </div>
                <div class="timeline-item">
                    <span class="timeline-date">2017 - Present</span>
                    <h3>U9 Soccer Team</h3>
                    <p>Utilized problem-solving and collaboration to win championships. Recognized for leadership with a retired jersey number.</p>
                </div>
            </section>
        </div>

        <div class="sidebar">
            <section>
                <h2>Certifications</h2>
                <p><strong>Entrepreneurship & Small Business</strong><br>
                <small>Certiport Industry Recognized Certification</small></p>
            </section>

            <section>
                <h2>Soft Skills</h2>
                <span class="skill-tag">Leadership</span>
                <span class="skill-tag">Communication</span>
                <span class="skill-tag">Collaboration</span>
                <span class="skill-tag">Problem-Solving</span>
            </section>

            <section>
                <h2>Languages</h2>
                <ul>
                    <li>English (Fluent)</li>
                    <li>Spanish (Fluent)</li>
                    <li>Italian (Fluent)</li>
                </ul>
            </section>
        </div>
    </div>
</div>

<footer>
    <p>Contact: maxdabest@gmail.com | 123-456-7890</p>
    <p>&copy; 2026 Maxim Bagby</p>
</footer>

</body>
</html>
