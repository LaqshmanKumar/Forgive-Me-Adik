index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>I'm Sorry</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(120deg, #f6d365, #fda085);
      color: #333;
      text-align: center;
      padding: 50px;
    }
    h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }
    p {
      font-size: 1.5rem;
      margin-bottom: 30px;
    }
    button {
      font-size: 1rem;
      padding: 10px 20px;
      background: #6a11cb;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: 0.3s;
    }
    button:hover {
      background: #2575fc;
    }
    #surprise {
      display: none;
      margin-top: 30px;
      font-size: 1.2rem;
      color: #6a11cb;
    }
  </style>
</head>
<body>
  <h1>I'm Sorry, Sis! 🙏</h1>
  <p>I know I might have hurt you, and I deeply regret it. Can you forgive me?</p>
  <button id="forgiveBtn">Forgive Me?</button>
  <div id="surprise">
    💖 Thank you for forgiving me! You’re the best sister ever. Let’s go for ice cream soon! 🍦
  </div>

  <script>
    document.getElementById("forgiveBtn").addEventListener("click", function () {
      const surprise = document.getElementById("surprise");
      surprise.style.display = "block";
    });
  </script>
</body>
</html>


---

