# MDAP-EX_01-Portfolio

```
NAME: V. POOJAA SREE
REG. NO: 212223040147

```

## Date:

## AIM:
To create a Portfolio using HTML and CSS.

## ALGORITHM:
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

## PROGRAM:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Poojaa Sree - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body onload="welcomeMessage()">
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <section id="self">
            <img src="images/Poojaa.jpg" alt="Poojaa Sree" height="200px" width="200px">
            <h2 id="name">V. Poojaa Sree</h2>
            <p>2nd Year CSE Student | Aspiring Full Stack Developer</p>
            <button onclick="changeBackground()">Change Background</button>
        </section>
        <h1>Welcome to My Portfolio</h1>
    </section>
    
    <section id="about">
        <h2>About Me</h2>
        <p>I am a 2nd-year Computer Science student with a passion for Full Stack Development. I am currently learning HTML, CSS, JavaScript, React, and Node.js to build interactive web applications. I enjoy solving problems, learning new technologies, and working on projects to strengthen my development skills.</p>
    </section>

    <section id="education">
        <h2>Education</h2>
        <p><strong>Bachelor of Computer Science Engineering</strong> - SAVEETHA ENGINEERING COLLEGE (2023 - Present)</p>
        <p>Studying core programming concepts, data structures, web development, Python, and C.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <p><strong>1. Personal Portfolio Website</strong> - A responsive portfolio showcasing my skills and projects.</p>
        <p><strong>2. Doctor Application</strong> - Enables patients to book appointments and doctors to manage schedules online.</p>
    </section>

    <section id="certifications">
        <h2>Certifications</h2>
        <ul>
            <li>Micro-Certification - ServiceNow</li>
            <img src="images/sn.jpg" height="200px" width="200px">
            <li>Full Stack Development - Inplant Training</li>
            <img src="images/it.jpg" height="200px" width="200px">
        </ul>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="#">poojaasree@example.com</a></p>
        <p>LinkedIn: <a href="#">linkedin.com/in/poojaasree</a></p>
        <p>GitHub: <a href="#">github.com/poojaasree</a></p>
    </section>

    <script>
        function welcomeMessage() {
            alert("Welcome to Poojaa Sree's Portfolio!");
        }

        function changeBackground() {
            document.body.style.backgroundColor = 
                document.body.style.backgroundColor === 'lightblue' ? '#f4f4f4' : 'lightblue';
        }

        document.getElementById('name').addEventListener('click', function() {
            console.log("You clicked on Poojaa Sree's name!");
        });
    </script>
</body>
</html>

```

## OUTPUT:

![1](https://github.com/user-attachments/assets/98e456f7-b4c7-4e43-a1c1-36daeb62ea86)
---
![1a](https://github.com/user-attachments/assets/613a3438-8a15-40be-945b-a00a07432c90)
---
![2](https://github.com/user-attachments/assets/bc7f2707-1662-46f0-987b-8f5a37cfdcce)
---
![3](https://github.com/user-attachments/assets/6618375c-91ff-4fd7-aa63-a04e997b5f0e)
---
![4](https://github.com/user-attachments/assets/ebe3a08f-4e64-4fda-b80e-0986be589f5c)


## RESULT:
The program for creating Portfolio using HTML and CSS is executed successfully.
