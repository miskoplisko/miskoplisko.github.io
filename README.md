<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Miskoplisko - Cybersecurity, Hacking, Pentesting, and Programming">
    <meta name="keywords" content="Cybersecurity, Hacking, Pentesting, Programming, Miskoplisko, Bananas">
    <meta name="author" content="Miskoplisko">
    <title>Miskoplisko's GitHub</title>
    <style>
        /* Importing Google Font */
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: #0d0d0d;
            color: #e0e0e0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            background-color: #1a1a1a;
            color: #ffcc00;
            padding: 20px 0;
            text-align: center;
            position: sticky;
            top: 0;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.6);
            z-index: 10;
        }

        header h1 {
            font-size: 3rem;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        section {
            max-width: 1000px;
            margin: 40px auto;
            padding: 20px;
            background-color: #1a1a1a;
            box-shadow: 0 0 15px rgba(255, 204, 0, 0.5);
            border-radius: 10px;
            transition: transform 0.3s;
        }

        section:hover {
            transform: scale(1.02);
        }

        h2 {
            color: #ffcc00;
            font-size: 2rem;
            margin-bottom: 20px;
            position: relative;
        }

        h2::before {
            content: '';
            width: 50px;
            height: 3px;
            background-color: #ffcc00;
            position: absolute;
            bottom: -10px;
            left: 0;
        }

        p, ul {
            line-height: 1.8;
        }

        ul {
            list-style: none;
        }

        ul li {
            background-color: #333;
            margin: 10px 0;
            padding: 15px;
            border-radius: 5px;
            font-weight: bold;
            color: #ffcc00;
            transition: background-color 0.3s ease;
        }

        ul li:hover {
            background-color: #ffcc00;
            color: #333;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #1a1a1a;
            color: #ffcc00;
            box-shadow: 0px -4px 10px rgba(0, 0, 0, 0.6);
            margin-top: auto;
        }

        a {
            color: #ffcc00;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        .banana {
            text-align: center;
            margin-top: 30px;
        }

        .banana img {
            width: 150px;
            animation: rotateBanana 5s linear infinite;
        }

        @keyframes rotateBanana {
            0% {
                transform: rotate(0deg);
            }
            50% {
                transform: rotate(360deg);
            }
            100% {
                transform: rotate(0deg);
            }
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            section {
                margin: 20px;
            }

            h2 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Miskoplisko</h1>
</header>

<section>
    <h2>About Me</h2>
    <p>Hey there! I'm <strong>Miskoplisko</strong>, a cybersecurity enthusiast, hacker, pentester, and programmer. I live and breathe code, and I'm constantly working on projects that challenge the boundaries of technology and security. I'm obsessed with solving complex problems and exploring the dark corners of the cyber world. 🔐</p>

    <h2>What I'm Studying</h2>
    <ul>
        <li>Advanced Cybersecurity Techniques</li>
        <li>Ethical Hacking and Pentesting</li>
        <li>Programming in Rust, Python, and C</li>
        <li>Network Security and Vulnerability Exploits</li>
    </ul>

    <h2>Current Projects</h2>
    <p>I'm currently working on several open-source projects involving network scanning, vulnerability detection, and penetration testing tools. Be sure to check out my <a href="https://github.com/miskoplisko" target="_blank">GitHub repositories</a> for the latest updates!</p>

    <h2>Fun Fact</h2>
    <p>Oh, and by the way, I absolutely love bananas 🍌. They fuel me during long coding sessions and are the perfect hacking snack!</p>

    <div class="banana">
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Banana-Single.jpg" alt="Banana">
    </div>
</section>

<footer>
    <p>Find my work on <a href="https://github.com/miskoplisko" target="_blank">GitHub</a> | Made with 💻 by Miskoplisko</p>
</footer>

</body>
</html>
