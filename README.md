# Eduex
Promotional Site
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Student Resource Hub</title>
  <style>
    
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f7fa;
      color: #333;
      line-height: 1.6;
    }

   
    header {
      background-color: #1a73e8;
      padding: 15px 30px;
      color: white;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }

    header img {
      height: 110px;
    }

    nav ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    nav li {
      display: flex;
      align-items: center;
      gap: 6px;
      cursor: pointer;
      padding: 6px 8px;
      color: white;
      transition: background 0.3s ease;
      border-radius: 4px;
    }

    nav li:hover {
      background-color: rgba(255, 255, 255, 0.1);
    }

    nav svg {
      fill: white;
      height: 14px;
      width: 14px;
    }

  
    .container {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .box {
      background-color: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .box:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    .box h3 {
      margin-bottom: 10px;
      font-size: 1.1em;
      color: #1a73e8;
    }

    .box a {
      display: block;
      margin: 5px 0;
      color: #333;
      text-decoration: none;
    }

    .box a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 30px;
      font-size: 0.9em;
      color: #777;
    }

    @media (max-width: 768px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }

      nav ul {
        gap: 12px;
        flex-wrap: wrap;
        margin-top: 10px;
      }
    }
  </style>
</head>

<body>

  <header>
    <a href="index.html"><img src="2-removebg-preview.png" alt="Logo" /></a>
    <nav>
      <ul>
        <li><span>Products</span>
          <svg viewBox="0 0 20 20"><path d="M5 7l5 5 5-5H5z" /></svg>
        </li>
        <li><span>Pricing</span>
          <svg viewBox="0 0 20 20"><path d="M5 7l5 5 5-5H5z" /></svg>
        </li>
        <li><span>Notes</span>
          <svg viewBox="0 0 20 20"><path d="M5 7l5 5 5-5H5z" /></svg>
        </li>
        <li><span>Services</span>
          <svg viewBox="0 0 20 20"><path d="M5 7l5 5 5-5H5z" /></svg>
        </li>
        <li><span>More</span>
          <svg viewBox="0 0 20 20"><path d="M5 7l5 5 5-5H5z" /></svg>
        </li>
      </ul>
    </nav>
  </header>

  <main class="container">
    <div class="grid">
      <div class="box">
        <h3>PYQ's</h3>
        <a href="#">Download</a>
      </div>
      <div class="box">
        <h3>First Year Notes</h3>
        <a href="https://drive.google.com/drive/folders/151FgtlcDbG0pxIvg5vGy2uwWg__TWU8Z?usp=drive_link">Chemistry</a>
        <a href="https://drive.google.com/drive/folders/1dXDi0M0FEJF8lLL14SoxLlIb-BSnogdl?usp=drive_link">Physics</a>
      </div>
      <div class="box">
        <h3>Third Sem</h3>
        <a href="https://drive.google.com/drive/folders/1y9VNeE5TWgY6aRWU7ThlNMe2vX1Hsava?usp=drive_link">Download</a>
      </div>
      <div class="box">
        <h3>Fourth Sem</h3>
        <a href="https://drive.google.com/drive/folders/10D-zCBffCeEBDjXCt1R8Nk_do5II55lA?usp=drive_link">Download</a>
      </div>
      <div class="box">
        <h3>Fourth Sem</h3>
        <p>Coming Soon</p>
      </div>
      <div class="box">
        <h3>Fifth Sem</h3>
        <p>Coming Soon</p>
      </div>
      <div class="box">
        <h3>Sixth Sem</h3>
        <p>Coming Soon</p>
      </div>
      <div class="box">
        <h3>Seventh Sem</h3>
        <p>Coming Soon</p>
      </div>
      <div class="box">
        <h3>Eighth Sem</h3>
        <p>Coming Soon</p>
      </div>
      <div class="box">
        <h3>Placement Details</h3>
        <p>Coming Soon</p>
      </div>
    </div>
  </main>

  <footer>
    <p>&copy; 2025 Student Resource Hub. All rights reserved.</p>
  </footer>

</body>

</html>
