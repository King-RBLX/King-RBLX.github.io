<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Portfolio</title>
<style>
  body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
  }

  .container {
    position: relative;
    width: 100%;
    min-height: 100vh;
    overflow: auto; /* Allow scrolling if content exceeds viewport height */
    background-image: url("background-image.jpg"); /* Set background image */
    background-size: cover;
  }

  .content {
    background-color: rgba(255, 255, 255, 0.8); /* Adjust the opacity as needed */
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    text-align: center;
    margin: 20px auto;
    max-width: 600px; /* Limit content width for readability */
  }

  .project {
    margin-bottom: 30px;
  }

  .project-heading {
    font-size: 24px;
    margin-bottom: 10px;
  }

  .project-image {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
  }

  .project-description {
    font-size: 16px;
    margin: 10px 0;
  }

  .project-link {
    display: inline-block;
    font-size: 18px;
    text-decoration: none;
    color: #fff;
    background-color: #3498db; /* Blue color */
    padding: 10px 20px;
    border-radius: 5px;
    transition: background-color 0.3s ease, color 0.3s ease;
  }

  .project-link:hover {
    background-color: #2980b9; /* Darker blue on hover */
    color: #fff;
  }
</style>
</head>
<body>
<div class="container">
  <div class="content">
    <div class="project">
      <h2 class="project-heading">Combat System Project</h2>
      <img class="project-image" src="combat-system.jpg" alt="Combat System Project">
      <p class="project-description">A dynamic combat system for a Roblox game that provides an engaging player experience.</p>
      <a class="project-link" href="https://www.roblox.com/games/14423227189/Combat-System" target="_blank">View Project</a>
    </div>
    <div class="project">
      <h2 class="project-heading">AI Script (PathFinding Service)</h2>
      <img class="project-image" src="RobloxScreenShot20230813_210857632.png" alt="Another Project">
      <p class="project-description">Upgrade your Roblox games with seamless Pathfinding Service. Watch your in-game characters navigate their world intelligently and effortlessly.</p>
      <a class="project-link" href="https://www.roblox.com/games/14429857043/AI-NPCs-Pathfinding-Service" target="_blank">View Project</a>
    </div>
    <!-- Add more project sections as needed -->
  </div>
</div>
</body>
</html>
