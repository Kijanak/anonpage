<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Anonymous Message</title>
<style>
  body {
    background: black;
    color: white;
    font-family: Arial, sans-serif;
    text-align: center;
    padding: 40px;
  }
  input, textarea, button {
    width: 90%;
    max-width: 400px;
    margin: 10px auto;
    padding: 10px;
    border-radius: 5px;
    border: none;
    display: block;
    font-size: 16px;
  }
  button {
    background: #00ff99;
    cursor: pointer;
  }
  button:hover {
    opacity: 0.8;
  }
</style>
</head>
<body>

<h1>Send Anonymous Message</h1>
<p>Your identity is not recorded. Fill in a message and optional phone number.</p>

<form action="https://formsubmit.co/mrealist76@gmail.com" method="POST">
  <!-- Disable CAPTCHA -->
  <input type="hidden" name="_captcha" value="false">
  <!-- Email subject -->
  <input type="hidden" name="_subject" value="New Anonymous Message">

  <!-- Optional phone number -->
  <input type="text" name="phone" placeholder="Your phone number (optional)">

  <!-- Message box -->
  <textarea name="message" rows="6" placeholder="Type your message here..." required></textarea>

  <!-- Submit button -->
  <button type="submit">Send Anonymously</button>
</form>

</body>
</html> anonpage
Anonymous 
