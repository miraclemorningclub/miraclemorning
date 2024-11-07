<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Miracle Morning Club</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
            -webkit-font-smoothing: antialiased;
        }

        body {
            line-height: 1.4;
            color: #444;
            max-width: 1200px;
            margin: 0 auto;
            padding: 15px;
            background: #fff;
        }

        .logo-container {
            text-align: center;
            margin: 15px 0 25px;
        }

        .logo {
            width: 60px;
            height: 60px;
        }

        .hero {
            text-align: center;
            padding: 30px 20px;
            background: #fff;
            border: 1px solid #e0e0e0;
            border-radius: 2px;
            margin-bottom: 30px;
        }

        .hero h1 {
            font-size: 2.2em;
            margin-bottom: 15px;
            font-weight: 500;
            letter-spacing: -0.5px;
            white-space: nowrap;
        }

        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }

        .feature-box {
            background: #fff;
            padding: 25px;
            border: 1px solid #e0e0e0;
            border-radius: 2px;
        }

        .feature-box h3 {
            font-weight: 500;
            margin-bottom: 12px;
            letter-spacing: -0.3px;
        }

        .examples {
            background: #fff;
            padding: 25px;
            border: 1px solid #e0e0e0;
            border-radius: 2px;
            margin: 20px 0;
        }

        .examples h2 {
            font-weight: 500;
            letter-spacing: -0.3px;
        }

        .cta-button {
            display: inline-block;
            background: #444;
            color: #fff;
            padding: 12px 24px;
            border-radius: 2px;
            text-decoration: none;
            font-weight: 500;
            margin: 15px 0;
            transition: all 0.2s ease;
        }

        .cta-button:hover {
            background: #555;
        }

        .faq {
            margin: 30px 0;
        }

        .faq-item {
            margin-bottom: 8px;
        }

        .faq-question {
            background: #fff;
            padding: 15px;
            cursor: pointer;
            border: 1px solid #e0e0e0;
            border-radius: 2px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-weight: 500;
        }

        .faq-question:hover {
            background: #fafafa;
        }

        .faq-answer {
            display: none;
            padding: 15px;
            background: #fff;
            border: 1px solid #e0e0e0;
            border-top: none;
            margin-top: -1px;
        }

        .testimonials {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }

        .testimonial {
            background: #fff;
            padding: 25px;
            border: 1px solid #e0e0e0;
            border-radius: 2px;
        }

        .nav-menu {
            display: flex;
            justify-content: center;
            gap: 40px;
            padding: 15px 0;
            margin-bottom: 30px;
            border-bottom: 1px solid #e0e0e0;
        }

        .nav-menu a {
            color: #444;
            text-decoration: none;
            font-weight: 500;
            text-transform: uppercase;
            font-size: 13px;
            letter-spacing: 1px;
        }

        .nav-menu a:hover {
            text-decoration: underline;
        }

        h2 {
            font-weight: 500;
            letter-spacing: -0.3px;
            margin-bottom: 15px;
        }

        ul {
            list-style-type: none;
        }

        ul li {
            margin-bottom: 8px;
            padding-left: 15px;
            position: relative;
        }

        ul li:before {
            content: "–";
            position: absolute;
            left: 0;
        }

        p {
            font-weight: 400;
        }
    </style>
</head>
<body>
    <div class="logo-container">
        <svg class="logo" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
            <circle cx="50" cy="50" r="45" fill="none" stroke="#444" stroke-width="2"/>
            <circle cx="50" cy="50" r="20" fill="#444"/>
            <g stroke="#444" stroke-width="2">
                <line x1="50" y1="0" x2="50" y2="20" />
                <line x1="50" y1="80" x2="50" y2="100" />
                <line x1="0" y1="50" x2="20" y2="50" />
                <line x1="80" y1="50" x2="100" y2="50" />
                <line x1="14.6" y1="14.6" x2="29.2" y2="29.2" />
                <line x1="70.8" y1="70.8" x2="85.4" y2="85.4" />
                <line x1="14.6" y1="85.4" x2="29.2" y2="70.8" />
                <line x1="70.8" y1="29.2" x2="85.4" y2="14.6" />
            </g>
        </svg>
    </div>

    <nav class="nav-menu">
        <a href="#about">About</a>
        <a href="#gatherings">Gatherings</a>
        <a href="#community">Community</a>
        <a href="#apply">Apply</a>
    </nav>

    <div class="hero">
        <h1>our goal is to help you rise and shine ✨</h1>
        <p>Join a community of early risers who are committed to personal growth and success</p>
        <a href="#apply" class="cta-button">Apply to join (takes less than 5 minutes)</a>
    </div>

    <!-- Rest of the HTML remains the same -->

    <script>
        document.querySelectorAll('.faq-question').forEach(question => {
            question.addEventListener('click', () => {
                const answer = question.nextElementSibling;
                const isOpen = answer.style.display === 'block';
                answer.style.display = isOpen ? 'none' : 'block';
                question.querySelector('span').textContent = isOpen ? '+' : '-';
            });
        });
    </script>
</body>
</html>
