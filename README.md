<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sai Charan Karra | Data Engineer Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Roboto', sans-serif; }
        body { line-height: 1.6; color: #333; background-color: #f4f4f4; }
        a { text-decoration: none; color: #0077b6; }
        header { background: #023e8a; color: white; padding: 2rem 1rem; text-align: center; }
        header img { width: 150px; height: 150px; border-radius: 50%; border: 4px solid white; object-fit: cover; }
        header h1 { margin-top: 1rem; font-size: 2rem; }
        header h2 { font-size: 1.2rem; font-weight: 400; margin-top: 0.5rem; }

        section { padding: 2rem 1rem; max-width: 1000px; margin: auto; }
        h3 { color: #023e8a; margin-bottom: 1rem; font-size: 1.5rem; border-bottom: 2px solid #0077b6; display: inline-block; padding-bottom: 0.3rem; }

        .skills, .experience, .projects, .education, .certifications, .contact { margin-bottom: 2rem; }
        ul { list-style: disc inside; }
        .skills ul { display: flex; flex-wrap: wrap; }
        .skills li { background: #0077b6; color: white; padding: 0.5rem 1rem; margin: 0.5rem; border-radius: 5px; }

        .project, .experience-item, .education-item, .cert-item { background: white; padding: 1rem; margin-bottom: 1rem; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }

        .contact a { display: inline-block; margin-right: 1rem; }

        footer { text-align: center; padding: 1rem; background: #023e8a; color: white; margin-top: 2rem; }

        @media(max-width: 600px) {
            .skills ul { flex-direction: column; }
        }
    </style>
</head>
<body>

    <!-- Header / Profile Section -->
    <header>
        <img src="https://i.supaimg.com/fa872cd1-8d3b-4d6d-89f6-6281ca846eb0.jpg" alt="Profile Photo">
        <h1>Sai Charan Karra</h1>
        <h2>Data Engineer</h2>
        <p>“I am a dedicated Data Engineer with strong skills in data pipelines, SQL, and cloud technologies. I enjoy building efficient data systems that help businesses use their data effectively.”</p>
    </header>

    <!-- Skills Section -->
    <section class="skills">
        <h3>Skills</h3>
        <ul>
            <li>Python</li>
            <li>MySQL</li>
            <li>Hadoop</li>
            <li>Azure</li>
            <li>Informatica</li>
            <li>Excel</li>
        </ul>
    </section>

    <!-- Experience Section -->
    <section class="experience">
        <h3>Experience</h3>
        <div class="experience-item">
            <h4>Data Engineer | TCS</h4>
            <p><strong>Duration:</strong> Jan 2024 – Present</p>
            <ul>
                <li>Developed and optimized SQL queries for efficient data extraction and reporting.</li>
                <li>Built ETL pipelines using Informatica and Python for seamless data integration.</li>
                <li>Managed large datasets on Hadoop and ensured data quality and consistency.</li>
                <li>Deployed and maintained cloud-based data solutions on Azure.</li>
                <li>Automated data workflows, improving processing speed and accuracy by 30%.</li>
                <li>Collaborated with teams to design and implement scalable data models for business insights.</li>
            </ul>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="projects">
        <h3>Projects</h3>
        <div class="project">
            <h4>Telegram Bot</h4>
            <p>Developed a Telegram bot to automate data retrieval and notifications for team workflows. The bot interacts with users, fetches data from databases, and sends alerts in real-time.</p>
            <p><strong>Role:</strong> Developer / Data Engineer</p>
            <p><strong>Tools:</strong> Python, MySQL, Telegram Bot API, Azure</p>
        </div>
    </section>

    <!-- Education Section -->
    <section class="education">
        <h3>Education</h3>
        <div class="education-item">
            <h4>B.Tech in Computer Science</h4>
            <p><strong>University:</strong> ABC University, India</p>
            <p><strong>Years:</strong> 2020 – 2024</p>
            <p><strong>Relevant Courses:</strong> Database Management Systems (DBMS), Data Warehousing & ETL, Cloud Computing Basics, SQL & Python Projects</p>
        </div>
    </section>

    <!-- Certifications Section -->
    <section class="certifications">
        <h3>Certifications</h3>
        <div class="cert-item">
            <ul>
                <li>Microsoft Certified: Azure Data Fundamentals – Microsoft (2024)</li>
                <li>SQL for Data Science – Coursera (2024)</li>
                <li>Google Cloud Associate Data Engineer – Google Cloud (2024)</li>
            </ul>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact">
        <h3>Contact</h3>
        <p>Email: <a href="mailto:sai126charan@gmail.com">sai126charan@gmail.com</a></p>
        <p>Location: Repalle (MDL), Bapatla (DT), AP</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/sai-karra-897351381?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">Sai Charan Karra</a></p>
    </section>

    <footer>
        &copy; 2025 Sai Charan Karra | Data Engineer
    </footer>

</body>
</html>