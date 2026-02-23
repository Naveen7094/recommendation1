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
body {
    font-family: Arial;
    background: linear-gradient(to right, #4CAF50, #2E7D32);
    text-align: center;
    color: white;
}

.container {
    background: white;
    color: black;
    padding: 30px;
    width: 400px;
    margin: 100px auto;
    border-radius: 10px;
}

input {
    width: 90%;
    padding: 10px;
    margin: 10px;
}

button {
    padding: 10px 20px;
    background: green;
    color: white;
    border: none;
    cursor: pointer;
}

img {
    width: 200px;
    margin-top: 20px;
}
