# AI-Based Fertilizer Recommendation System
fertilizer_website/
│
├── index.html
├── style.css
├── script.js
└── images/
      urea.jpg
      dap.jpg
      npk.jpg
      compost.jpg
<!DOCTYPE html>
<html>
<head>
    <title>AI Fertilizer Recommendation</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">
    <h1>AI-Based Fertilizer Recommendation System</h1>

    <form id="fertilizerForm">
        <input type="number" id="nitrogen" placeholder="Nitrogen (N)" required>
        <input type="number" id="phosphorus" placeholder="Phosphorus (P)" required>
        <input type="number" id="potassium" placeholder="Potassium (K)" required>
        <input type="number" id="ph" placeholder="Soil pH" required>
        <button type="submit">Get Recommendation</button>
    </form>

    <div id="result"></div>
</div>

<script src="script.js"></script>
</body>
</html>
