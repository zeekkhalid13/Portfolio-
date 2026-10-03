<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Zeek | Student Timetable</title>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', sans-serif; }

  body {
    background: linear-gradient(135deg, #0a1930 0%, #123a6b 100%);
    min-height: 100vh;
    color: #eaf3ff;
    padding: 40px 20px;
  }

  header { text-align: center; margin-bottom: 40px; }

  header h1 {
    font-size: 3rem;
    letter-spacing: 6px;
    color: #4fc3f7;
    text-shadow: 0 0 15px rgba(79,195,247,0.6);
  }

  header p { color: #9fc5e8; margin-top: 8px; font-size: 1.1rem; }

  .container {
    max-width: 1000px;
    margin: auto;
    background: rgba(255,255,255,0.05);
    border: 1px solid rgba(79,195,247,0.3);
    border-radius: 16px;
    padding: 25px;
    backdrop-filter: blur(8px);
    box-shadow: 0 8px 32px rgba(0,0,0,0.4);
    overflow-x: auto;
  }

  table { width: 100%; border-collapse: collapse; min-width: 700px; }

  th, td {
    padding: 16px;
    text-align: center;
    border-bottom: 1px solid rgba(79,195,247,0.2);
  }

  th {
    background: #1e5aa8;
    color: #fff;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-size: 0.9rem;
  }

  tr:hover td { background: rgba(79,195,247,0.1); transition: 0.3s; }

  .time { color: #4fc3f7; font-weight: bold; }

  .tag {
    display: inline-block;
    padding: 6px 14px;
    border-radius: 20px;
    font-size: 0.85rem;
    font-weight: bold;
  }

  .programming { background: #1565c0; color: #fff; }
  .maths       { background: #42a5f5; color: #062b4f; }
  .pakstudies  { background: #0d47a1; color: #bbdefb; }
  .break       { background: rgba(255,255,255,0.1); color: #9fc5e8; }

  footer {
    text-align: center;
    margin-top: 30px;
    color: #6fa8d6;
    font-size: 0.9rem;
  }
</style>
</head>
<body>

<header>
  <h1>⚡ ZEEK</h1>
  <p>Your Smart Student Timetable</p>
</header>

<div class="container">
  <table>
    <tr>
      <th>Time</th>
      <th>Monday</th>
      <th>Tuesday</th>
      <th>Wednesday</th>
      <th>Thursday</th>
      <th>Friday</th>
    </tr>
    <tr>
      <td class="time">8:00 – 9:00</td>
      <td><span class="tag programming">Programming</span></td>
      <td><span class="tag maths">Maths</span></td>
      <td><span class="tag programming">Programming</span></td>
      <td><span class="tag pakstudies">Pakistan Studies</span></td>
      <td><span class="tag maths">Maths</span></td>
    </tr>
    <tr>
      <td class="time">9:00 – 10:00</td>
      <td><span class="tag maths">Maths</span></td>
      <td><span class="tag programming">Programming</span></td>
      <td><span class="tag maths">Maths</span></td>
      <td><span class="tag programming">Programming</span></td>
      <td><span class="tag pakstudies">Pakistan Studies</span></td>
    </tr>
    <tr>
      <td class="time">10:00 – 10:30</td>
      <td colspan="5"><span class="tag break">☕ Break</span></td>
    </tr>
    <tr>
      <td class="time">10:30 – 11:30</td>
      <td><span class="tag pakstudies">Pakistan Studies</span></td>
      <td><span class="tag pakstudies">Pakistan Studies</span></td>
      <td><span class="tag programming">Programming</span></td>
      <td><span class="tag maths">Maths</span></td>
      <td><span class="tag programming">Programming</span></td>
    </tr>
  </table>
</div>

<footer>Zeek © 2025 — Made by a student, for students 💙</footer>

</body>
</html>
