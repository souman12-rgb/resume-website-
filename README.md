# resume-website-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Souman Das - Resume</title>
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans&family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background-color: #f4f6f8;
      color: #333;
    }

    header {
      background-color: #2C3E50;
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 1.5rem;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      padding: 5px 10px;
      transition: background 0.3s;
    }

    nav a:hover {
      background-color: #1a252f;
      border-radius: 5px;
    }

    .container {
      max-width: 900px;
      margin: 100px auto 40px auto;
      padding: 20px;
    }

    .section {
      background-color: white;
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    .section h2 {
      font-family: 'Roboto', sans-serif;
      color: #2C3E50;
      border-bottom: 2px solid #eee;
      padding-bottom: 10px;
    }

    ul {
      list-style-type: disc;
      padding-left: 20px;
    }

    @media screen and (max-width: 768px) {
      nav {
        flex-direction: column;
      }

      .container {
        margin-top: 140px;
        padding: 10px;
      }
    }
  </style>
</head>
<body>
  <header>
    Souman Das
    <nav>
      <a href="#profile">Profile</a>
      <a href="#education">Education</a>
      <a href="#experience">Experience</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="container">
    <div class="section" id="profile">
      <h2>Profile</h2>
      <p>Motivated and passionate student pursuing a BBA in Digital Business and Entrepreneurship at IIMB. Enthusiastic about business innovation, technology, and design.</p>
    </div>

    <div class="section" id="education">
      <h2>Education</h2>
      <ul>
        <li>BBA in Digital Business and Entrepreneurship, IIMB (2024 - 2027)</li>
        <li>High School: Sribhumi High School, Assam (2022)</li>
      </ul>
    </div>

    <div class="section" id="experience">
      <h2>Experience</h2>
      <ul>
        <li>Created a zero-budget handcrafted venture featuring designer stationery and décor.</li>
        <li>Designed and built a personal resume website using HTML, CSS, and responsive design principles.</li>
      </ul>
    </div>

    <div class="section" id="contact">
      <h2>Contact</h2>
      <ul>
        <li>Email: soumand24@iimb.ac.in</li>
        <li>Phone: 1234567890</li>
        <li>LinkedIn: linkedin.com/in/yourname</li>
      </ul>
    </div>
  </div>
</body>
</html>
