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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Danford Chriss - Mobile Developer</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #e3f2fd, #f4f4f9);
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1.5rem 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
            margin-top: 0.5rem;
        }
        nav {
            text-align: center;
            margin: 1rem 0;
        }
        nav a {
            display: inline-block;
            margin: 0 1rem;
            padding: 0.5rem 1rem;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        nav a:hover {
            background-color: #45a049;
        }
        section {
            padding: 2rem;
            text-align: center;
        }
        .about, .faq, .location {
            margin-bottom: 3rem;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 2rem;
            max-width: 800px;
            margin: 2rem auto;
        }
        .about h2, .faq h2, .location h2 {
            color: #4CAF50;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            font-size: 0.9rem;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Danford Chriss</h1>
        <p>Mobile Developer | Innovator | Problem Solver</p>
        <nav>
            <a href="#about">About</a>
            <a href="#faq">FAQ</a>
            <a href="#location">Contact</a>
        </nav>
    </header>
    <section id="about" class="about">
        <h2>About Me</h2>
        <p>Hello! I'm Danford Chriss, a professional mobile developer with a passion for creating innovative and user-friendly mobile applications.</p>
        <p>I specialize in both Android and iOS development, leveraging modern tools and frameworks to deliver high-quality solutions tailored to client needs.</p>
        <h3>What is a Mobile Developer?</h3>
        <p>A mobile developer designs, builds, and maintains applications for mobile devices. This involves coding, testing, and optimizing apps for performance and user experience.</p>
        <h3>Skills</h3>
        <ul style="text-align: left; max-width: 600px; margin: 0 auto;">
            <li><strong>Programming Languages:</strong> Java, Kotlin, Swift, Dart</li>
            <li><strong>Frameworks:</strong> Flutter, React Native</li>
            <li><strong>Tools:</strong> Android Studio, Xcode, Firebase</li>
            <li><strong>APIs:</strong> RESTful APIs, GraphQL</li>
            <li><strong>Other Skills:</strong> UI/UX Design, Agile Development</li>
        </ul>
    </section>
    <section id="faq" class="faq">
        <h2>Frequently Asked Questions</h2>
        <p><strong>Q: What services do you offer?</strong></p>
        <p>A: I specialize in mobile app development for Android and iOS platforms, including UI/UX design and performance optimization.</p>
        <p><strong>Q: What technologies do you use?</strong></p>
        <p>A: I use Java, Kotlin, Swift, Dart, Flutter, and React Native, among other tools and frameworks.</p>
    </section>
    <section id="location" class="location">
        <h2>Location & Contact</h2>
        <p><strong>Location:</strong> Dar es Salaam, Tanzania</p>
        <p><strong>Phone:</strong> 0699500156</p>
    </section>
    <footer>
        <p>&copy; 2025 Danford Chriss. All rights reserved.</p>
    </footer>
