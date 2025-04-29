<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About Me</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0f1115;
      color: #e0e0e0;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }

    .container {
      background-color: #1a1a1a;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(0, 255, 255, 0.15);
      display: flex;
      align-items: center;
      max-width: 900px;
      gap: 30px;
    }

    .text-section {
      flex: 2;
    }

    .video-section {
      flex: 1;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 20px;
      color: #00ffc8;
      text-shadow: 0 0 5px #00ffc8;
    }

    p {
      font-size: 1.2em;
      line-height: 1.5;
    }

    video {
      max-width: 200px;
      border-radius: 12px;
      box-shadow: 0 0 10px #00ffc8;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="text-section">
      <h1>Hello fellow developers!</h1>
      <p>
        I'm a passionate learner, coder, and creative thinker. I enjoy solving problems, building projects, and exploring new technologies. Always curious, always growing—ready to take on new challenges every day.
      </p>
    </div>
    <div class="video-section">
      <video autoplay loop muted playsinline>
        <source src="hand_salute.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
  </div>
</body>
</html>
