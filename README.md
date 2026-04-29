<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 20px;
        }
        main {
            padding: 20px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background: #45a049;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My Website</h1>
</header>

<main>
    <p>This is a simple website made with HTML, CSS, and a little JavaScript.</p>
    <button onclick="showMessage()">Click Me</button>
    <p id="message"></p>
</main>

<script>
    function showMessage() {
        document.getElementById("message").innerText = "You clicked the button!";
    }
</script>

</body>
</html>
