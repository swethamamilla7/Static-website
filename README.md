# Static-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My First Static Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #444;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 10px;
    }

    main {
      padding: 20px;
    }

    button {
      background-color: #4CAF50;
      color: white;
      padding: 10px 15px;
      border: none;
      cursor: pointer;
      font-size: 16px;
      margin-top: 20px;
    }

    #message {
      margin-top: 20px;
      font-size: 18px;
      color: #333;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Website</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <main>
    <h2>About Me</h2>
    <p>Hello! I'm learning how to build websites. This is my first static webpage made with only HTML, CSS, and JavaScript.</p>

    <!-- Button to trigger JavaScript -->
    <button onclick="showMessage()">Click Me</button>
    <div id="message"></div>
  </main>

  <footer>
    &copy; 2025 My Website
  </footer>

  <!-- JavaScript Section -->
  <script>
    function showMessage() {
      const messageDiv = document.getElementById("message");
      messageDiv.textContent = "🎉 Thanks for clicking! You just triggered JavaScript.";
    }
  </script>

</body>
</html>
