 Assignment 2.3 — Div, Attributes & Clean Structure
 1. Complete HTML code — index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Introduction Page</title>
</head>
<body>

    <!-- Header Section -->
    <div id="header" class="section header-section"
         data-page-type="personal-profile">
        <h1 id="main-heading" class="heading">
            Your Name
        </h1>
        <p class="tagline">
            Student | Web Development Learner | Future Professional
        </p>
    </div>

    <hr>

    <!-- About Section -->
    <div id="about" class="section about-section">
        <h2 class="heading">About Me</h2>
        <p id="about-text" class="description">
            Hello! My name is Your Name. I am a student who enjoys
            learning new technologies and developing new skills.
            I am hardworking, creative, and always ready to learn.
        </p>
        <p class="description">
            My goal is to become confident in web development and
            create useful and attractive websites.
        </p>
    </div>

    <hr>

    <!-- Education Section -->
    <div id="education" class="section education-section">
        <h2 class="heading">Education</h2>
        <p class="description">
            <strong>School/College:</strong> Your School or College Name
        </p>
        <p class="description">
            <strong>Course:</strong> Your Current Course
        </p>
        <p class="description">
            <strong>Learning:</strong> HTML and basic web development
        </p>
    </div>

    <hr>

    <!-- Skills Section -->
    <div id="skills" class="section skills-section">
        <h2 class="heading">My Skills</h2>
        <p class="description">
            <strong>Technical Skills:</strong> Basic HTML and computer skills
        </p>
        <p class="description">
            <strong>Personal Skills:</strong> Teamwork, creativity,
            communication, and problem-solving
        </p>
        <p class="description">
            <strong>Current Goal:</strong> Improve my coding skills
            through regular practice.
        </p>
    </div>

    <hr>

    <!-- Contact Section -->
    <div id="contact" class="section contact-section">
        <h2 class="heading">Contact Me</h2>
        <p class="description">
            Thank you for visiting my personal webpage!
        </p>
        <p class="description">
            Email: yourname@example.com
        </p>
        <p class="description">
            I look forward to learning, connecting, and working
            on exciting projects.
        </p>
    </div>

    <hr>

    <!-- Footer Section -->
    <div id="footer" class="section footer-section">
        <p class="description">
            &copy; 2026 Your Name. Created for my HTML assignment.
        </p>
    </div>

</body>
</html>
2. Requirements covered
Requirement

Where it is used

Header section

id="header"

About section

id="about"

Education section

id="education"

Skills section

id="skills"

Contact section

id="contact"

div containers

Each section is inside a div

Unique IDs

Each section and main text element has its own ID

Reusable classes

class="section", class="heading", class="description"

Custom attribute

data-page-type="personal-profile"

Updated text and new content

Expanded About Me and added Contact and Footer content

Clean indentation

Code is organized into clearly labeled sections