<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Everything Tech!</title>
  <link rel="stylesheet" href="stylesheet1.css">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    .sidebar {
      width: 250px;
      position: fixed;
      height: 100%;
      background: #222;
      padding-top: 20px;
      transition: 0.3s;
    }
    .sidebar a {
      padding: 10px 20px;
      text-decoration: none;
      color: white;
      display: block;
      transition: 0.3s;
    }
    .sidebar a:hover {
      background: #575757;
    }
    .content {
      margin-left: 250px;
      padding: 20px;
    }
    .menu-icon {
      display: none;
      font-size: 24px;
      margin: 15px;
      cursor: pointer;
    }
    @media screen and (max-width: 768px) {
      .sidebar {
        width: 0;
        overflow: hidden;
      }
      .menu-icon {
        display: block;
      }
      .content {
        margin-left: 0;
      }
    }
  </style>
</head>
<body>
  <div class="menu-icon" onclick="toggleSidebar()">
    <i class="fas fa-bars"></i>
  </div>
  <nav class="sidebar" id="sidebar">
    <a href="how2.html"><i class="fas fa-home"></i> Home</a>
    <a href="https://linktr.ee/funnygifdan"><i class="fas fa-link"></i> My Linktree</a>
    <a href="cyberaware.html"><i class="fas fa-shield-alt"></i> Cyber Awareness</a>
    <a href="important.html"><i class="fas fa-exclamation-circle"></i> Important Links</a>
  </nav>
  <div class="content">
    <h2>Everything Tech!!</h2>
    <ul>
      <li><a href="https://www.usnews.com/news/world/articles/2023-06-15/us-government-agencies-hit-in-global-cyber-attack-cnn">US Government Cyber Attack</a></li>
      <li><a href="https://www.montclairnjusa.org/news/headlines/cyber_incident_hits_township_computer_systems">Montclair Township Cyber Incident</a></li>
    </ul>
  </div>
  <script>
    function toggleSidebar() {
      var sidebar = document.getElementById("sidebar");
      sidebar.style.width = sidebar.style.width === "250px" ? "0" : "250px";
    }
  </script>
</body>
</html>
