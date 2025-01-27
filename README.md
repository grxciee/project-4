<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Business Form</title>
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
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Enter your email address" required>
      
      <label for="tel">Phone Number:</label>
      <input type="tel" id="tel" name="tel" placeholder="Enter your phone number" required>
      
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Create a password" required>
    </fieldset>

    <fieldset>
      <legend>Business Preferences</legend>
      <label for="color">Brand Color:</label>
      <input type="color" id="color" name="color" value="#000000">

      <label for="services">Select Services:</label>
      <input type="checkbox" id="service1" name="services" value="Consulting"> Consulting
      <input type="checkbox" id="service2" name="services" value="Marketing"> Marketing
      <input type="checkbox" id="service3" name="services" value="Web Development"> Web Development
      
      <label for="range">Preferred Budget Range:</label>
      <input type="range" id="range" name="budget" min="1000" max="10000" step="500">
      
      <label for="date">Preferred Start Date:</label>
      <input type="date" id="date" name="start_date">
      
      <label for="time">Preferred Meeting Time:</label>
      <input type="time" id="time" name="meeting_time">
    </fieldset>

    <fieldset>
      <legend>File Upload</legend>
      <label for="file">Upload Business Logo:</label>
      <input type="file" id="file" name="file">
    </fieldset>

    <fieldset>
      <legend>Additional Information</legend>
      <label for="url">Website URL:</label>
      <input type="url" id="url" name="url" placeholder="Enter your website URL">

      <label for="search">Search for Services:</label>
      <input type="search" id="search" name="search" placeholder="Search...">

      <label for="hidden">Hidden Info:</label>
      <input type="hidden" id="hidden" name="hidden" value="business123">
    </fieldset>

    <fieldset>
      <legend>Options</legend>
      <label for="datetime-local">Select Date & Time:</label>
      <input type="datetime-local" id="datetime-local" name="datetime_local">

      <label for="month">Preferred Month:</label>
      <input type="month" id="month" name="month">

      <label for="week">Preferred Week:</label>
      <input type="week" id="week" name="week">

      <label>Gender:</label>
      <input type="radio" id="male" name="gender" value="Male"> Male
      <input type="radio" id="female" name="gender" value="Female"> Female
    </fieldset>

    <fieldset class="buttons">
      <input type="submit" value="Submit">
      <input type="reset" value="Reset">
      <input type="button" value="Click Me" onclick="alert('Button clicked!')">
      <input type="image" src="submit.png" alt="Submit" width="100">
    </fieldset>
  </form>
</body>
</html>
