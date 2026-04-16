m                                                                                                                                                                                                                                                                                                                                                                                                                                                  <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Mashaba Kamogelo</title>
<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f4f4f4;
  }

  header {
    background: #222;
    color: white;
    text-align: center;
    padding: 30px 10px;
  }

  nav {
    background: #444;
    text-align: center;
  }

  nav a {
    color: white;
    padding: 15px;
    display: inline-block;
    text-decoration: none;
  }

  nav a:hover {
    background: #666;
  }

  .container {
    padding: 20px;
  }

  .card {
    background: white;
    padding: 20px;
    margin: 15px 0;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  }

footer {
  background: #222;
  color: white;
  text-align: center;
  padding: 15px;
}

html {
  scroll-behavior: smooth;
}
.profile-pic {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid #444;
}
</style>

</head>
<body>

<header>
  <h1>Mashaba Kamogelo</h1>
  <p>Welcome to my personal website</p>
</header>
<!-- NAVIGATION MENU -->
<nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#projects">Projects</a>
  <a href="#contact">Contact</a>
</nav>
<!-- MAIN CONTENT -->
<div class="container">

  <div class="card" id="home">
    <h2>Home</h2>
    <p>Welcome to my website.</p>
  </div>
  
<div class="card" id="about">
  <h2 style="text-align: center;">About Me</h2>
  
  <div style="text-align: center; margin: 20px 0;">
    <img src="profile.jpg" alt="Profile Picture" class="profile-pic">
  </div>
  
 <p style="text-align: center;">
    I am <strong>Kamogelo Mashaba</strong>, an IT Level 4 graduate with a strong interest in 
    technology and web development. I enjoy building websites and continuously improving my skills 
    in the IT field. I am dedicated, motivated, and eager to take on new challenges that help me grow 
    professionally.
  </p>
</div>

<div class="card" id="projects">
    <h2>Projects</h2>
    <h3>My personal Website</h3>
    <p>its based on the website i build using CSS and HTML to showcase my profile</p>
    <h4>mechanical web app development</h4>
    <p>This development is based on promoting services to customers through local machanics which are good at their duties and they will be able to provide best services to the requesters </p>                                </div>

<div class="card" id="contact">
  <h2>Contact</h2>
  <p>📞 Phone: <a href="tel:0637308308">063 730 8308</a></p>
  <p>📧 Email: <a href="mailto:loyaltymash10@gmail.com">loyaltymash10@gmail.com</a></p>
</div>

</div>

<!-- FOOTER -->
<footer>
  <p>© 2026 Mashaba Kamogelo</p>
</footer>

</body>
</html>
