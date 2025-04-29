<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome - Danford Chriss</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #add8e6; /* Light blue background */
            color: #333;
            text-align: center;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .landing {
            text-align: center;
        }
        .landing h1 {
            font-size: 3rem;
            margin-bottom: 1.5rem;
            color: #333;
        }
        .landing button {
            padding: 1rem 2rem;
            font-size: 1.2rem;
            color: white;
            background-color: #4CAF50;
            border: none;
            border-radius: 50px; /* Oval shape */
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }
        .landing button:hover {
            background-color: #45a049;
            transform: scale(1.05); /* Slight zoom effect */
        }
    </style>
</head>
<body>
    <div class="landing">
        <h1>Welcome to Danford Chriss' Portfolio</h1>
        <button onclick="enterPage()">Enter</button>
    </div>
    <script>
        function enterPage() {
            document.body.innerHTML = `
                <!-- Main content starts here -->
                ${document.body.innerHTML = `
                <iframe src="dan_inner.html" style="border:none;width:100%;height:100vh;"></iframe>`}
            `;
        }
    </script>
</body>
</html>
