<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>School Fees Reminder 😂</title>  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #141e30, #243b55);
      color: white;
      text-align: center;
      padding: 40px 15px;
      margin: 0;
    }

    .box {
      background: white;
      color: #222;
      max-width: 350px;
      margin: 50px auto;
      padding: 25px;
      border-radius: 18px;
      box-shadow: 0 5px 20px #0005;
    }

    h1 {
      color: #e63946;
    }

    button {
      background: #e63946;
      color: white;
      border: none;
      padding: 14px 22px;
      border-radius: 10px;
      font-size: 17px;
      cursor: pointer;
      margin-top: 12px;
    }

    #message {
      display: none;
      margin-top: 20px;
      font-size: 20px;
      font-weight: bold;
      color: #198754;
    }
  </style></head><body>  <div class="box">
    <h1>🚨 SCHOOL FEES ALERT!</h1><p>Hello, student!</p>

<p>Your school fees are calling! 😂</p>

<button onclick="showMessage()">
  Check Your Fees
</button>

<div id="message">
  😂 GOT YOU! IT'S JUST A PRANK!
  <p>Relax, my friend. No fees are being collected!</p>
</div>

  </div>  <script>
    function showMessage() {
      document.getElementById("message").style.display = "block";
      alert("🚨 URGENT: PAY UP YOUR SCHOOL FEES! 😂");
    }
  </script></body>
</html>
