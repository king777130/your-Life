<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>your Life</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background: url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1350&q=80') no-repeat center center fixed;
      background-size: cover;
      color: white;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.7);
    }
    .imgcontainer img {
      max-width: 200px;
      display: block;
      margin: 10px 0;
      border-radius: 8px;
    }
    .container {
      margin-top: 15px;
      background-color: rgba(0,0,0,0.5);
      padding: 15px;
      border-radius: 8px;
      max-width: 350px;
    }
    input[type=text], input[type=password] {
      width: 100%;
      padding: 8px;
      margin: 5px 0 15px 0;
      display: inline-block;
      border: none;
      border-radius: 4px;
      box-sizing: border-box;
    }
    button {
      background-color: #4CAF50;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-weight: bold;
    }
    button.cancelbtn {
      background-color: #f44336;
    }
    label {
      display: block;
      margin-bottom: 5px;
    }
    a {
      color: #f0e68c;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <h2>Hello</h2>
  <h1>Hi, I am Manoj</h1>
  <h3><strong>Welcome to this page</strong></h3>

  <a href="#">About</a>

  <p>I am a student from PU (<strong>Parul University</strong>)<br>
  This is my first HTML program.<br>
  I am very happy it worked and passed and excited for the next program.</p>

  <h3><strong>What I like</strong></h3>
  <ol>
    <li>Football</li>
    <li>To see movies</li>
    <li>To watch anime</li>
  </ol>

  <h4>Create your page</h4>

  <form action="action_page.php" method="post">
    <div class="imgcontainer">
      <img src="login2.jpg" alt="Login Image" />
    </div>

    <div class="container">
      <label for="uname"><b>Username</b></label>
      <input type="text" placeholder="Enter Username" name="uname" required />

      <label for="psw"><b>Password</b></label>
      <input type="password" placeholder="Enter Password" name="psw" required />

      <button type="submit">Login</button>

      <label>
        <input type="checkbox" checked="checked" name="remember" /> Remember me
      </label>
    </div>

    <div class="container" style="background-color: rgba(0,0,0,0.4); padding: 10px; margin-top: 10px;">
      <button type="button" class="cancelbtn">Cancel</button>
      <span class="psw">Forgot <a href="#">password?</a></span>
    </div>
  </form>

</body>
</html>
