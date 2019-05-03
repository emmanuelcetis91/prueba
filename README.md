<html>
<head>
<meta charset="utf-8" />
<title>Selectores avanzados en una tabla</title>
<style>
table, tr, th, td {
  border: 1px solid #333;
  line-height: 2em;
}
th {
  background-color: #FFCC99;
  padding: 0 .5em;
}
td {
  padding: 0 .3em;
}
th.chihuahua {
  background: #E6F3FF;
  padding: 0 .3em 0 1.2em;
}
th.pug {
  background: #E6F3FF;
  padding: 0 .3em 0 1.2em;
}
th.poddle {
  background: #E6F3FF;
  padding: 0 .3em 0 1.2em;
}
th.labrador {
  background: #E6F3FF;
  padding: 0 .3em 0 1.2em;
}
tr:nth-child(n+1) td {
  text-align: right;
}
tr:nth-child(2n) {
  background-color: #FF9999;
}
tr:hover {
  background: #66FF66;
}
</style>
</head>
<body>
<table>
  <tr>
    <th>Raza</th>
    <th>Pequeño</th>
    <th>Grande</th>
    <th>Edad</th>
    <th>Nombre</th>
  </tr>
  <tr>
    <th class="chihuahua">Chihuahua</th>
    <td>Si</td>
    <td>No</td>
    <td>6 meses</td>
    <td>luke</td>
  </tr>
  <tr>
    <th class="pug">Pug</th>
    <td>Si</td>
    <td>No</td>
    <td>7 meses</td>
    <td>eros</td>
  </tr>
  <tr>
    <th class="poddle">Poddle</th>
    <td>Si</td>
    <td>No</td>
    <td>5 meses</td>
    <td>Casper</td>
  </tr>
  <tr>
    <th class="labrador">Labrador</th>
    <td>No</td>
    <td>Si</td>
    <td>10 meses</td>
    <td>oddie</td>
  </tr>
</table>
</body>
</html>
