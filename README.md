<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My First Webpage</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #ffeef5; /* нежно-розовый фон */
      color: #333;
      margin: 0;
      padding: 20px;
    }

    h1, h2, h3 {
      color: #d63384;
    }

    p, li, td {
      font-size: 16px;
    }

    /* Ссылки */
    a {
      color: #c2185b;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }

    /* Фото */
    img {
      border-radius: 12px;
      border: 2px solid #f8bbd0;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }

    /* Кнопка */
    button, input[type="submit"] {
      background: #f48fb1;
      border: none;
      color: white;
      padding: 10px 20px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
    }
    button:hover, input[type="submit"]:hover {
      background: #ec407a;
    }

    /* Таблица */
    table {
      border-collapse: collapse;
      width: 100%;
      margin-top: 10px;
      background: #fff;
    }
    th, td {
      border: 1px solid #f8bbd0;
      padding: 10px;
      text-align: left;
    }
    th {
      background: #fce4ec;
      color: #880e4f;
    }
    tr:nth-child(even) {
      background: #fff0f5;
    }

    /* Форма */
    input[type="text"], input[type="email"], input[type="color"] {
      padding: 8px;
      margin: 5px 0;
      border: 1px solid #f8bbd0;
      border-radius: 6px;
    }

    form {
      background: #fff;
      padding: 15px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
      width: 300px;
    }
  </style>
</head>
<body>

  <h1>About ME</h1>
  <h2>SE-2416, second year student</h2>
  <h3>Ospanali Akbota</h3>
  <p>HI! I am a student of Astana IT University. I want to learn web development and create websites.</p>

  <h3>My Hobbies</h3>
  <ol>
    <li>Dancing</li>
    <li>Watching Turkish films and podcasts</li>
    <li>Cooking and Blogging</li>
  </ol>

  <h3>My favorite websites</h3>
  <ul>
    <li><a href="https://www.instagram.com" target="_blank">Instagram</a></li>
    <li><a href="https://www.youtube.com" target="_blank">YouTube</a></li>
    <li><a href="https://kinogo.biz" target="_blank">KinoGo</a></li>
    <li><a href="https://www.numerology.com/" target="_blank">Numerology</a></li>
  </ul>

  <h3>My photo</h3>

 <img src="C:\Users\aospa\Downloads\my photo.jpg" alt="My photo" width="200">


  <h3>Button</h3>
  <button>Click Me</button>

  <h3>My schedule</h3>
  <table>
    <tr>
      <th>Subject</th>
      <th>Day</th>
      <th>Time</th>
    </tr>
    <tr>
      <td>Design and analysis of algorithms</td>
      <td>Monday</td>
      <td>16:00-17:50</td>
    </tr>
    <tr>
      <td>Russian language</td>
      <td>Tuesday</td>
      <td>16:00-17:50</td>
    </tr>
    <tr>
      <td>Web frontend</td>
      <td>Wednesday</td>
      <td>13:00-13:50</td>
    </tr>
    <tr>
      <td>Finance</td>
      <td>Thursday</td>
      <td>17:00-18:50</td>
    </tr>
  </table>

  <h3>My mood today</h3>
  <p>Today I feel 😀 💻 👍</p>

  <h3>Form</h3>
  <form>
    Name:<br>
    <input type="text" required><br><br>
    Email:<br>
    <input type="email" required><br><br>
    Favorite color:<br>
    <input type="color"><br><br>
    <input type="submit" value="Send">
  </form>

</body>
</html>
