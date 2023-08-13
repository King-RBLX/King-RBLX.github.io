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
    height: 100vh;
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

  .profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 10px;
  }

  .content h1 {
    margin: 0;
    font-size: 24px;
  }

  .content p {
    margin: 10px 0;
    font-size: 16px;
  }

  .example-link {
    display: inline-block;
    margin-top: 15px;
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
    <img class="profile-pic" src="profile-picture.jpg" alt="Profile Picture">
    <h1>Your Name</h1>
    <p>Front-end Developer</p>
    <p>Hello! I'm a front-end developer passionate about creating user-friendly and visually appealing websites.</p>
    <a class="example-link" href="example-project.html">View Example Project</a>
  </div>
</div>
</body>
</html>
