# Rahul-ki-dairy
Personal project 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rahul Ki Dairy</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background: #f4f4f9;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #6c63ff;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
    }

    nav {
      background: #5548c8;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .container {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    .section {
      margin-bottom: 40px;
    }

    footer {
      background: #6c63ff;
      color: white;
      text-align: center;
      padding: 15px 0;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Rahul Ki Dairy</h1>
    <p>Your space, your thoughts.</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <section id="about" class="section">
      <h2>About Me</h2>
      <p>Hello! I'm Rahul. This website is a collection of my personal thoughts, ideas, and small projects I enjoy working on. From web design to random experiments, you'll find a bit of everything here.</p>
    </section>

    <section id="projects" class="section">
      <h2>My Projects</h2>
      <ul>
        <li><strong>Diary App:</strong> A digital diary app built in HTML and JavaScript.</li>
        <li><strong>Personal Blog:</strong> Sharing my learnings and interests.</li>
        <li><strong>CSS Tricks:</strong> Mini projects exploring creative CSS designs.</li>
      </ul>
    </section>

    <section id="contact" class="section">
      <h2>Contact Me</h2>
      <p>You can reach me at: <a href="mailto:rahul@example.com">rahul@example.com</a></p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 Rahul Ki Dairy. All rights reserved.</p>
  </footer>
</body>
</html>
