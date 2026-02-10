<!DOCTYPE html>
<html>
<head>
<title>Seminar Schedule</title>
<style>
  table {
    border-collapse: collapse;
    width: 90%;
    margin: 30px auto;
    font-family: Arial, sans-serif;
  }

  th, td {
    border: 2px solid #555;
    padding: 12px;
    text-align: center;
    font-size: 16px;
  }

  th {
    font-weight: bold;
  }

  .begin {
    background-color: #fff8b3; /* light yellow */
  }

  .end {
    background-color: #d6d8ff; /* light blue */
  }

  .mid {
    background-color: #c8f7c5; /* light green */
  }
</style>
</head>

<body>

<table>
  <tr>
    <th rowspan="3">Day</th>
    <th colspan="3">Seminar</th>
  </tr>

  <tr>
    <th colspan="2">Schedule</th>
    <th rowspan="2">Topic</th>
  </tr>

  <tr>
    <th>Begin</th>
    <th>End</th>
  </tr>

  <!-- Monday -->
  <tr>
    <td rowspan="2">Monday</td>
    <td class="begin">8:00 a.m.</td>
    <td class="end">5:00 p.m.</td>
    <td>Introduction to XML</td>
  </tr>

  <tr>
    <td colspan="2"> </td>
    <td>Validity: DTD and Relax NG</td>
  </tr>

  <!-- Tuesday -->
  <tr>
    <td rowspan="3">Tuesday</td>
    <td class="begin">8:00 a.m.</td>
    <td class="begin">11:00 a.m.</td>
    <td>XPath</td>
  </tr>

  <tr>
    <td class="begin">11:00 a.m.</td>
    <td class="mid">2:00 p.m.</td>
    <td rowspan="2">XSL Transformations</td>
  </tr>

  <tr>
    <td class="mid">2:00 p.m.</td>
    <td class="end">5:00 p.m.</td>
  </tr>

  <!-- Wednesday -->
  <tr>
    <td>Wednesday</td>
    <td class="begin">8:00 a.m.</td>
    <td class="mid">12:00 p.m.</td>
    <td>XSL Formatting Objects</td>
  </tr>

</table>

</body>
</html>
