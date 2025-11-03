<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Box Model Exercise</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5f5f5;
      padding: 30px;
    }

    .box {
      background-color: #ffffff;
      border: 5px solid #4CAF50; /* border */
      padding: 20px; /* space inside */
      margin: 30px; /* space outside */
      width: 250px;
      text-align: center;
      box-shadow: 2px 2px 8px rgba(0, 0, 0, 0.1);
    }

    .box h2 {
      margin-bottom: 10px;
      color: #4CAF50;
    }

    .box p {
      color: #555;
      font-size: 14px;
    }

    .explain {
      margin-top: 20px;
      font-size: 15px;
    }

    .highlight {
      color: #4CAF50;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <h1>HTML & CSS Box Model Exercise</h1>
  <div class="box">
    <h2>My Box</h2>
    <p>This is a simple example of the <span class="highlight">Box Model</span>.</p>
  </div>

  <div class="explain">
    <p><span class="highlight">Content</span>: The text or image inside the box.</p>
    <p><span class="highlight">Padding</span>: Space between content and border.</p>
    <p><span class="highlight">Border</span>: The edge of the box.</p>
    <p><span class="highlight">Margin</span>: Space outside the border.</p>
  </div>
</body>
</html>
