<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://fonts.googleapis.com/css2?family=Cardo:wght@700&display=swap" rel="stylesheet">
  <style>
    /* Center content */
    body {
      margin: 0;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background: white; /* Ensure background is visible */
      height: 100vh;
    }

    /* Main text style */
    .floating-text, .address-text {
      font-family: 'Cardo', serif;
      font-weight: bold;
      text-align: center;
      color: black;
      opacity: 0;
      animation: fadeUp 1s ease-out forwards;
    }

    /* Text sizes */
    .floating-text {
      font-size: 2.5rem;
    }

    .address-text {
      font-size: 1rem;
      margin-top: 5px;
    }

    /* Animation */
    @keyframes fadeUp {
      from {
        transform: translateY(10px);
        opacity: 0;
      }
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }
  </style>
</head>
<body>
  <div class="floating-text">CASA CHIC DECOR AND FURNITURE</div>
  <div class="address-text">204 Pierce St, Kingston, PA 18704</div>
</body>
</html>
