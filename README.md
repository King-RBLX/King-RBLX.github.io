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
    overflow: hidden;
  }

  .background {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
    filter: blur(10px); /* Adjust the blur level as needed */
  }

  .content {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background-color: rgba(255, 255, 255, 0.8); /* Adjust the opacity as needed */
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    text-align: center;
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
    color: #333;
    border: 1px solid #333;
    padding: 5px 10px;
    border-radius: 5px;
  }
</style>
</head>
<body>
<div class="container">
  <img class="background" src="IMG_9247.webp" alt="Blurred Background">
  <div class="content">
    <div class="project">
      <h2 class="project-heading">Combat System Project</h2>
      <img class="project-image" src="hqdefault.jpg" alt="Combat System Project">
      <p class="project-description">A dynamic combat system for a Roblox game that provides an engaging player experience.</p>
      <a class="project-link" href="combat-system-project.html">View Project</a>
    </div>
    <div class="project">
      <h2 class="project-heading">Another Project</h2>
      <img class="project-image" src="another-project.jpg" alt="Another Project">
      <p class="project-description">Description of another amazing project you've worked on.</p>
      <a class="project-link" href="another-project.html">View Project</a>
    </div>
    <!-- Add more project sections as needed -->
  </div>
</div>
</body>
</html>
