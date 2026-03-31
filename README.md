<html>
<head>
  <title>Percentage Calculator</title>
</head>
<body>

<h2>Percentage Calculator</h2>

<input type="number" id="total" placeholder="Total Marks">
<input type="number" id="obtained" placeholder="Obtained Marks">

<button onclick="calc()">Calculate</button>

<p id="res"></p>

<script>
function calc(){
  let t = document.getElementById("total").value;
  let o = document.getElementById("obtained").value;

  let per = (o/t)*100;

  document.getElementById("res").innerText = per.toFixed(2) + "%";
}
</script>

</body>
</html>
