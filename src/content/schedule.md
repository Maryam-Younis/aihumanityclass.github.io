+++
date = "13 Jan 2026"
draft = false
title = "Schedule"
slug = "schedule"
+++

<style>
  table {
  width: 100%;
  border-collapse: collapse;
  font-family: sans-serif;
  }
  /* UPDATED: Changed text-align to center */
  td {
  padding: 5px;
  text-align: center; 
  border-bottom: 1px solid #ddd;
  }

  th {
  text-align: center;
  background-color: #f2f2f2;
  font-weight: bold;
  }
  tr:nth-child(even) {
  background-color: #f9f9f9;
  }
  .center-text {
  text-align: center !important; /* !important ensures it overrides other rules */
  }

  /* --- SNOW DAY ROW STYLES --- */
  .snow-day-row {
  background: linear-gradient(135deg, #e0f7fa 0%, #b3e5fc 100%);
  color: #0277bd;
  position: relative;
  overflow: hidden;
  border-left: 5px solid #0288d1;
  }

  .snow-day-row td {
  /* padding: 20px 15px; */
  font-weight: bold;
  position: relative;
  z-index: 2; /* Keep text above snowflakes */
  }

  /* Date Column Styling */
  .snow-date {
  display: flex;
  align-items: center;
  }

  /* Message Column Styling */
  .snow-message {
  letter-spacing: 1px;
  color: #01579b;
  }

  /* Animated Snowflake Decoration */
  .snowflake {
  position: absolute;
  top: -10px;
  color: rgba(255, 255, 255, 0.8);
  font-size: 1.5em;
  animation: fall linear infinite;
  z-index: 1;
  pointer-events: none;
  }

  /* Snowflake Animation Keyframes */
  @keyframes fall {
  0% { transform: translateY(-20px) rotate(0deg); opacity: 0; }
  20% { opacity: 1; }
  100% { transform: translateY(80px) rotate(360deg); opacity: 0; }
  }

  /* Specific positioning for flakes */
  .flake-1 { left: 10%; animation-duration: 3s; animation-delay: 0s; font-size: 1.2rem; }
  .flake-2 { left: 30%; animation-duration: 4s; animation-delay: 1s; font-size: 1.8rem; }
  .flake-3 { left: 60%; animation-duration: 2.5s; animation-delay: 0.5s; font-size: 1rem; }
  .flake-4 { left: 85%; animation-duration: 3.5s; animation-delay: 2s; font-size: 1.5rem; }

  /* Responsive adjustments */
  @media (max-width: 480px) {
  .snow-day-row td {
  display: block;
  width: 100%;
  text-align: center;
  }
  .snow-date {
  justify-content: center;
  }
  }
</style>

# Upcoming Schedule

[See below for past classes.](#past-schedule)

<table>
  <thead>
  <tr>
  <th class="center-text">Date</th>
  <th class="center-text">News Team</th>
  <th class="center-text">Lead Team</th>
  <th class="center-text">Blog Team</th>
  </tr>
  </thead>
  <tbody>

  
  <tr>
  <td>Thursday 2 Apr</td>
  <td>3</td>
  <td>10</td>
  <td>2</td>
  </tr>
  <tr>
  <td>Tuesday 7 Apr</td>
  <td>4</td>
  <td>11</td>
  <td>7</td>
  </tr>
  <tr>
  <td>Thursday 9 Apr</td>
  <td colspan=2>"Midterm"</td>
  <td>8</td>
  </tr>
  <tr>
  <td>Tuesday 14 Apr</td>
  <td>&ndash;</td>
  <td>12</td>
  <td>4</td>
  </tr>
  <tr>
  <td>Thursday 16 Apr</td>
  <td>&ndash;</td>
  <td>&ndash;</td>
  <td>6</td>
  </tr>
  <tr style="background-color: #effad1ff;">
  <td>Tuesday 21 Apr</td>
  <td colspan=3 class="center-text">Project Draft Presentations</td>
  </tr>
  <tr style="background-color: #faf3d1ff;">
  <td>Thursday 23 Apr</td>
  <td colspan=3 class="center-text">Project Draft Presentations</td>
  </tr>
  <tr style="background-color: #effad1ff;">
  <td>Tuesday 28 Apr</td>
  <td colspan=3 class="center-text">Project Draft Presentations</td>
  </tr>
  </tbody>
</table>

# Past Schedule

<table>
  <thead>
  <tr>
  <th class="center-text">Date</th>
  <th class="center-text">News Topic (Team)</th>
  <th class="center-text">Lead Topic (Team)</th>
  <th class="center-text">Blog</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td>Tuesday 13 Jan</td>
  <td colspan=3><a href="/class1/">Class 1: Introduction</a></td>
  </tr>

  <tr>
  <td>Thursday 15 Jan</td>
  <td colspan=3><a href="/class2/">Class 2: Golden Ages</a></td>
  </tr>

  <tr>
  <td>Tuesday 20 Jan</td>
  <td>Chinese Drills (1)</td>
  <td>Machines of Loving Grace (5)</td>
  <td><a href="/blogs/class3/">Class 3</a> (9)</td>
  </tr>
  <tr>
  <td>Thursday 22 Jan</td>
  <td>Data Centers (2)</td>
  <td>AI2027 / Normal Technology (6)</td>
  <td><a href="/blogs/class4/">Class 4</a> (10)</td>
  </tr>
  <tr class="snow-day-row">
  <td>
  <div class="snowflake flake-1">❄️</div>
  <div class="snowflake flake-2">❅</div>
  <div class="snowflake flake-3">❆</div>
  <div class="snowflake flake-4">❄️</div>
  <span>Tuesday 27 Jan</span>
  </td>
  <td colspan="3" class="snow-message">☃️ Snow Day! ❄️</td>
  </tr>
  <tr>
  <td>Thursday 29 Jan</td>
  <td>AI Genomics (3)</td>
  <td>AlphaFold (7)</td>
  <td><a href="/blogs/class5/">Class 5</a> (11)</td>
  </tr>
  <tr>
  <td>Tuesday 3 Feb</td>
  <td>MoltBook (4)</td>
  <td>AI in Clinical Medicine (8)</td>
  <td>  <a href="/blogs/class6/">Class 6</a> (12)</td>
  </tr>
    <tr>
  <td>Thursday 5 Feb</td>
  <td>Circular AI Investments (5)</td>
  <td>AI Bias and Interpretability (9)</td>
  <td><a href="/blogs/class7/">Class 7</a> (1)</td>
  </tr>
  <tr>
  <td>Tuesday 10 Feb</td>
  <td>Advertising (6)</td>
  <td>Interpretability (10)</td>
  <td><a href="/blogs/class8">Class 8</a> (2)</td>
  </tr>
  <tr>
  <td>Thursday 12 Feb</td>
  <td>Retiring GPT-4o (7)</td>
  <td>Extractability (11)</td>
  <td><a href="/blogs/class9/">Class 9</a> (3)</td>
  </tr>
  <tr>
  <td>Tuesday 17 Feb</td>
  <td>Labor (8)</td>
  <td>Software Development (12)</td>
  <td><a href="/blogs/class10">Class 10</a> (4)</td>
  </tr>

  <tr>
  <td>Thursday 19 Feb (Class 11)</td>
  <td>Love (9)</td>
  <td>Software Development (1)</td>
  <td><a href="/blogs/class11">Class 11</a> (5)</td>
  </tr>

  <tr>
  <td>Tuesday 24 Feb (Class 12)</td>
  <td>Ohio AI Regulation (10)</td>
  <td>Adolescence of Technology I (2)</td>
  <td><a href="/blogs/class12">Class 12</a> (6)</td>
  </tr>

  <tr>
  <td>Thursday 26 Feb (Class 13)</td>
  <td>AI Safety and DoW (Dave)</td>
  <td>Adolescence of Technology II (3)</td>
  <td><a href="/blogs/class13">Class 13</a> (7)</td>
  </tr>

  <tr style="background-color: #d1fae5;">
  <td></td>
  <td colspan=3 class="center-text">Spring Break</td>
  </tr>
  <tr>
  <td>Tuesday 10 Mar</td>
  <td>&ndash;</td>
  <td>Autonomous War (4)</td>
  <td><a href="/blogs/class14">Class 14</a> (8)</td>
  </tr>
  <tr>
  <td>Thursday 12 Mar</td>
  <td>Open AI's Agreement (12)</td>
  <td>Nuclear Weapons, Techno-Optimism (5)</td>
  <td><a href="/blogs/class15">Class 15</a> (9)</td>
  </tr>

  <td>Tuesday 17 Mar</td>
  <td>QuitGPT (1)</td>
  <td>Jobs for Humans (6)</td>
  <td><a href="/blogs/class16/">Class 16</a> (10)</td>
  </tr>
  <tr>
  <td>Thursday 19 Mar</td>
  <td>Quantum Cryptography</td>
  <td>Universal Basic Income (7)</td>
  <td><a href="/blogs/class17">Class 17</a> (3)</td>
  </tr>
  <tr>
  <td>Tuesday 24 Mar</td>
  <td>Looksmaxxing (2)</td>
  <td>Creativity (8)</td>
  <td><a href="/blogs/class18">Class 18</a> (12)</td>
  </tr>
  <tr>
  <td>Thursday 26 Mar</td>
  <td>&ndash;</td>
  <td>9</td>
  <td>1</td>
  </tr>
  <tr>
  <td>Tuesday 31 Mar</td>
  <td>&ndash;</td>
  <td>Project Pitches</td>
  <td>5</td>
  </tr>

 </tbody>
</table>

## Expectations

(Last updated on [9 March](/tablemap-10mar/).)

The expectations for presenting teams (both "News" and "Lead"):

   - **Before 5:00pm** on the **day before** you are scheduled to lead (so Monday for Tuesday classes and Wednesday for Thursday classes), share your plans and draft slides with me. **You should do this in an email with all of the team members who are contributing cc'd so I can reply-all to everyone.** The "before 5pm" deadline assumes that if I am able to get you feedback before 8pm you will have time to make revisions before class. If not, you should get me the slides before noon.

   - **Be creative!** All presenting teams so far have followed fairly closely the same format. This isn't a bad format, but it is definitely not the best for most topics. Teams are encouraged to incroporate more interesting activities and use the class time in more varied ways.

   - **Better presentations.** I will provide some more guidance on general ways to improve presentations in Tuesday's class (and maybe more in later classes), and although you are not required to follow everything I say it is expected that you'll design presentations in ways that are mindful of it. 