# Portfolio
Using Html css create a portfolio 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body style="background-image:lightblue">

  <!-- Header -->
  <header>
    <h1 style="text-align:center">Nukanaboina Amarnath</h1>
    <p>Web Developer | Designer | Learner</p>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <img src="C:\Users\abhil\Downloads\WhatsApp Image 2025-08-13 at 8.PM.jpeg" width="120"height="80" alt="Your Photo">
    <p>I’m a passionate web developer skilled in HTML, CSS, JavaScript, and React. I love creating beautiful and functional websites.</p>
  </section>
<!-- Skills Section -->
  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>React</li>
      <li>Python</li>
    </ul>
  </section>
<!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <img src="project1.jpg" alt="Project 1">
      <h3>Project Title 1</h3>
      <p>Short description of the project and what technologies you used.</p>
    </div>
    <div class="project">
      <img src="project2.jpg" alt="Project 2">
      <h3>Project Title 2</h3>
      <p>Another description of your work and achievements.</p>
    </div>
  </section>

  <!-- Resume Section -->
  <section id="resume">
    <h2>Resume</h2>
    <a href="file:///C:/Users/abhil/OneDrive/Desktop/Amar%20(2)-2.pdf" download>Download My Resume (PDF)</a>
  </section>

  <!-- Contact Section -->
  <section id="7815953546">
    <h2>Contact us</h2>
<form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="Amarnath"><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email"><br><br>
            <label for="message">Message:</label>
            <textarea id="message" name="message"></textarea><br><br>
            <input type="submit" value="Send">
        </form>
        <div class="contact-info">
            <h2 style="background-color:black">Contact Information</h2>
            <p>Email: <a href="mailto:amarnathnukanaboina@gamil.com">amarnathnukanaboina1@gamil.com</a></p>
            <p>Phone: 7815953546</p>
            <p>Address: ulavalapalli(v),<br>konduru(p),pendliamrri(m),kadpa(dist)<br></p>
</body>
</html>
