<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Claire Harnum | Engineering Portfolio</title>

    <style>
        /* ------------------------
           GENERAL PAGE STYLING
        ------------------------- */

        body {
            margin: 0;
            font-family: Calibri, Candara, "Segoe UI", sans-serif;
            background-color: #f4f7fa;
            color: #052642;
            line-height: 1.6;
        }

        main {
            max-width: 1000px;
            margin: auto;
            padding: 40px;
        }

        h1, h2, h3 {
            margin-top: 0;
        }

        a {
            color: #ffffff;
            text-decoration: none;
        }

        /* ------------------------
           HEADER
        ------------------------- */

        header {
            background: #052642;
            color: white;
            text-align: center;
            padding: 70px 20px;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }

        .buttons a {
            display: inline-block;
            margin: 8px;
            padding: 12px 24px;
            background: #0b71c7;
            border-radius: 8px;
            transition: 0.3s;
        }

        .buttons a:hover {
            background: #09589b;
        }

        /* ------------------------
           SECTIONS
        ------------------------- */

        section {
            margin: 60px 0;
        }

        section h2 {
            border-bottom: 3px solid #0b71c7;
            padding-bottom: 8px;
            margin-bottom: 30px;
        }

        /* ------------------------
           PROJECT CARDS
        ------------------------- */

        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px,1fr));
            gap: 30px;
        }

        .project-card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 12px rgba(0,0,0,.12);
        }

        .project-card img {
            width: 100%;
            display: block;
        }

        .project-content {
            padding: 20px;
        }

        .project-content h3 {
            margin-bottom: 10px;
        }

        .project-button {
            display: inline-block;
            margin-top: 15px;
            background: #0b71c7;
            color: white;
            padding: 10px 18px;
            border-radius: 6px;
        }

        .project-button:hover {
            background: #09589b;
        }

        /* ------------------------
           ABOUT SECTION
        ------------------------- */

        .about {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,.1);
        }

        /* ------------------------
           CONTACT
        ------------------------- */

        .contact p {
            font-size: 18px;
        }

        footer {
            background: #052642;
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 80px;
        }

    </style>
</head>

<body>

<!-- ===================== HEADER ===================== -->

<header>

    <h1>Claire Harnum</h1>

    <p class="subtitle">
        Engineering Student • Memorial University of Newfoundland
    </p>

    <div class="buttons">

        <!-- Replace # with your actual links -->

        <a href="#">GitHub</a>

        <a href="#">LinkedIn</a>

        <a href="resume.pdf">Resume</a>

    </div>

</header>

<!-- ===================== MAIN PAGE ===================== -->

<main>

<!-- ===================== ABOUT ===================== -->

<section>

<h2>About Me</h2>

<div class="about">

<p>

Welcome to my engineering portfolio!

This website showcases the projects I've designed, built, and tested throughout university. Each project highlights my engineering design process—from brainstorming and CAD modeling to manufacturing, programming, testing, and the final product.

Feel free to explore the projects below to see photos, videos, and the steps behind each design.

</p>

</div>

</section>

<!-- ===================== PROJECTS ===================== -->

<section>

<h2>Featured Projects</h2>

<div class="project-grid">

    <!-- ROV -->

    <div class="project-card">

        <img src="images/rov/hero.jpg" alt="ROV Thruster Mount">

        <div class="project-content">

            <h3>ROV Thruster Mount</h3>

            <p>

            Designed and manufactured a custom thruster mount for the
            Memorial University Eastern Edge Robotics ROV. This project
            includes CAD models, design iterations, machining, 3D printing,
            assembly, and competition photos.

            </p>

            <a class="project-button" href="projects/rov.html">
                View Project →
            </a>

        </div>

    </div>

    <!-- PNEUMATIC PISTON -->

    <div class="project-card">

        <img src="images/piston/piston.jpg" alt="Pneumatic Piston">

        <div class="project-content">

            <h3>Pneumatic Piston</h3>

            <p>

            Manufactured a functioning pneumatic piston using mills,
            lathes, precision measuring tools, and engineering drawings.

            Includes photos and a demonstration video.

            </p>

            <a class="project-button" href="projects/piston.html">
                View Project →
            </a>

        </div>

    </div>

    <!-- VIDEO GAME -->

    <div class="project-card">

        <img src="images/game/game.jpg" alt="Python Video Game">

        <div class="project-content">

            <h3>Python Video Game</h3>

            <p>

            Designed and programmed a multi-level snake-style game using
            Python and Arduino. Includes gameplay screenshots and video.

            </p>

            <a class="project-button" href="projects/game.html">
                View Project →
            </a>

        </div>

    </div>

    <!-- ZAMBONI -->

    <div class="project-card">

        <img src="images/zamboni/zamboni.jpg" alt="Miniature Zamboni">

        <div class="project-content">

            <h3>Miniature Zamboni</h3>

            <p>

            Developed a low-cost backyard ice resurfacer, from sketches
            and CAD modeling to the finished prototype.

            </p>

            <a class="project-button" href="projects/zamboni.html">
                View Project →
            </a>

        </div>

    </div>

</div>

</section>

<!-- ===================== CONTACT ===================== -->

<section class="contact">

<h2>Contact</h2>

<p>📧 your_email@email.com</p>

<p>💼 LinkedIn</p>

<p>💻 GitHub</p>

</section>

</main>

<!-- ===================== FOOTER ===================== -->

<footer>

© 2026 Claire Harnum

</footer>

</body>

</html>
