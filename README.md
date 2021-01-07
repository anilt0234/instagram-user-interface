# instagram-user-interface
I have created user interface of instagram with highly secured unique id .
<!DOCTYPE html>
<html>

<head>
  <script src="shared/jquery.js" type="text/javascript"></script>
  <script src="shared/shiny.js" type="text/javascript"></script>
  <link rel="stylesheet" type="text/css" href="shared/shiny.css"/>
</head>

<body>

  <h1>Instagram</h1>

  <p>
    <label>user ID</label> ***:</label><br />
    <select name="dist">
      <option value="norm">Normal</option>
      <option value="unif">Uniform</option>
      <option value="lnorm">Log-normal</option>
      <option value="exp">Exponential</option>
    </select>
  </p>

  <p>

    <label> share your daily routine  :</label><br />
    <input type="character" name="upload post  " value="0" min="1" max="1000" />

  </p>

  <h3>connect with us:</h3>
  <pre id="summary" class="shiny-text-output"></pre>

  <h3> we are connecting world  :</h3>
  <div id="plot" class="shiny-plot-output"
       style="width: 100%; height: 300px"></div>

  <h3> I made this as an  assignment :</h3>
  <div id="table" class="shiny-html-output"></div>

</body>
</html>
