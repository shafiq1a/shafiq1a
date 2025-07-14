<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My GitHub Profile</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #0d1117;
      color: #c9d1d9;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 20px;
    }

    .profile {
      display: flex;
      align-items: center;
      gap: 20px;
      margin-bottom: 40px;
    }

    .profile img {
      border-radius: 50%;
      width: 120px;
      height: 120px;
      border: 2px solid #30363d;
    }

    .profile-info h1 {
      margin: 0;
      font-size: 28px;
    }

    .profile-info p {
      color: #8b949e;
      margin-top: 5px;
    }

    .social-links a {
      margin-right: 15px;
      color: #58a6ff;
      text-decoration: none;
      font-size: 16px;
    }

    .repos {
      margin-top: 30px;
    }

    .repo-card {
      background-color: #161b22;
      border: 1px solid #30363d;
      padding: 15px;
      border-radius: 8px;
      margin-bottom: 15px;
    }

    .repo-card h3 {
      margin: 0;
      color: #58a6ff;
    }

    .repo-card p {
      color: #8b949e;
      margin: 5px 0 0;
    }

    @media (max-width: 600px) {
      .profile {
        flex-direction: column;
        align-items: flex-start;
      }

      .profile img {
        width: 100px;
        height: 100px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="profile">
      <img src="https://avatars.githubusercontent.com/u/1?v=4" alt="Profile Picture" />
      <div class="profile-info">
        <h1>Shafik Ahmed</h1>
        <p>Front-End Developer | JavaScript Enthusiast</p>
        <div class="social-links">
          <a href="https://github.com/yourusername" target="_blank">GitHub</a>
          <a href="https://linkedin.com/in/yourusername" target="_blank">LinkedIn</a>
        </div>
      </div>
    </div>

    <div class="repos">
      <div class="repo-card">
        <h3>Weather App</h3>
        <p>Simple weather forecast app using OpenWeatherMap API and JavaScript.</p>
      </div>
      <div class="repo-card">
        <h3>Portfolio Website</h3>
        <p>Personal portfolio with animations and responsive design using HTML/CSS/JS.</p>
      </div>
      <div class="repo-card">
        <h3>Todo List</h3>
        <p>A minimal and fast task manager using local storage.</p>
      </div>
    </div>
  </div>
</body>
</html>

