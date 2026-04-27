# Ex01 Portfolio
## Date: 27/04/2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
## index.html
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Subbiah S Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <header>
        <h1>SUBBIAH S</h1>
        <p>Aspiring Data Analyst</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#projects">Projects</a>
        <a href="#experience">Experience</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>Career Objective</h2>
        <p>
            Aspiring Data Analyst with skills in Python and Power BI, passionate about transforming data into actionable
            insights. Eager to apply analytical skills and grow within a dynamic team.
        </p>
    </section>

    <section id="education">
        <h2>Education</h2>
        <div class="card">
            <h3>Saveetha Engineering College, Chennai, India</h3>
            <p style="margin-bottom: 5px;"><strong>B.Tech Information Technology</strong> | CGPA: 7.7/10</p>
            <p>July 2023 - May 2027</p>
        </div>
    </section>

    <section id="projects">
        <h2>Project Experience</h2>
        <div class="card">
            <h3>Automated Food Quality Analysis using Image Processing & Machine Learning</h3>
            <p style="margin-bottom: 10px;"><strong>Sep 2025 – Dec 2025</strong></p>
            <ul class="list-details">
                <li>Trained and deployed a production-grade YOLOv8 & Random Forest model achieving 96.7% accuracy, with
                    a focus on model optimization for real-time inference (&lt;0.5s).</li>
                <li>Developed a responsive frontend dashboard with React and Chart.js, providing users with visual
                    analytics, historical trend tracking.</li>
                <li>Architected a complete computer vision pipeline from image capture to result visualization,
                    specializing in feature extraction for agricultural quality assessment.</li>
            </ul>
        </div>
    </section>

    <section id="experience">
        <h2>Internship Experience</h2>
        <div class="card">
            <h3>Data Analytics Internship</h3>
            <p style="margin-bottom: 10px;"><strong>Re-tech Solutions PVT Ltd, Chennai</strong> | Jan 2025 – Feb 2025
            </p>
            <ul class="list-details">
                <li>Developed interactive Power BI dashboards to analyse quality control data and identify performance
                    trends.</li>
                <li>Applied data analytics techniques to detect defects, monitor process efficiency, and support
                    decision-making.</li>
                <li>Improved reporting accuracy by visualizing key quality metrics and validating insights for process
                    optimization.</li>
            </ul>
        </div>
    </section>

    <section id="skills">
        <h2>Skills & Interests</h2>
        <div class="card" style="margin-bottom: 30px;">
            <p style="margin-bottom: 10px;"><strong>Programming:</strong> Python, DBMS, Java, HTML, CSS.</p>
            <p style="margin-bottom: 10px;"><strong>Software Tools:</strong> VS Code, Vibe Coding, AWS Cloud, Unix Linux
                OS.</p>
            <p style="margin-bottom: 10px;"><strong>Soft Skills:</strong> Problem Solving, Critical Thinking,
                Leadership, Teamwork, Communication, Hands-on Prototyping.</p>
            <p><strong>Areas of Interest:</strong> Python & Data Structures/Algorithms | Machine Learning & Data
                Science/Analyst.</p>
        </div>

        <h3 style="color: var(--accent); margin-bottom: 15px; font-size: 1.5rem;">Core Technologies</h3>
        <ul class="skill-tags">
            <li>Python</li>
            <li>Power BI</li>
            <li>Machine Learning</li>
            <li>Data Analytics</li>
            <li>HTML/CSS</li>
            <li>AWS</li>
            <li>DBMS</li>
        </ul>
    </section>

    <section id="achievements">
        <h2>Achievements</h2>
        <div class="card">
            <ul class="list-details">
                <li>Contributed in various college-level technical symposiums, showcasing interest in emerging
                    technologies.</li>
                <li>Attended technical workshops to gain additional knowledge and hands-on experience.</li>
                <li>Awarded Certificate of Contributed in the Paper Presentation "Why Math in Engineering?" organized by
                    the Department of Mathematics.</li>
                <li>Contributed in IBM Z Datathon 2025 - A Global Datathon Event held in our College Campus.</li>
                <li><strong>Hackathon, Annapoorna Engineering College 2025:</strong> Contributed in a team-based
                    hackathon focused on problem-solving and rapid prototyping. Collaborated with teammates to design
                    and implement a solution within a limited timeframe.</li>
            </ul>
        </div>
    </section>

    <section id="certifications">
        <h2>Certifications</h2>
        <div class="card">
            <ul class="list-details">
                <li>NPTEL - Industrial Internet of Things (IIoT), Jul-Oct 2024</li>
                <li>Infosys - Unix Linux OS - Unix Fundamentals, May 6 2024</li>
                <li>LinkedIn Learning - Introduction to Career Skills in Data Analytics - Jan 24, 2025</li>
                <li>AWS Academy - AWS Academy Graduate - Cloud Foundations - Training Badge, June 11, 2025</li>
                <li>IBM - Big Data Foundations - Level 1, Jan 2026</li>
            </ul>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: subbiahs1904@gmail.com</p>
        <p>Phone: +91 6382570076</p>
        <p>Location: Chennai, India</p>
        <p style="margin-top: 15px;">
            <a href="#" style="color: var(--accent); text-decoration: none; font-weight: 600;">LinkedIn</a>
            &nbsp;|&nbsp;
            <a href="#" style="color: var(--accent); text-decoration: none; font-weight: 600;">GitHub</a>
        </p>
    </section>

    <footer>
        <p>© 2026 SUBBIAH S</p>
    </footer>

</body>

</html>
```


## Style.css
```
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');

:root {
    --bg-color: #111115;
    /* Deeper, rich dark background */
    --text-primary: #f8fafc;
    --text-secondary: #a1a1aa;
    --accent: #a855f7;
    /* Vibrant Purple/Violet */
    --accent-gradient: linear-gradient(135deg, #a855f7, #ec4899);
    /* Purple to Pink */
    --card-bg: #18181b;
    --card-border: rgba(255, 255, 255, 0.08);
}

html {
    scroll-behavior: smooth;
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Inter', sans-serif;
    background-color: var(--bg-color);
    color: var(--text-primary);
    line-height: 1.6;
    overflow-x: hidden;
}

header {
    background: var(--card-bg);
    padding: 100px 20px;
    text-align: center;
    border-bottom: 1px solid var(--card-border);
    position: relative;
    overflow: hidden;
}

header::before {
    content: '';
    position: absolute;
    top: -50%;
    left: -50%;
    width: 200%;
    height: 200%;
    background: radial-gradient(circle, rgba(168, 85, 247, 0.05) 0%, transparent 60%);
    pointer-events: none;
}

header h1 {
    font-size: 3.5rem;
    font-weight: 700;
    background: var(--accent-gradient);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 15px;
    animation: fadeInDown 0.8s ease-out;
}

header p {
    font-size: 1.3rem;
    color: var(--text-secondary);
    font-weight: 300;
    animation: fadeInUp 0.8s ease-out 0.2s both;
}

nav {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    background: rgba(17, 17, 21, 0.85);
    /* rgba for --bg-color */
    backdrop-filter: blur(12px);
    position: sticky;
    top: 0;
    z-index: 1000;
    border-bottom: 1px solid var(--card-border);
    padding: 15px 0;
}

nav a {
    color: var(--text-primary);
    padding: 10px 20px;
    margin: 5px;
    text-decoration: none;
    font-weight: 600;
    border-radius: 8px;
    transition: all 0.3s ease;
}

nav a:hover {
    background: var(--accent-gradient);
    color: white;
    transform: translateY(-2px);
    box-shadow: 0 4px 15px rgba(168, 85, 247, 0.4);
}

section {
    max-width: 900px;
    margin: 80px auto;
    padding: 0 20px;
    animation: fadeIn 1s ease-out;
}

section h2 {
    font-size: 2.2rem;
    color: var(--accent);
    margin-bottom: 40px;
    position: relative;
    display: inline-block;
}

section h2::after {
    content: '';
    position: absolute;
    width: 60%;
    height: 4px;
    bottom: -10px;
    left: 0;
    background: var(--accent-gradient);
    border-radius: 2px;
}

section p {
    color: var(--text-secondary);
    font-size: 1.15rem;
}

.card {
    background: var(--card-bg);
    padding: 30px;
    margin: 25px 0;
    border-radius: 16px;
    border: 1px solid var(--card-border);
    transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
    cursor: pointer;
}

.card:hover {
    transform: translateY(-6px);
    box-shadow: 0 15px 35px rgba(0, 0, 0, 0.4);
    border-color: rgba(168, 85, 247, 0.5);
}

.card h3 {
    color: var(--text-primary);
    font-size: 1.5rem;
    margin-bottom: 12px;
}

.card p {
    font-size: 1.05rem;
    color: var(--text-secondary);
}

.list-details {
    list-style: disc;
    margin-left: 20px;
    margin-top: 15px;
}

.list-details li {
    color: var(--text-secondary);
    font-size: 1.05rem;
    margin-bottom: 10px;
    line-height: 1.7;
}

.list-details li strong {
    color: var(--text-primary);
}

.skill-tags {
    list-style: none;
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    margin-top: 20px;
}

.skill-tags li {
    background: rgba(168, 85, 247, 0.1);
    color: var(--accent);
    padding: 12px 25px;
    border-radius: 30px;
    font-weight: 600;
    font-size: 1.1rem;
    border: 1px solid rgba(168, 85, 247, 0.2);
    transition: all 0.3s ease;
    cursor: default;
}

.skill-tags li:hover {
    background: var(--accent-gradient);
    color: white;
    transform: scale(1.05);
    box-shadow: 0 5px 15px rgba(168, 85, 247, 0.3);
}

#contact p {
    margin: 15px 0;
    font-size: 1.15rem;
    display: flex;
    align-items: center;
    gap: 10px;
}

footer {
    text-align: center;
    background: var(--card-bg);
    color: var(--text-secondary);
    padding: 40px;
    margin-top: 80px;
    border-top: 1px solid var(--card-border);
    font-size: 1rem;
}

/* Animations */
@keyframes fadeInDown {
    from {
        opacity: 0;
        transform: translateY(-30px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes fadeIn {
    from {
        opacity: 0;
    }

    to {
        opacity: 1;
    }
}
```

## OUTPUT
<img width="1890" height="879" alt="image" src="https://github.com/user-attachments/assets/07399f60-a5f4-4163-9ef3-e792b7e4cf60" />
https://portfolio-subbiah-19.vercel.app/

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
