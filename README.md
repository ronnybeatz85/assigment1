<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rajiv Jadon Portfolio</title>
</head>
<body>

  <!-- Name at top -->
  <h1>Rajiv Jadon</h1>

  <!-- Navigation menu -->
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>

  <!-- Hero section -->
  <h2>Welcome to My Portfolio</h2>
  <p>Hello! I am a web development student. This is my personal portfolio website.</p>

  <!-- About section -->
  <h2 id="about">About Me</h2>
  <img src="rajiv.png" alt="Photo of Rajiv Jadon" width="150", style="border-radius:50%">
  <p>I am passionate about learning web development and building creative projects.</p>

  <!-- Projects section -->
  <h2 id="projects">My Projects</h2>
  <ul>
    <li><strong>Portfolio Website:</strong> A personal one-page website to showcase your bio, skills, and contact details.</li>
    <li><strong>Medium Clone:</strong> A simple blog layout that looks like Medium, built only with HTML and CSS.</li>
    <li><strong>Birthday Card:</strong> A creative greeting card webpage designed with HTML structure and CSS styling.</li>
    <li><strong>User Form:</strong> A form webpage with fields like name, email, and message for practicing form handling.</li>
  </ul>

  <!-- Skills section -->
  <h2>Technical Skills</h2>
  <table border="1">
    <tr>
      <th>Skill</th>
      <th>Level</th>
    </tr>
    <tr>
      <td>HTML</td>
      <td>Beginner</td>
    </tr>
    <tr>
      <td>CSS</td>
      <td>Beginner</td>
    </tr>
    <tr>
      <td>JavaScript</td>
      <td>Learning</td>
    </tr>
  </table>

  <!-- Contact section -->
  <h2 id="contact">Contact Me</h2>
  <form>
    <p>
      Name: <input type="text" placeholder="Enter your name" required>
    </p>
    <p>
      Email: <input type="email" placeholder="Enter your email" required>
    </p>
    <p>
      Message:<br>
      <textarea placeholder="Enter your message" required></textarea>
    </p>
    <button type="submit">Send</button>
  </form>

</body>
</html>
