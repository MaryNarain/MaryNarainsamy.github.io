<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Portfolio</title>
<style>
  /* Add all your CSS styles here */
  .container {
    max-width: 800px;
    margin: 0 auto;
  }

  .app {
    display: flex;
  }

  .sidebar {
    width: 250px;
    background-color: #212529;
    position: absolute;
    top: 60px;
    left: 0;
    height: 150%;
    color: #fff;
    padding: 20px;
  }

  /* Rest of your CSS styles... */
</style>
</head>
<body>
<div class="container">
  <div class="app">
    <div class="sidebar">
      <h1>My Portfolio</h1>
      <p>Hi, My name is Mary and I am a developer :) Welcome to my portfolio!!!</p>
      <img src="./Assets/profile_picture_adjusted.png" alt="Profile Picture">
      <blockquote>
        “My powers are ordinary. Only my application brings me success.” ~ Isaac Newton
      </blockquote>
      <a href="https://www.instagram.com/learnwlala/">
        <img src="./Assets/instagram.png" alt="Instagram">
      </a>
      <a href="https://www.linkedin.com/in/mary-narainsamy-294bb0102/">
        <img src="./Assets/linkedin.png" alt="LinkedIn">
      </a>
      <p>I am a passionate self-taught developer skilled in C#, JavaScript, Power Platform, Dynamics CRM, and React.js. Specializing in developing robust software solutions and creating efficient applications. I am committed to delivering high-quality code and ensuring client satisfaction. I am especially passionate about problem-solving and trying to find ways to solve different problems using code.</p>
      <a href="https://raw.githubusercontent.com/MaryNarain/My_Portfolio/main/path/to/cv.pdf">GET MY CV</a>
    </div>
    <!-- Rest of your content... -->
  </div>
</div>
</body>
</html>
