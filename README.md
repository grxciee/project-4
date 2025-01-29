<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> Business Form </title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    form {
      max-width: 600px;
      margin: auto;
    }
    fieldset {
      margin-bottom: 20px;
      border-radius: 8px;
      padding: 15px;
    }
    legend {
      font-size: 1.2em;
      font-weight: bold;
    }
    label {
      display: block;
      margin-top: 10px;
    }
    input, select, textarea {
      width: 100%;
      margin-top: 5px;
      padding: 8px;
      font-size: 1em;
    }
    input[type="radio"], input[type="checkbox"] {
      width: auto;
      margin-right: 5px;
    }
    .buttons {
      display: flex;
      gap: 10px;
      margin-top: 15px;
    }
  </style>
</head>
<body>
  <h1>Marketing Form</h1>
  <form method="post" action="process.php">
    <fieldset>
      <legend>Personal Details</legend>
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your full name" required>
      
     
  </form>
</body>
</html>
