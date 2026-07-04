# Seo-audit-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Sakshi Kochar | Portfolio</title>

    <meta name="description" content="Personal portfolio of Sakshi Kochar showcasing skills, projects, and contact information.">

    <meta name="keywords" content="Portfolio, HTML5, CSS, Student, Web Developer">

    <meta name="author" content="Sakshi Kochar">
</head>

<body>

<header role="banner">
    <h1>Sakshi Kochar</h1>

    <nav aria-label="Main Navigation">
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="projects.html">Projects</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
</header>

<main id="main-content">

    <section aria-labelledby="about-heading">
        <h2 id="about-heading">About Me</h2>
        <p>Computer Science student passionate about web development and technology.</p>
    </section>

    <section aria-labelledby="skills-heading">
        <h2 id="skills-heading">Skills</h2>
        <ul>
            <li>HTML5</li>
            <li>CSS3</li>
            <li>JavaScript</li>
            <li>Responsive Web Design</li>
        </ul>
    </section>

    <section aria-labelledby="projects-heading">
        <h2 id="projects-heading">Projects</h2>

        <article>
            <h3>Portfolio Website</h3>
            <p>A responsive portfolio website built using semantic HTML5 and CSS.</p>
        </article>

        <article>
            <h3>Student Management System</h3>
            <p>A basic web application for managing student records.</p>
        </article>
    </section>

    <section aria-labelledby="contact-heading">
        <h2 id="contact-heading">Contact Me</h2>

        <form aria-label="Contact Form">

            <label for="name">Full Name</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email Address</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Send Message</button>

        </form>
    </section>

</main>

<footer role="contentinfo">
    <p>&copy; 2026 Sakshi Kochar. All Rights Reserved.</p>
</footer>

</body>
</html>
