<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ta Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Press Start 2P', cursive;
            background: url('https://cdn.discordapp.com/attachments/1329706584267558983/1334752967219347517/image.png?ex=67a05011&is=679efe91&hm=ee89ef521804b7bb02221c91a7575c60fc7e994c5b416aa97021cbed3b0505ae&') no-repeat center center fixed;
            background-size: cover;
            color: #e0e0e0;
            line-height: 1.6;
            padding: 2rem;
        }

        header {
            background: #222;
            color: #101010; /* Neon black-ish color */
            padding: 1rem 0;
            text-align: center;
            border-radius: 10px;
            font-size: 2rem;
            box-shadow: 0 0 15px 5px rgba(16, 16, 16, 0.8);
        }

        header img {
            width: 50px;
            height: 50px;
            margin-right: 10px;
            vertical-align: middle;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            background: #333;
            padding: 1rem;
            border-radius: 10px;
            margin-top: 1rem;
        }

        nav ul li {
            margin: 0 1rem;
        }

        nav ul li a {
            color: #101010; /* Neon black-ish color */
            text-decoration: none;
            font-weight: bold;
            text-transform: uppercase;
            font-size: 1.2rem;
        }

        .hero {
            background: rgba(0, 0, 0, 0.6); /* Dark background with opacity */
            padding: 2rem;
            border-radius: 10px;
            text-align: center;
            margin-top: 2rem;
            box-shadow: 0 0 20px 5px rgba(16, 16, 16, 0.8);
        }

        .hero h1 {
            font-size: 3rem;
            color: #101010; /* Neon black-ish color */
            text-shadow: 0 0 15px #101010;
        }

        section {
            background: rgba(0, 0, 0, 0.7); /* Slightly transparent dark background */
            padding: 2rem;
            margin-top: 2rem;
            border-radius: 10px;
            box-shadow: 0 0 20px 5px rgba(16, 16, 16, 0.8);
        }

        .languages {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            text-align: center;
        }

        .language {
            background: #444;
            padding: 1.5rem;
            border-radius: 10px;
            box-shadow: 0 0 15px 5px rgba(16, 16, 16, 0.8);
            transition: transform 0.3s ease;
        }

        .language:hover {
            background: #555;
            transform: scale(1.05);
            box-shadow: 0 0 25px 5px rgba(16, 16, 16, 0.8);
        }

        footer {
            background: #000;
            color: #101010;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
            border-radius: 10px;
        }

        footer a {
            color: #101010;
            text-decoration: none;
        }

        .icon {
            width: 50px;
            height: 50px;
            margin-top: 1rem;
        }

        /* Ensure responsiveness */
        @media (max-width: 768px) {
            header {
                font-size: 1.5rem;
            }

            .hero h1 {
                font-size: 2rem;
            }

            nav ul {
                flex-direction: column;
                padding: 1rem;
            }

            nav ul li {
                margin: 0.5rem 0;
            }

            section {
                padding: 1rem;
            }

            .languages {
                grid-template-columns: 1fr 1fr;
                gap: 1rem;
            }

            .language {
                padding: 1rem;
            }
        }

        @media (max-width: 480px) {
            header {
                font-size: 1.2rem;
            }

            .hero h1 {
                font-size: 1.5rem;
            }

            .languages {
                grid-template-columns: 1fr;
                gap: 1rem;
            }

            .language {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <img src="https://imgs.search.brave.com/Sah4baMiU0hXgKllE_5cWzXMLPG7EAOt6xAyTGW1qe8/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly93YWxs/cGFwZXJzLmNvbS9p/bWFnZXMvZmVhdHVy/ZWQvY29kaW5nLWF2/ZnUwNDN5Mmt2NTJ3/aGEuanBn" alt="HTML Logo">
        Welcome to ta Website
    </header>

    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#languages">My Languages</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello, I'm a 14-year-old coder and I can make menus, websites, and more!</p>
    </section>

    <section id="languages">
        <h2>My Languages</h2>
        <div class="languages">
            <div class="language">
                <h3>Python</h3>
                <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" alt="Python" class="icon">
            </div>
            <div class="language">
                <h3>JavaScript</h3>
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" alt="JavaScript" class="icon">
            </div>
            <div class="language">
                <h3>HTML</h3>
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/HTML5_logo.svg" alt="HTML" class="icon">
            </div>
            <div class="language">
                <h3>C++</h3>
                <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg" alt="C++" class="icon">
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Got a question or want to team up? Hit me up at <a href="mailto:yusfxoshnawm@gmail.com">yusfxoshnawm@gmail.com</a>.</p>
    </section>

    <footer>
        <p>&copy; 2025 ta Website. Designed with passion and pixels. <a href="#">Back to top</a></p>
    </footer>

</body>
</html>
