<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Blurred Background Website</title>
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
  }

  .content h1 {
    margin: 0;
    font-size: 24px;
  }

  .content p {
    margin: 10px 0;
    font-size: 16px;
  }
</style>
</head>
<body>
<div class="container">
  <img class="background" src="IMG_9247.webp" alt="Blurred Background">
  <div class="content">
    <h1>Welcome to Our Website</h1>
    <p>This is an example of a website with a blurred background and a centered content layer. You can replace this text with your own content.</p>
  </div>
</div>
</body>
</html>
