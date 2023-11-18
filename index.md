<!DOCTYPE html>
<html>
<head>
  <title>Darkspeed Gaming</title>
  <style>
    body {
      background-color: black;
      color: white;
    }
    h1 {
      color: darkblue;
    }
    .calendar {
      border-collapse: collapse;
      margin: 20px auto;
    }
    .calendar th, .calendar td {
      border: 1px solid white;
      padding: 10px;
      text-align: center;
    }
    .calendar .today {
      background-color: orange;
    }
    .calendar .prev-month, .calendar .next-month {
      color: gray;
    }
    .calendar .current-month {
      color: white;
    }
    .calendar .current-day {
      background-color: orange;
    }
  </style>
</head>
<body>
  <h1>Darkspeed Gaming</h1>
  <table class="calendar">
    <thead>
      <tr>
        <th colspan="7">November 2023</th>
      </tr>
      <tr>
        <th>Sun</th>
        <th>Mon</th>
        <th>Tue</th>
        <th>Wed</th>
        <th>Thu</th>
        <th>Fri</th>
        <th>Sat</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="prev-month">31</td>
        <td class="prev-month">1</td>
        <td class="prev-month">2</td>
        <td class="prev-month">3</td>
        <td class="prev-month">4</td>
        <td class="prev-month">5</td>
        <td class="prev-month">6</td>
      </tr>
      <tr>
        <td>7</td>
        <td>8</td>
        <td>9</td>
        <td class="current-day">10</td>
        <td>11</td>
        <td>12</td>
        <td>13</td>
      </tr>
      <tr>
        <td>14</td>
        <td>15</td>
        <td>16</td>
        <td>17</td>
        <td>18</td>
        <td>19</td>
        <td>20</td>
      </tr>
      <tr>
        <td>21</td>
        <td>22</td>
        <td>23</td>
        <td>24</td>
        <td>25</td>
        <td>26</td>
        <td>27</td>
      </tr>
      <tr>
        <td>28</td>
        <td>29</td>
        <td>30</td>
        <td class="next-month">1</td>
        <td class="next-month">2</td>
        <td class="next-month">3</td>
        <td class="next-month">4</td>
      </tr>
    </tbody>
  </table>
</body>
</html>
