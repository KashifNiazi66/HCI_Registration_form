<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Registration Form</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
      integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color:#e7e393;
      }
      header {
        background-color: #DD7230;
        color: #fff;
        padding: 10px;
        text-align: center;
      }
      .container {
        border: 2px solid #f4c95d;
        border-radius: 2%;
        max-width: 800px;
        margin: 100px auto 0 auto;
        padding: 20px;
      }
    
      .signup-box {
        margin-left: 193px;
        padding: 20px;
      }
      input {
        background-color: darkgray;
        border-radius: 10px;
        outline-style: none;
        outline-width: 0;
        font-size: 20px;
        display: inline-block;
        width: 50%;
        margin: 10px auto;
        padding: 5px 10px;
      }
      .btn {
        margin-left: 105px;
        margin-top: 10px;
        display: inline-block;
        padding: 10px 20px;
        background-color: #854d27;
        color: #fff;
        text-decoration: none;
        border-radius: 5px;
        transition: background-color 0.3s;
      }
      .btn:hover {
        background-color: #555;
      }
      .const {
        text-align: center;
      }
    </style>
  </head>
  <body>
    <header>
      <h1 class="heading">BiteBoss</h1>
      <h3 class="title">Registration Form</h3>
    </header>
    <div class="container">
      <!-- signup form -->
      <div class="signup-box">
        <i class="fa fa-user fa-lg"></i>
        <input
          type="text"
          class="name ele"
          placeholder="Enter your name"
          required
        />
        <br />
        <i class="fa fa-user fa-lg "></i>
        <input
          type="email"
          class="email ele"
          placeholder="youremail@email.com"
          required
        />
        <br />
        <i class="fa fa-lock fa-lg "></i>
        <input type="password" class="password ele" placeholder="password" />
        <br />
        <i class="fa fa-lock fa-lg "></i>
        <input
          type="password"
          class="password ele"
          placeholder="Confirm password"
          required
        />
        <br />

        <button class="btn">Signup</button>
      </div>
    </div>
    <div class="const">
      <h4>
        CAUTION
        <i class="fa-solid fa-triangle-exclamation fa-flip"></i>
      </h4>
      <p>
        A strong password typically consists of at least 8 characters that include a mix of uppercase and lowercase letters, numbers, 
        and symbols.
      </p>
    </div>
  </body>
</html>
