<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Tharidu L. Rupasingha | Full-Stack Developer</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      background: #f7f9fc;
      color: #2c3e50;
      padding: 0 20px;
    }
    header {
      background: linear-gradient(to right, #4e54c8, #8f94fb);
      color: white;
      padding: 60px 20px 40px;
      text-align: center;
      border-radius: 0 0 30px 30px;
    }
    h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    .emoji {
      font-size: 1.5rem;
    }
    .section {
      margin: 40px 0;
    }
    .badges {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }
    .project-list li {
      margin-bottom: 8px;
    }
    .connect a {
      margin-right: 10px;
      display: inline-block;
      margin-bottom: 10px;
    }
    blockquote {
      font-style: italic;
      color: #555;
      border-left: 4px solid #ccc;
      padding-left: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header data-aos="fade-down">
    <h1>Hi 👋, I'm Tharidu L. Rupasingha</h1>
    <p class="emoji">🇱🇰 Full-Stack Developer from Sri Lanka</p>
    <p>Building apps that solve real-world problems</p>
  </header>

  <section class="section" data-aos="fade-up">
    <h2>💻 Tech Stack</h2>
    <div class="badges">
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
      <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
      <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android">
      <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
      <img src="https://img.shields.io/badge/Firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase">
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
      <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo">
      <img src="https://img.shields.io/badge/ESP32-999999?style=for-the-badge" alt="ESP32">
    </div>
  </section>

  <section class="section" data-aos="fade-right">
    <h2>📱 Recent Projects</h2>
    <ul class="project-list">
      <li><strong>HandyHub:</strong> Android + Firebase app to connect service providers with customers.</li>
      <li><strong>Smart Plant Watering:</strong> ESP32 + Android + Soil Moisture Sensor + Pump.</li>
      <li><strong>Smart Home IoT:</strong> Power monitoring & appliance control with ESP32.</li>
      <li><strong>Note App:</strong> Offline note-taking app in Java.</li>
    </ul>
  </section>

  <section class="section" data-aos="fade-left">
    <h2>📫 Connect With Me</h2>
    <div class="connect">
      <a href="https://www.linkedin.com/in/tharidul/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
      <a href="https://www.youtube.com/@tharindulakmal5593"><img src="https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white" alt="YouTube"></a>
      <a href="https://www.hackerrank.com/profile/tharindulakmal51"><img src="https://img.shields.io/badge/HackerRank-2EC866?style=flat&logo=HackerRank&logoColor=white" alt="HackerRank"></a>
    </div>
  </section>

  <section class="section" data-aos="zoom-in">
    <blockquote>
      "I hear and I forget. I see and I remember. I do and I understand." — Confucius
    </blockquote>
  </section>

  <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
  <script>
    AOS.init({
      duration: 1000,
      once: true
    });
  </script>

</body>
</html>
