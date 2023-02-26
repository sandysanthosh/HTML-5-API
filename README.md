# HTML-5- FORM 

```


<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Custom Signup Form</title>
    <style>
      /* Style the form container */
      .form-container {
        display: flex;
        flex-direction: column;
        max-width: 500px;
        margin: auto;
        padding: 20px;
        border: 1px solid #ccc;
        border-radius: 5px;
      }

      /* Style the form input fields */
      .form-container input[type=text], .form-container input[type=email], .form-container input[type=password] {
        width: 100%;
        padding: 12px 20px;
        margin: 8px 0;
        box-sizing: border-box;
        border: 2px solid #ccc;
        border-radius: 4px;
        font-size: 16px;
      }

      /* Style the form submit button */
      .form-container input[type=submit] {
        background-color: #4CAF50;
        color: white;
        padding: 12px 20px;
        border: none;
        border-radius: 4px;
        cursor: pointer;
        font-size: 16px;
      }

      /* Style the form submit button on hover */
      .form-container input[type=submit]:hover {
        background-color: #45a049;
      }
    </style>
  </head>
  <body>
    <div class="form-container">
      <h2>Sign Up</h2>
      <form action="/submit-form" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>

        <input type="submit" value="Sign Up">
      </form>
    </div>
  </body>
</html>



```


