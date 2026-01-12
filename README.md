<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>when you sad look at me you will be happy.</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      margin: 0;
      padding: 0;
      color: #333;
    }

    header {
      background: #a8dadc;
      padding: 20px;
      text-align: center;
      font-size: 1.8em;
      font-weight: bold;
      color: #1d3557;
    }

    nav {
      display: flex;
      justify-content: center;
      background: #f1faee;
      padding: 10px;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #1d3557;
      font-weight: bold;
      position: relative;
      transition: color 0.3s ease;
    }

    nav a::after {
      content: '';
      position: absolute;
      width: 0%;
      height: 2px;
      bottom: -5px;
      left: 0;
      background-color: #457b9d;
      transition: width 0.3s ease;
    }

    nav a:hover {
      color: #457b9d;
    }

    nav a:hover::after {
      width: 100%;
    }

    section {
      padding: 40px;
      text-align: center;
    }

    .notes {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .note-btn {
      background: #f1faee;
      border: 2px solid #457b9d;
      border-radius: 8px;
      padding: 20px;
      font-size: 1.2em;
      cursor: pointer;
      transition: transform 0.3s ease, background-color 0.3s ease;
    }

    .note-btn:hover {
      transform: scale(1.05);
      background-color: #a8dadc;
    }
  </style>
</head>
<body>
  <header>My Study Website</header>

  <nav>
    <a href="#blogs">Blogs</a>
    <a href="#notes">Notes</a>
  </nav>

  <section id="blogs">
    <h2>Blogs</h2>
    <p>Welcome to the blog section! Share your thoughts, updates, and articles here.</p>
  </section>

  <section id="notes">
    <h2>Notes</h2>
    <div class="notes">
      <button class="note-btn">Physics</button>
      <button class="note-btn">Maths</button>
      <button class="note-btn">C Programming</button>
      <button class="note-btn">Electronics & Communications</button>
    </div>
  </section>
</body>
</html>
